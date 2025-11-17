# `regMMD`: an `R` package for parametric estimation and regression with maximum mean discrepancy

*This document provides a complete introduction to the template based on
the `regMMD` package for `R`, that implements minimum distance
estimation in various parametric and regression models using the maximum
mean discrepancy (MMD) metric.*

[![build and publish](https://github.com/computorg/published-202511-alquier-regmmd/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202511-alquier-regmmd/actions/workflows/build.yml)
[![DOI:10.57750/d6d1-gb09](https://img.shields.io/badge/DOI-10.57750/d6d1--gb09-034E79.svg)](https://doi.org/10.57750/d6d1-gb09)
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)
[![reviews](https://img.shields.io/badge/review-report-blue.png)](https://github.com/computorg/published-202511-alquier-regmmd/issues?q=is%3Aopen+is%3Aissue+label%3Areview)

### Authors

- [Pierre Alquier](https://pierrealquier.github.io/) (ESSEC Business School)
- [Mathieu  Gerber](https://research-information.bris.ac.uk/en/persons/mathieu-gerber) (University of Bristol)

### Abstract

The Maximum Mean Discrepancy (MMD) is a kernel-based metric widely used
for nonparametric tests and estimation. Recently, it has also been
studied as an objective function for parametric estimation, as it has
been shown to yield robust estimators. We have implemented MMD
minimization for parameter inference in a wide range of statistical
models, including various regression models, within an `R` package
called `regMMD`. This paper provides an introduction to the `regMMD`
package. We describe the available kernels and optimization procedures,
as well as the default settings. Detailed applications to simulated and
real data are provided.
