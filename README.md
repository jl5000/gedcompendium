
<!-- README.md is generated from README.Rmd. Please edit that file -->

# The gedcompendium <img src='man/figures/logo.png' align="right" height="138" />

<!-- badges: start -->

[![R-CMD-check](https://github.com/jl5000/gedcompendium/workflows/R-CMD-check/badge.svg)](https://github.com/jl5000/gedcompendium/actions)
[![](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
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
#> Loading required package: tidyged.utils
#> Loading required package: visged
#> Loading required package: tidyged.io
#> When importing existing GEDCOM files, you should ensure that they are error free.
#> This package assumes imported GEDCOM files are valid and very few validation checks are carried out.
#> Several GEDCOM validators are available, including an online validator at http://ged-inline.elasticbeanstalk.com/
```

## State of the ecosystem

### tidyged.internals

[![R-CMD-check](https://github.com/jl5000/tidyged.internals/workflows/R-CMD-check/badge.svg)](https://github.com/jl5000/tidyged.internals/actions)
[![](https://codecov.io/gh/jl5000/tidyged.internals/branch/main/graph/badge.svg)](https://codecov.io/gh/jl5000/tidyged.internals)

### tidyged

[![R-CMD-check](https://github.com/jl5000/tidyged/workflows/R-CMD-check/badge.svg)](https://github.com/jl5000/tidyged/actions)
[![](https://codecov.io/gh/jl5000/tidyged/branch/master/graph/badge.svg)](https://codecov.io/gh/jl5000/tidyged)

### tidyged.io

[![R-CMD-check](https://github.com/jl5000/tidyged.io/workflows/R-CMD-check/badge.svg)](https://github.com/jl5000/tidyged.io/actions)
[![](https://codecov.io/gh/jl5000/tidyged.io/branch/main/graph/badge.svg)](https://codecov.io/gh/jl5000/tidyged.io)

### tidyged.utils

[![R-CMD-check](https://github.com/jl5000/tidyged.utils/workflows/R-CMD-check/badge.svg)](https://github.com/jl5000/tidyged.utils/actions)
[![](https://codecov.io/gh/jl5000/tidyged.utils/branch/main/graph/badge.svg)](https://codecov.io/gh/jl5000/tidyged.utils)

### shinyged

Not started

### visged

[![R-CMD-check](https://github.com/jl5000/visged/workflows/R-CMD-check/badge.svg)](https://github.com/jl5000/visged/actions)
[![](https://codecov.io/gh/jl5000/visged/branch/master/graph/badge.svg)](https://codecov.io/gh/jl5000/visged)

### autoged

Not started

### geddown

Not started
