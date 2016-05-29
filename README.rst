========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |codacy|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/pyeo/badge/?style=flat
    :target: https://readthedocs.org/projects/pyeo
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/renemilk/pyeo.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/renemilk/pyeo

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/renemilk/pyeo?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/renemilk/pyeo

.. |requires| image:: https://requires.io/github/renemilk/pyeo/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/renemilk/pyeo/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/renemilk/pyeo/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/renemilk/pyeo

.. |codecov| image:: https://codecov.io/github/renemilk/pyeo/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/renemilk/pyeo

.. |landscape| image:: https://landscape.io/github/renemilk/pyeo/master/landscape.svg?style=flat
    :target: https://landscape.io/github/renemilk/pyeo/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg?style=flat
    :target: https://www.codacy.com/app/renemilk/pyeo
    :alt: Codacy Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/pyeo.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/pyeo

.. |downloads| image:: https://img.shields.io/pypi/dm/pyeo.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/pyeo

.. |wheel| image:: https://img.shields.io/pypi/wheel/pyeo.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/pyeo

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pyeo.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/pyeo

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pyeo.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/pyeo


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD license

Installation
============

::

    pip install pyeo

Documentation
=============

https://pyeo.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
