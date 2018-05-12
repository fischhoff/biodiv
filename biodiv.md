biodiv
================
Ilya
5/12/2018

install packages
----------------

``` r
#install package dplyr if not already installed
list.of.packages <- c("dplyr", "leaflet", "shiny", "rgdal", "raster", "sp", "data.table")
new.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
if(length(new.packages)) install.packages(new.packages)
print(new.packages)
```

    ## character(0)
