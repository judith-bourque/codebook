
<!-- README.md is generated from README.Rmd. Please edit that file -->

# codebook

<!-- badges: start -->
<!-- badges: end -->

The goal of codebook is to create codebooks in R.

## Create a codebook

``` r
# install.packages("codebookr")
library("codebookr")

study_codebook <- codebook(study)
print(study_codebook, "basic_study_codebook.docx")
```
