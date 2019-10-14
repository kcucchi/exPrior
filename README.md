
<!-- README.md is generated from README.Rmd. Please edit that file -->
exPrior
=======

<!-- badges: start -->
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Travis build status](https://travis-ci.org/GeoStat-Bayesian/exPrior.svg?branch=master)](https://travis-ci.org/GeoStat-Bayesian/exPrior) <!-- badges: end -->

Recent papers have made the case that geostatistics in subsurface hydrology is still falling short on available software tools ([Rubin et al., 2018](https://www.hydrol-earth-syst-sci.net/22/5675/2018/)) and that Bayesian inference is the most relevant framework for subsurface statistics ([Hesse et al., 2019](https://www.frontiersin.org/articles/10.3389/feart.2019.00118/full)). The exPrior package, providing tools for Bayesian inference, is therefore a timely addition to the R ecosystem of geostatistical tools.

The aim of this package is to provide practitioners of geostatistics a tool to derive *ex-situ priors* for Bayesian inference in hydrogeology. Ex-situ priors summarize hydrogeological knowledge from studies at similar sites ([Cucchi et al., 2019](https://www.sciencedirect.com/science/article/abs/pii/S0309170818309059)). The main features of the package are:

-   generate prior distributions based on external, ie, ex-situ, data only, therefore meeting the likelihood principle,
-   account for possible autocorrelation in these ex-situ data, therefore avoiding the problem of Pseudoreplication,
-   account for available soft data, say, in the form of expert information on bounds and moments,
-   comes bundled with the largest open-source database on hydrogeological parameters (batteries included), etc.

Installation
------------

exPrior is not yet on CRAN. You can install the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("GeoStat-Bayesian/exPrior")
```

Example
-------

Examples on how to use exPrior can be found in the vignettes in the /vignettes folder.

Documentation
-------------

A publication detailing the algorithm can be found at [Cucchi et al. (2019)](https://www.sciencedirect.com/science/article/abs/pii/S0309170818309059). A publication detailing the package and how to use it is in preparation.
