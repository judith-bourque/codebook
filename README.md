
<!-- README.md is generated from README.Rmd. Please edit that file -->

# codebook

<!-- badges: start -->
<!-- badges: end -->

The goal of codebook is to create codebooks in R.

## Create a codebook

With [codebookr](https://brad-cannell.github.io/codebookr/):

``` r
# install.packages("codebookr")
library("codebookr")

study_codebook <- codebook(study)
print(study_codebook, "basic_study_codebook.docx")
```

With [codebook](https://github.com/rubenarslan/codebook):

``` r
# install.packages("codebook")
library("codebook")

new_codebook_rmd()
```
