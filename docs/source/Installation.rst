=============================
Installing Observable-Jupyter
=============================

To get started using Observable-Jupyter, first install the library using pip.
This can be done a few ways.

.. card::
   **From the Command Line**
   ^^^

   .. code-block:: console

      pip install observable_jupyter

.. card::
   **From a Notebook Cell**
   ^^^

   .. code-block:: console

      !pip install observable_jupyter

Once you have installed Observable-Jupyter open up a .py or .ipynb file and run the following
block of code to make sure the installation worked properly and that you have the latest version
of Observable-Jupyter.

.. code:: python
   
   import observable_jupyter
   print(observable_jupyter.__version__)

.. note::
   
   The latest version of Observable-Jupyter is currently version 0.1.13

Now that you have Observable-Jupyter properly installed check out the :doc:`Embedding_cells` section to get
started embedding visualizations from Observable into your python code.
