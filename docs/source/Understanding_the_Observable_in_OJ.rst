=========================================
Relating Observable to Observable-Jupyter
=========================================

At the most basic level, Observable-Jupyter is a library for embedding Observable cells in a Jupyter notebook. To better understand what this means, it's helpful to start by describing what Observable is and why it can be useful for Python-based programming.

What is Observable?
-------------------
Observable is a cell-based platform for JavaScript programming. It functions in a similar way to how
Jupyter notebooks and Google Colab work for Python programming. Observable cells can contain JavaScript,
HTML/CSS, or Markdown.

Observable provides a few key capabilities:

.. card:: 

    JavaScript
    ^^^
    As a JavaScript platform, Observable natively supports popular visualization libraries such
    as d3, Leaflet/MapBox/MapLibre, and others.
    

.. card::

    Topological Dependencies
    ^^^
    Unlike Jupyter notebooks, where values are updated in the order that cells are run, Observable
    maintains a dependency graph behind the scenes. This means that when the value of a variable 
    changes, all cells that depend on that value re-run automatically. This improve reproducibility
    and enables techniques such as literate programming by eliminating the need to structure the
    notebook around the order in which cells must be run.

.. card::           

    Interactivity
    ^^^
    Because it is based on web technologies, building interactive elements in Observable requires
    only a basic knowledge of JavaScript. This also means that any visualizations developed 
    via Observable are easily incorporated into web apps and other front-end frameworks. This cannot
    be said of the native Python interactive elements.

Observable Community
--------------------

Observable is not just software. It is also a community of data practitioners who are passionate
about visualization.

All published Notebooks on Observable are open source and it is common for users to build off of each others work. 
This is great news for Observable-Jupyter users since it means that there are countless visualizations at our 
fingertips that we can simply modify, embed, and use in our own projects.


Observable vs Observable-Jupyter
--------------------------------
 
It is best to think of Observable-Jupyter as a program that works in collaboration with Observable.

Given that a majority of the data science community works with python, Observable Jupyter looks to introduce python 
users to Observable by giving them access to visualizations that are made with powerful visualization libraries like d3. 

Observable-Jupyter gives Python users access to Observable visualizations by using APIs provided by Observable to pass data back and forth essentially allowing Python users to modify
existing Observable notebooks for their own personal projects. 

.. note::
   Check out how to embed visualizations into your own project in the :doc:`Embedding_cells` section. 


Additional Observable Resources
-------------------------------

| Interested in learning more about Observable?
| Take a look at the following links:

.. hlist::
   :columns: 1
   
   * :bdg-link-primary-line:`Obsevable<https://observablehq.com/explore>`
   * :bdg-link-primary-line:`Observable for Jupyter Users<https://observablehq.com/@observablehq/observable-for-jupyter-users>`
   * :bdg-link-primary-line:`Visualize a data frame with Observable, in Jupyter<https://observablehq.com/@observablehq/visualize-a-data-frame-with-observable-in-jupyter>`
