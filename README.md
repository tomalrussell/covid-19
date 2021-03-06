Spatial Impact Modelling of COVID-19
=================================

Description
===========

The **covid-19** repo models the potential spatial impacts of covid-19.

See [notebook](https://github.com/edwardoughton/covid-19/blob/master/scripts/Spatial%20exposure%20notebook.ipynb) for calculations.


Run using conda
==============

The recommended installation method is to use conda, which handles packages and virtual
environments, along with the conda-forge channel which has a host of pre-built libraries and
packages.

Create a conda environment called covid-19:

    conda create --name covid-19 python=3.7

Activate it (run this each time you switch projects):

    conda activate covid-19

First, install optional packages:

    conda install fiona shapely rtree pyproj

Then run script:

    python scripts/lads.py

Contributors
============
- Edward J. Oughton (University of Oxford)
