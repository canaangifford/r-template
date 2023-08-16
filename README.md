
<!-- README.md is generated from README.Rmd. Please edit that file -->

# r-template

Templated R Project with useful structure

## Initial Installation

Install the latest version of renv globally from CRAN with: Note: This
should be done globally via `R` on the cmdline. See:
<https://github.com/rstudio/renv>

``` r
install.packages("renv")
```

Pandoc is required to generate the README as well as use .Rmd files. If
you are using RStudio you can ‘Knit’ or run via the cmdline. If you are
not using RStudio you will have to install pandoc
[globally](https://pandoc.org/installing.html).

``` r
rmarkdown::render('README.Rmd')
```

Install the project and all out-of-the-box packages with:

``` r
renv::install()
```
