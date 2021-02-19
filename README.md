
<!-- README.md is generated from README.Rmd. Please edit that file -->

# The gedcompendium <img src='man/figures/logo.png' align="right" height="138" />

<!-- badges: start -->

[![R-CMD-check](https://github.com/jl5000/gedcompendium/workflows/R-CMD-check/badge.svg)](https://github.com/jl5000/gedcompendium/actions)
<!-- badges: end -->

This meta-package loads the `gedcompendium` ecosystem of packages to
enable the handling of `tidyged` objects (tibble representations of
GEDCOM files), and the main package of this ecosystem is
[`tidyged`](https://jl5000.github.io/tidyged/).

<img src="man/figures/allhex.png" width="65%" style="display: block; margin: auto;" />

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("jl5000/gedcompendium")
```

## Use

You can load `tidyged` and all of its associated packages at once:

``` r
library(gedcompendium)
#> Loading required package: tidyged
#> Loading required package: visged
#> Loading required package: tidyged.io
#> When importing existing GEDCOM files, you should ensure that they are error free.
#> This package assumes imported GEDCOM files are valid and very few validation checks are carried out.
#> Several GEDCOM validators are available, including an online validator at http://ged-inline.elasticbeanstalk.com/
#> Loading required package: autoged
```
