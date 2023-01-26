# Documentation

Contributing to documentation on readthedocs.org

## Environment Setup

### With `pip`

```bash
python3 -m venv observable-jupyter
source observable-jupyter/bin/activate
pip install -r requirements.txt
```

### With `conda`

```bash
conda create -n observable-jupyter --file environment.yml
conda activate observable-jupyter
```

## Add a demo to the Gallery

* Create a jupyter notebook that runs an observable-jupyter visualization
* Create a thumbnail (right now we do this with a screen shot) and put it in source/thumbnail/images
  * Sphinx looks for this thumbnail in the Jupyter notebook, the notebook should have the following line...
  ```
  ADD THE CODE HERE
  ```
* Put the notebook in ./source
* Add an entry for the thumbnail in source/conf.py to the `nbsphinx_thumbnails` dictionary
* Add an entry for the notebook in source/VisualizationLibrary.rst
* Rebuild the HTML (see above)

## Build

The recommended method of building is using the `Makefile`:

```
make html
```

This will generate the static site in the [./build/](./build/) directory. To view the site, open [./build/html/index.html](./build/html/index.html).

## Contributing

* Commit your changes to a new branch and push to GitHub
* Open a pull request. Once reviewed and approved, your changes will be visible on [readthedocs.org](https://observable-jupyter.readthedocs.io/en/latest/).

