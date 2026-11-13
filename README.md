# survMisc

A collection of functions to help in the analysis of right-censored survival data, extending the methods in the survival package.

Compatibility updates by Renova.

Version 0.5.6.9001 makes three metadata and documentation changes and no R code change. The stale optional `Date` field was removed. The single author is now also listed in an `Authors@R` entry, and the `Author` field reads `Chris Dardis [aut, cre]`; the person and maintainer address are unchanged. In `man/sf.Rd`, `{data.table}` in the `\value` section is written as `\code{data.table}`.

## Install

From R-universe:

```r
install.packages("survMisc", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or the exact release tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/survMisc@renova-0.5.6.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

survMisc was written by Chris Dardis (maintainer). License: GPL-2 (see [COPYING](COPYING)).
