<!-- README.md is generated from README.Rmd. Please edit that file -->
This is a practice package for STAT 545. The purpose of the package is to make factors less annoying.

Here comes the defination for `fbind()`.

``` r
fbind <- function(a, b) {
  factor(c(as.character(a), as.character(b)))
}
```
