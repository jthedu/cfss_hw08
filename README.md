# Homework 08: Collecting and analyzing data from the web (Julia Du)

Detailed instructions for this homework assignment are [here](https://cfss.uchicago.edu/homework/webdata/).

## Executing the files

For Part 1 (exploring `gapminder` data), you can find the source code at [gapminder.Rmd](gapminder.Rmd) and the rendered report at [gapminder.md](gapminder.md). 

For Part 2 (creating & analyzing our own dataset), I scraped a website. You can find the scraping source code at [hw08_p2.Rmd](hw08_p2.Rmd) and the rendered report at [hw08_p2.md](hw08_p2.md).

For the sake of knowing how to use an API, I also used the NYT Article Search API and looked at coverage of Obama's stance on gay marriage. You can find the API source code at [hw08-p2-API.Rmd](hw08-p2-API.Rmd) and rendered report at [hw08-p2-API.md](hw08-p2-API.md). **In terms of grading, feel free to ignore this API .Rmd file** (and just grade the scraping files), though I'd appreciate feedback if you have the bandwidth.

There's nothing special about running these files - just open the .Rmd files & knit them to get the .md rendered reports.

**Note**: be sure to register for an API key with the geonames.org website. You'll need this key (in this case, your username) to access the info from geonames for running [gapminder.Rmd](gampinder.Rmd). (I discuss this in more detail there as well.)
The same goes for the NYT API. You'll need to register for a key and add it to your .Rprofile before running the [hw08-p2-API.Rmd](hw08-p2-API.Rmd) file.

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

library(jsonlite)
library(httr)
library(lubridate)
```

The 2nd chunk of packages are needed for gapminder.Rmd & allow you to access country information and run a statistical learning model. The 3rd chunk is needed to scrape a website in hw08_p2.Rmd. The 4th chunk is needed to use an API in hw08-p2-API.Rmd.
