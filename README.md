<!-- README.md is generated from README.Rmd. Please edit that file -->

# Binary_Segmentation R_CPP Package

<!-- badges: start -->

[![License: GPL
v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![GitHub repo
size](https://img.shields.io/github/repo-size/Prapti-044/Binary_Segmentation)
![GitHub code size in
bytes](https://img.shields.io/github/languages/code-size/Prapti-044/Binary_Segmentation)
![GitHub language
count](https://img.shields.io/github/languages/count/Prapti-044/Binary_Segmentation)
![GitHub top
language](https://img.shields.io/github/languages/top/Prapti-044/Binary_Segmentation)
<!-- badges: end -->

The goal of Binary Segmentation is to learn how to create an R-package by
implementing [Binary_Segmentation
algorithm](https://arxiv.org/abs/1801.00718) efficiently
using C++ for binary segmentation of the data points.

*Note*: This RMarkdown is created following the guidelines of [this
R-package example](https://github.com/mvuorre/exampleRPackage).

## Installation

You can only install the development version from [this
repository](https://github.com/Prapti-044/Binary_Segmentation) with:

``` r
# install.packages("devtools")
devtools::install_github("Prapti-044/Binary_Segmentation")
```

## Example

This is a basic example which shows you how to perform binary segmentation in datasets:

``` r
library(BINSEG)
x <- c(0.1, 0, 1, 1.1, 0.1, 0)
result <- apply_binseg(x, 3)
result
$loss
[1] -0.8816667  0.4600000  2.1680000

```
