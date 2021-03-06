
<!-- README.md is generated from README.Rmd. Please edit that file -->

# myRexerc

<!-- badges: start -->
<!-- badges: end -->

A package with some R programming exercises compiled with ‘learner’.

Beware: all the material must be considered experimental, in full
development, not yet tested.

Caveat emptor: use it at your own risk.

## Installing the package

You can install the development version of ‘myRexerc’ from the
repository at [GitHub](https://github.com/maxbre/myRexerc/) with:

``` r
if(!require("devtools")) install.packages("devtools")
devtools::install_github("maxbre/myRexerc")
```

## Running the exercises

You need to install the package ‘learnr’ before running the exercises
within the pakage ‘myRexerc’ and then give a try to the `test_me`
exercise:

``` r
if(!require("learnr")) install.packages("leranr")
learnr::run_tutorial("test_me", package = "myRexerc")
```

then you’ll probably go ahead with the `00_initial_setup` for checking
everything is fine with your system set-up:

``` r
learnr::run_tutorial("00_initial_setup", package = "myRexerc")
```

and finally going through the first exercie by:

``` r
learnr::run_tutorial("01_basic", package = "myRexerc")
```
