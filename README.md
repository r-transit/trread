[![Travis-CI Build
Status](https://travis-ci.com/r-transit/trread.svg?branch=master)](https://travis-ci.com/r-transit/trread)
[![CRAN
status](http://www.r-pkg.org/badges/version-ago/trread?)](https://cran.r-project.org/package=trread)
[![Project Status: Active](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active) 
[![](https://cranlogs.r-pkg.org/badges/trread)](https://cran.r-project.org/package=trread)

# trread

Use trread to calculate transit
frequencies, and validate transit feeds. trread reads the [General Transit Feed Specification](http://gtfs.org/) into dataframes.

If you need to work with map data consider using [tidytransit](https://github.com/r-transit/trread/).

## Installation

This package requires a working installation of
[sf](https://github.com/r-spatial/sf#installing).

A CRAN version is available:

``` r
install.packages('trread')
```

For the development version from Github:

```
# install.packages("devtools")
devtools::install_github("r-transit/trread")
```

# Usage

Please see:

- [the tutorial](http://trread.r-transit.org/articles/introduction.html)   
- [the reference](http://trread.r-transit.org/reference/index.html).   


# Background

trread is a
[fork](https://en.wikipedia.org/wiki/Fork_\(software_development\)) of
[gtfsr](https://github.com/ropensci/gtfsr), published to
[CRAN](https://cran.r-project.org/), with frequency/headway calculation
functions. 

# Contributing

If you would like to contribute please feel free to issue a pull request or [open an issue](https://github.com/r-transit/trread/issues/new).

# Contributors

Among the many
[contributors](https://github.com/r-transit/trread/graphs/contributors),
[Danton Noriega](https://github.com/dantonnoriega) wrote much of this
package.
