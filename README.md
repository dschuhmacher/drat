
## `drat` repository for R packages

This [R](https://www.r-project.org/) package repository is powered by Dirk Eddelbuettel's `drat` package ([CRAN](https://cran.r-project.org/package=drat), [GitHub](https://github.com/eddelbuettel/drat), [docs](https://eddelbuettel.github.io/drat)).  

It contains bundled versions of [my](https://github.com/dschuhmacher) non-CRAN R packages, especially the ones used in "Suggests" fields of other packages.

The repository is primarily meant to be used from within an R session like this:
```r
available.packages(repos="https://dschuhmacher.github.io/drat")
install.packages("kanjistat.data", repos="https://dschuhmacher.github.io/drat")
```
