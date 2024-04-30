=====================================================
nsbi: Simulation Based Inference with Nested Sampling
=====================================================
:nsbi: Simulation Based Inference with Nested Sampling 
:Author: Will Handley
:Version: 0.0.0
:Homepage: https://github.com/handley-lab/nsbi
:Documentation: http://nsbi.readthedocs.io/

.. image:: https://github.com/handley-lab/nsbi/actions/workflows/unittests.yaml/badge.svg?branch=master
   :target: https://github.com/handley-lab/nsbi/actions/workflows/unittests.yaml?query=branch%3Amaster
   :alt: Unit test status
.. image:: https://github.com/handley-lab/nsbi/actions/workflows/build.yaml/badge.svg?branch=master
   :target: https://github.com/handley-lab/nsbi/actions/workflows/build.yaml?query=branch%3Amaster
   :alt: Build status
.. image:: https://codecov.io/gh/handley-lab/nsbi/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/handley-lab/nsbi
   :alt: Test Coverage Status
.. image:: https://readthedocs.org/projects/nsbi/badge/?version=latest
   :target: https://nsbi.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status
.. image:: https://badge.fury.io/py/nsbi.svg
   :target: https://badge.fury.io/py/nsbi
   :alt: PyPi location
.. image:: https://anaconda.org/handley-lab/nsbi/badges/version.svg
   :target: https://anaconda.org/handley-lab/nsbi
   :alt: Conda location
.. image:: https://zenodo.org/badge/705730277.svg
   :target: https://zenodo.org/doi/10.5281/zenodo.10009816
   :alt: Permanent DOI for this release
.. image:: https://img.shields.io/badge/license-MIT-blue.svg
   :target: https://github.com/handley-lab/nsbi/blob/master/LICENSE
   :alt: License information


A repository for linear modelling and simulation based inference

UNDER CONSTRUCTION


Features
--------

Installation
------------

``nsbi`` can be installed via pip

.. code:: bash

    pip install nsbi

via conda

.. code:: bash

    conda install -c handley-lab nsbi

or via the github repository

.. code:: bash

    git clone https://github.com/handley-lab/nsbi
    cd nsbi
    python -m pip install .

You can check that things are working by running the test suite:

.. code:: bash

    python -m pytest
    black .
    isort --profile black .
    pydocstyle --convention=numpy nsbi


Dependencies
~~~~~~~~~~~~

Basic requirements:

- Python 3.6+
- `anesthetic <https://pypi.org/project/anesthetic/>`__

Documentation:

- `sphinx <https://pypi.org/project/Sphinx/>`__
- `numpydoc <https://pypi.org/project/numpydoc/>`__

Tests:

- `pytest <https://pypi.org/project/pytest/>`__

Documentation
-------------

Full Documentation is hosted at `ReadTheDocs <http://nsbi.readthedocs.io/>`__.  To build your own local copy of the documentation you'll need to install `sphinx <https://pypi.org/project/Sphinx/>`__. You can then run:

.. code:: bash

    python -m pip install ".[all,docs]"
    cd docs
    make html

and view the documentation by opening ``docs/build/html/index.html`` in a browser. To regenerate the automatic RST files run:

.. code:: bash

    sphinx-apidoc -fM -t docs/templates/ -o docs/source/ nsbi/

Citation
--------

If you use ``nsbi`` to generate results for a publication, please cite
as: ::

   Handley et al, (2024) nsbi: Simulation Based Inference with Nested Sampling

or using the BibTeX:

.. code:: bibtex

   @article{nsbi,
       year  = {2023},
       author = {Will Handley et al},
       title = {nsbi: Simulation Based Inference with Nested Sampling},
       journal = {In preparation}
   }


Contributing
------------
There are many ways you can contribute via the `GitHub repository <https://github.com/handley-lab/nsbi>`__.

- You can `open an issue <https://github.com/handley-lab/nsbi/issues>`__ to report bugs or to propose new features.
- Pull requests are very welcome. Note that if you are going to propose major changes, be sure to open an issue for discussion first, to make sure that your PR will be accepted before you spend effort coding it.
- Adding models and data to the grid. Contact `Will Handley <mailto:wh260@cam.ac.uk>`__ to request models or ask for your own to be uploaded.


Questions/Comments
------------------
