
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->
<!-- badges: end -->

The goal of mypackage is to help you understand your libraries…

## Installation

You can install the development version of mypackage from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("sungoose/mypackage")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(mypackage)
## basic example code
lib_summary()
#>                                                                                        Library
#> 1                        /Library/Frameworks/R.framework/Versions/4.3-x86_64/Resources/library
#> 2 /private/var/folders/_h/wpv1sqh556z9dmfj5l4gc5kw0000gn/T/Rtmp16RIr2/temp_libpath27802f863819
#>   n_packages
#> 1        166
#> 2          1
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
