
<!-- README.md is generated from README.Rmd. Please edit that file -->

# jmpwashdata

<!-- badges: start -->
<!-- badges: end -->

The goal of jmpwashdata is to provide a snapshot of the JMP WASH
household, WASH in schools and WASH in health care facilities data that
is normally available in Excel sheets on <https://washdata.org>. The
data is loaded in the package since the data is updated at the moment no
more often than once a year.

## Installation

You cannot yet install from [CRAN](https://CRAN.R-project.org). You must
build it from source and install that. The easiest way to do this is
with devtools.

``` r
install.packages("devtools")
```

# Install JMP package with devtools

The easiest way is to install the package from Github using devtools.

``` r
devtools::install_github("WASHNote/jmpwashdata")
```

Otherwise you can also close the repository and open it in RStudio to
build the source code package and install it locally if you would like
to contribute to the package. For example:

``` r
if (length(grep(pattern = "jmpwashdata", x = installed.packages()[,"Package"])) == 0) {
  devtools::install_local("~/RStudio/packages/jmpwashdata_0.1.2.tar.gz")
}
```

# Changes

-   v.0.1.3 November 2021 Addition of extraction of regional and world
    school and healthcare facility datasets.
-   v.0.1.2 October 2021 Update of data files to include the new world
    and region files and changes in other files and to add more error
    handling. Includes now the data summary sheets found in the
    inequality files parsed to be in a cleaner long format.
-   v.0.1.1 July 2021 New published data files extracted with the 2019
    and 2020 data sets from JMP Excel sheets.
-   v.0.1.0 June 2021 Extraction of 2017 JMP files.
