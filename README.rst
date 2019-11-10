.. |binder| image:: https://mybinder.org/badge_logo.svg
.. _binder: https://mybinder.org/v2/gh/mfarragher/appelpy-examples/master

.. |nbviewer| image:: https://img.shields.io/badge/render-nbviewer-orange.svg
.. _nbviewer: https://nbviewer.jupyter.org/github/mfarragher/appelpy-examples/tree/master/

=================================================================================
appelpy: Example notebooks
=================================================================================
About 👁️
=====================
`appelpy <https://github.com/mfarragher/appelpy>`_ is the *Applied Econometrics Library for Python*.  It seeks to bridge the gap between the software options that have a simple syntax (such as Stata) and other powerful options that use Python's object-oriented programming as part of data modelling workflows.  ⚗️

This **appelpy-examples** repo contains notebooks that demonstrate some of the functions of appelpy applied to econometric datasets.

This repo can be launched in with **nbviewer** or **Binder** (click on the badges in the table below).

+----------------+-----------------------------------------------------------------------+
| Notebooks      | Info                                                                  |
+================+=======================================================================+
| |nbviewer|_    | Launch the repo and see static notebook output in nbviewer            |
+----------------+-----------------------------------------------------------------------+
| |binder|_      | Launch the repo and explore notebooks interactively with Binder.      |
+----------------+-----------------------------------------------------------------------+

Get started with the **10 Minutes To Appelpy** notebook to see the main features in action on `The California Test Score Data Set <https://rdrr.io/cran/Ecdat/man/Caschool.html>`_:

- Exploratory data analysis
    - Statistical moments
- Model estimation
    - Fit OLS model (non-robust and HC1 standard errors)
    - Model selection stats
    - Standardized estimates (e.g. beta coefficients)
- Model diagnostics
    - Plots, e.g. P-P plot
    - Heteroskedasticity tests
    - `BadApples` class
        - Leverage vs residuals squared plot
        - Influence, outliers and leverage

Note
=====================
As more features and functionality are added, more notebooks will be pushed to this repo.

The aim is to have notebooks numbered sequentially (the notebooks with most general and basic features are first in sequence).

Some output is compared to the results of other software (e.g. Stata) where possible.
