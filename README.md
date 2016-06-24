
<!-- README.md is generated from README.Rmd. Please edit that file -->
ctsem allows for easy specification and fitting of a range of continuous and discrete time dynamic models, including multiple indicators (dynamic factor analysis), multiple, potentially higher order processes, and time dependent (varying within subject) and time independent (not varying within subject) covariates. Classic longitudinal models like latent growth curves and latent change score models are also possible. Version 1 of ctsem provided SEM based functionality by linking to the OpenMx software, allowing mixed effects models (random means but fixed regression and variance parameters) for multiple subjects. For version 2 of the R package ctsem, we include a Bayesian specification and fitting routine that uses the Stan probabilistic programming language, via the rstan package in R. This allows for all parameters of the dynamic model to individually vary, using an estimated population mean and variance, and any time independent covariate effects, as a prior. ctsem version 1 is documented in a forthcoming JSS publication (Driver, Voelkle, Oud, in press), and in R vignette form at <https://cran.r-project.org/web/packages/ctsem/vignettes/ctsem.pdf> . The new Bayesian approach is outlined in the vignette, Intro to Hierarchical Continuous Time Dynamic Modelling with ctsem. To cite ctsem please use the citation("ctsem") command in R.
