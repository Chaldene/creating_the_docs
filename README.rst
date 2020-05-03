=================
Creating the Docs
=================


.. image:: https://img.shields.io/pypi/v/creating_the_docs.svg
        :target: https://pypi.python.org/pypi/creating_the_docs

.. image:: https://img.shields.io/travis/chaldene/creating_the_docs.svg
        :target: https://travis-ci.org/chaldene/creating_the_docs

.. image:: https://readthedocs.org/projects/creating-the-docs/badge/?version=latest
        :target: https://creating-the-docs.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status




An attempts to build an example repo with sphinx built-in

The folder was built using my local cookiecutter use of pipenv.
First activate my general python virtualenv

Then use the command:

.. code:: console

   > cookiecutter templatedir -o outputdir

This creates the template directory completed by the wizard.

To compile the docs, again ensure the environment with sphinx is activated then run

.. code:: python

   sphinx-build -b sphinx-build -b html sourcedir builddir

For the nice readthedocs template
Template: https://github.com/readthedocs/sphinx_rtd_theme
                


* Free software: BSD license
* Documentation: https://creating-the-docs.readthedocs.io.


Features
--------

* TODO

Credits
-------

This package was created with Cookiecutter_ and the `elgertam/cookiecutter-pipenv`_ project template, based on `audreyr/cookiecutter-pypackage`_.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`elgertam/cookiecutter-pipenv`: https://github.com/elgertam/cookiecutter-pipenv
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
