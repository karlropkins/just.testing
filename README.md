
<!-- README.md is generated from README.Rmd. Please edit that file -->

# just.testing

<!-- badges: start -->
<!-- badges: end -->

The goal of just.testing is to …

## Installation

You can install the released version of just.testing from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("just.testing")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("karlropkins/just.testing")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(just.testing)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(example.data)
#>        id              ans    
#>  Min.   :  1.00   h      : 8  
#>  1st Qu.: 25.75   o      : 7  
#>  Median : 50.50   v      : 7  
#>  Mean   : 50.50   i      : 6  
#>  3rd Qu.: 75.25   m      : 6  
#>  Max.   :100.00   j      : 5  
#>                   (Other):61
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/master/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
