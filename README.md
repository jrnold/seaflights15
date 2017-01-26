# seaflights15

This package contains information about all flights that departed or arrived from SEA in 2015.
To help understand what causes delays, it also includes a number of other useful datasets:

- weather: hourly meterological data for each airport
- planes: construction information about each plane
- airports: airport names and locations
- airlines: translation between two letter carrier codes and names

This package was inspired was inspired by [nycflights13](https://github.com/hadley/nycflights13), 
and built with [groundcontrol](https://github.com/jrnold/groundcontrol) which generates R data-only packages like **nycflights** for
the user's choice of aiports and years.

## Install

This package is not on CRAN.
You can install it using [devtools](https://cran.r-project.org/package=devtools),
```r
devtools::install_github("jrnold/seaflights15")
```
