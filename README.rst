========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - | |github-actions| |travis|
        | |coveralls|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |travis| image:: https://api.travis-ci.com/jidn/idid.svg?branch=main
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/jidn/idid

.. |github-actions| image:: https://github.com/jidn/idid/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/jidn/idid/actions

.. |coveralls| image:: https://coveralls.io/repos/jidn/idid/badge.svg?branch=main&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/jidn/idid

.. |version| image:: https://img.shields.io/pypi/v/idid.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/idid

.. |wheel| image:: https://img.shields.io/pypi/wheel/idid.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/idid

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/idid.svg
    :alt: Supported versions
    :target: https://pypi.org/project/idid

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/idid.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/idid

.. |commits-since| image:: https://img.shields.io/github/commits-since/jidn/idid/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/jidn/idid/compare/v0.0.0...main



.. end-badges

Track what I did

* Free software: MIT license

Installation
============

::

    pip install idid

You can also install the in-development version with::

    pip install https://github.com/jidn/idid/archive/main.zip


Documentation
=============


To use the project:

.. code-block:: python

    import idid
    idid.longest()


Development
===========

To run all the tests run::

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
