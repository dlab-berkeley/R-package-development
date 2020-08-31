
# R Package Development Workshop

by [Jae Yeon Kim](https://jaeyk.github.io/)

File an [issue](https://github.com/dlab-berkeley/R-package-development/issues) if you have problems, questions or suggestions.

## Overview

Developing your own R package is a great way to reuse and distribute your R code. The workshop aims to demonstrate that developing and distributing an R package is easy to do, if you know how to write functions and use Git and GitHub.

## Learning objectives

- Developing your first and minimally viable R package

## Prerequisites

I assume students have familiarity R and Git and GitHub.

If you haven't done, please install Git and sign up a new GitHub account.

- Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

- [Sign up a GitHub account](https://docs.github.com/en/github/getting-started-with-github/signing-up-for-a-new-github-account). Also, don't forget to [set up your user name and email](https://kbroman.org/github_tutorial/pages/first_time.html).


## Setup

Please install required packages manually before attending the workshop:

```r

# package manager
install.packages("pacman")
library(pacman)

# install pkgs
pacman::p_load(
    devtools, # key package 
    usethis, # workflow management 
    testthat, # for testing 
    roxygen2, # for documentation 
    pkgdown # to build a package website
)

```

# References
- [R Packages](http://r-pkgs.had.co.nz/) by Hadley Wickam (O'Reily 2015)
  - [The second edition](https://r-pkgs.org/) is now under development written by Hadley Wickam and Jerry Bryan.
- [Writing an R package from scratch](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/) by Hilary Parker
- [R package primer](https://kbroman.org/pkg_primer/) by Karl Broman
- [usethis workflow for package development](https://www.hvitfeldt.me/blog/usethis-workflow-for-package-development/) by Emil Hvitfeldt 

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
