# Pagedreport and Pagedown to generate pretty reports in R

This repository contains a basic tutorial on the usage of the R packages *pagedown* and *pagedreport*.

Please refer to the authors website of both packages for more details:

-   pagedown: <https://pagedown.rbind.io/>
-   pagedreport: <https://pagedreport.rfortherestofus.com/>
-   Great intro and tutorial: <https://rfortherestofus.com/2022/11/no-designer-needed/>

## Install

The package *pagedown* is in CRAN, to install it just run this command in the R console:

``` r
install.packages("pagedown")
```

The package *pagedreport* is not in CRAN, to install it from the R console:

``` r
remotes::install_github("rfortherestofus/pagedreport", ref = "main")
```

If the *remotes* object is not installed, install it from the R console:

``` r
install.packages("remotes")
```

### Dependencies

In Ubuntu based operating systems, the following dependencies might need to be installed from the system's console:

-   rsvg

```         
sudo apt install librsvg2-dev
```

-   magick

```         
sudo apt install libmagick++-dev
```

-   curl

```         
sudo apt install libcurl4-openssl-dev
```
