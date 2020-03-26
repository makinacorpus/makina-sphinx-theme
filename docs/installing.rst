************
Installation
************

Via Git or Download
===================

Symlink or subtree the ``makinacorpus/makina-sphinx-theme`` repository into your documentation at
``docs/_themes/sphinx_makina_theme`` then add the following two settings to your Sphinx
``conf.py`` file:

.. code:: python

    html_theme = "sphinx_makina_theme"
    html_theme_path = ["_themes", ]
