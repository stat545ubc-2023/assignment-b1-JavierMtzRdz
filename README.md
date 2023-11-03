# mda-project-template

## Author

Javier Martinez-Rodriguez

## Description

This repository contains the `indexing()` function, which creates an index from a variable based on specified observation(s).

### Repository Contents

This repository includes three documents:

-   [`indexing.rmd`](./indexing.rmd): This file contains the code to load the `indexing()` function, along with examples and tests.
-   [`indexing.md`](./indexing.rm): A markdown document compiled from `indexing.rmd`.
-   [`indexing_files`](./indexing_files/): This folder contains the necessary files for the markdown document.

## How to Run Code from This Repository

### Pre-requisites

1.  Ensure you have R and RStudio installed on your computer. Download R from [CRAN](https://cran.r-project.org/) and RStudio from [rstudio.com](https://www.rstudio.com/).

### Steps

#### Clone the Repository using RStudio

1.  Launch RStudio.
2.  Go to `File -> New Project`.
3.  Choose `Version Control`.
4.  Select `Git`.
5.  In the "Repository URL" field, paste the GitHub repository URL.
6.  Choose where to save the repository in the "Create project as a subdirectory of" field.
7.  Click `Create Project`.

#### Install Required Packages

1.  Open the R console within RStudio.
2.  Run the following code on the console.

```         
install.packages("tidyverse")
install.packages("rlang")
install.packages("gapminder")
install.packages("testthat")
```

#### Run the Code

1.  If the code is in an R script, you can run it by clicking `Source`.
2.  If the code is in an R Markdown file, you can knit the document by clicking the `Knit` button.

#### Troubleshooting

-   If you encounter errors or missing packages, the error messages usually provide clues about what's missing or needs fixing.
