<!-- README.md is generated from README.Rmd. Please edit that file -->

# r-template

Templated R Project skeleton with useful structure and packages

## Initial Installation

1.  Install `R` via homebrew or [CRAN](https://cran.r-project.org/bin/).

2.  Just start `R` in the project directory and `renv` will begin setup!
    (Go grab a :coffee: as this will take a while…)

### Dependency Conflicts

Pandoc *may* be required to generate the README as well as use .Rmd
files. If you are using RStudio you can ‘Knit’ or run the following via
the cmdline. If you are not using RStudio you may have to install pandoc
[globally](https://pandoc.org/installing.html).

    rmarkdown::render('README.Rmd', 'md_document')

Package dependencies can sometimes conflict with local r caches.
Typically following the suggested fixes via `renv` or homebrew will
resolve the conflicts.

#### *OPTIONAL* - Install the latest version of renv globally from CRAN with:

    cd ~/
    R

then

    install.packages("renv")

## Components

This template is mainly comprised with the following tools and aggregate
packages.  
[renv](https://rstudio.github.io/renv/articles/renv.html)  
[Tidyverse](https://www.tidyverse.org/)
