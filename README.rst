*****************************************************
Deploying Django Projects as Python Packages Workshop
*****************************************************

Python has a powerful, versatile and fast packaging toolchain consisting of
setuptools, pip and wheel. Why not use this toolchain to package and deploy
Django projects instead of pushing complete Git repositories to servers?

In this workshop you will learn how to structure your Django project, so that
it can be packaged as a Python package. You will learn about the advantages for
development and deployment, as well as the pitfalls you have to be aware of.

This workshop was held at

* `DjangoCon Europe 2016 <https://2016.djangocon.eu/>`_ in Budapest
* `Leipzig Python User Group <http://www.python-academy.de/User-Group/>`_ in April 2016

Requirements
============

You have to install the following requirements to build and serve the
presentation:

- `npm <https://www.npmjs.com/>`_
- `Python 3 <https://www.python.org/>`_

Installing and linking the dependencies
=======================================

Install and link all required resources:

::

    $ make link

Running the presentation
========================

Serve the slides:

::

    $ make serve

License
=======

This work is licensed under a
`Creative Commons Attribution 4.0 International License <http://creativecommons.org/licenses/by/4.0/>`_.
