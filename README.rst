Welcome to the Geocom Python Framework (GPF)
============================================

|python| |status| |pypi| |build| |issues| |docs|

.. |python| image:: https://img.shields.io/pypi/pyversions/gpf3?logo=python
    :alt: Python version(s)

.. |status| image:: https://img.shields.io/pypi/status/gpf3
    :alt: PyPI status

.. |pypi| image:: https://img.shields.io/pypi/v/gpf3?logo=pypi
    :alt: PyPI homepage
    :target: https://pypi.org/project/gpf3

.. |build| image:: https://img.shields.io/appveyor/ci/geocom/gpf3?logo=appveyor
    :alt: AppVeyor
    :target: https://ci.appveyor.com/project/geocom/gpf3

.. |issues| image:: https://img.shields.io/github/issues-raw/geocom-gis/gpf3?logo=github
    :alt: GitHub issues
    :target: https://github.com/geocom-gis/gpf3/issues

.. |docs| image:: https://img.shields.io/readthedocs/gpf3?logo=read%20the%20docs
    :alt: Documentation
    :target: https://gpf3.readthedocs.io/en/latest/

Purpose
-------

The *Geocom Python Framework* or ``gpf`` provides a set of Python modules that contain tools, helpers, loggers etc. for a more pleasant Python scripting experience with `ArcGIS Pro`_.
GIS users who need to write geoprocessing scripts with ``arcpy`` might benefit from importing the ``gpf`` module into their script as well.

The ``gpf`` module in this repository has been developed for **Python 3.6+ (ArcGIS Pro, Server)**.
However, it is also available for Python 2.7.14+ (ArcGIS Desktop/Server) on `GitHub <https://github.com/geocom-gis/gpf>`_ and `PyPI <https://pypi.org/project/gpf>`_.

Geocom customers who need to write GEONIS menu or form scripts should be aware of the gntools_ module.
However, this module is not available for ArcGIS Pro, as it is Python 2.7 only.

.. _ArcGIS Pro: https://www.esri.com
.. _GEONIS: https://geonis.com/en/solutions/framework/geonis
.. _gntools: https://pypi.org/project/gntools

Requirements
------------

- ArcGIS Pro 2.3 or higher
- Python 3.6 or higher (along with the ``arcpy`` module)

Installation
------------

The easiest way to install the Geocom Python Framework, is to use the built-in package manager in ArcGIS Pro.
Navigate to Options > Python and select the environment in which you wish to install the ``gpf`` package.

Alternatively, you can use pip_, a Python package manager.
When ``pip`` is installed, the user can simply run:

    ``python -m pip install gpf3``

.. note::   Although the PyPI package is called ``gpf3``, the name of the import package is ``gpf``.
            This means, that you can import it into your own modules using ``import gpf``.

.. _pip: https://pip.pypa.io/en/stable/installing/

Documentation
-------------

The complete ``gpf`` documentation can be found at `Read the Docs`_.

.. _Read the Docs: https://gpf3.readthedocs.io/

License
-------

`Apache License 2.0`_ � 2019 Geocom Informatik AG / VertiGIS & contributors

.. _Apache License 2.0: https://github.com/geocom-gis/gpf3/blob/master/LICENSE