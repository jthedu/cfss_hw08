# Homework 08: Collecting and analyzing data from the web (Julia Du)

Detailed instructions for this homework assignment are [here](https://cfss.uchicago.edu/homework/webdata/).

## Executing the files

For Part 1 (exploring `gapminder` data), you can find the source code at [gapminder.Rmd](gapminder.Rmd) and the rendered report at [gapminder.md](gapminder.md). 


For Part 2 (creating & analyzing our own dataset), you can find the source code at [hw08_p2.Rmd](hw08_p2.Rmd) and the rendered report at [hw08_p2.md](hw08_p2.md).

There's nothing special about running these files - just open the .Rmd files & knit them to get the .md rendered reports.

**Note**: be sure to register for an API key with the geonames.org website. You'll need this key (in this case, your username) to access the info from geonames for running [gapminder.Rmd](gampinder.Rmd). (I discuss this in more detail there as well.)

## Required packages

You should have the following packages installed:

```r
library(reprex)
library(tidyverse)

library(geonames)
library(countrycode)
library(gapminder)
library(tidymodels)

library(stringr)
library(rvest)
library(glue)
```

The 2nd chunk of packages are needed for gapminder.Rmd & allow you to access country information and run a statistical learning model. The 3rd chunk is needed to scrape a website in hw08_p2.Rmd.
