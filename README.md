# Primordial non-Gaussianity Simulations

This `<README.md>` summarizes the main codes that were used during the project. It comes with the Jupyter Notebook `<nonG_notebook.ipynb>` that shows examples of performed simulations.

The folder modules contains six Python tool files:

* `<colorednoise.py>` contains functions that can generate 1D colored noise. It is used for ICA simulations.

* `<correlationfunctions.py>` contains routines to compute statistics of random fields, including power spectrum, CDF and PDF.

* `<filters.py>` allows to smooth a given field on a 3D lattice for a specified window function (e.g. in Fourier space) and a chosen scale.

* `<fouriertransform.py>` adapts numpy's fast fourier transforms to the considered situations

* `<gaussianfield.py>` generates Gaussian random fields on a 3D lattic for a given power spectrum.

* `<peaks.py>` is used to either add uncorrelated peaks of a given shape to a 3D field, or map a 3D field into an $F_{NL}$ function.

The Jupyter Notebook `<nonG_notebook.ipynb>` explains how the different functions were used and how to perform some of the calculations. [`<nbodykit>`](https://nbodykit.readthedocs.io/) was used in some cases to compare the results. 

The folder `<DataCAMB>` contains the data of CDM transfer function generated using [`<CAMB>`](https://camb.info/) at redshift z=0.

The folder `<Report>` contains the report I submitted to Ecole polytechnique, and the slides of the presentation in front of my Ecole polytechnique professors at IAP.

The folder `<Plots>` contains various plots of the results.
