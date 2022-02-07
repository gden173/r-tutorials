r-tutorials
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

# Description

This project contains `R` code and data for a series of introductory
programming and data analysis tutorials with the `R` programming
language.

# Installation

To download and use this code on a windows machine, open the Git Bash
terminal and clone the repository into directory.  
Try to make sure the directory is something like `~/Projects`, (where
`~` signifies the user home directory), just so there are no issues with
accessing the project.

To do this process, copy and paste the following lines of code into the
git bash terminal.

``` bash
$ mkdir ~/Projects # Make a projects directory if it doesn't exist
$ cd ~/Projects # Move to the project directory
$ git clone https://github.com/gden173/r-tutorials.git # Clone the repository into this directory
$ cd r-tutorials # Move into the project directory
```

# Initial Project Setup

To make sure you have everything installed correctly, double click on
the `Rstudio` project file `r-tutorials.Rproj` which will open up `R`
studio into the project.

The, go to the `R` console and run the following lines of code

``` r
> install.packages('renv') # R package manager
> renv::hydrate() # Downloads all packages that you will need, all of the same version that I will be using. 
```

This will download and install all the necessary `R` packages that (most
likely) you will ever need, and that will be needed to run this
analysis.  
Installation of the `tidyverse` package will take \~10 minutes, so it is
better to do these steps ahead of time.

# Project Structure

This project has been structured similar to an `R` package, just so it
has all the necessary tools for analysis. All `R` source code will be
placed in the `R/` directory (we probably won’t add anything to this),
and all data will be placed in the `data/` directory.

# Tutorial Structure

The tutorial are placed inside `Rmarkdown` templates. To access these
templates got to `File > New File > R Markdown`. A box should pop up
asking about the `R Markdown` configurations that you will like. From
here, say that you would like to use an `R Markdown` template. After
clicking on this option a list of templates will be shown, to select the
appropriate tutorial click on `r-tutorial_XX`.

## Tutorial 01

TODO: Add instructions

# References

``` r
citation()
#> 
#> To cite R in publications use:
#> 
#>   R Core Team (2020). R: A language and environment for statistical
#>   computing. R Foundation for Statistical Computing, Vienna, Austria.
#>   URL https://www.R-project.org/.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {R: A Language and Environment for Statistical Computing},
#>     author = {{R Core Team}},
#>     organization = {R Foundation for Statistical Computing},
#>     address = {Vienna, Austria},
#>     year = {2020},
#>     url = {https://www.R-project.org/},
#>   }
#> 
#> We have invested a lot of time and effort in creating R, please cite it
#> when using it for data analysis. See also 'citation("pkgname")' for
#> citing R packages.
```
