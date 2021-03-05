# Homework 08: Collecting and analyzing data from the web (Julia Du)

Detailed instructions for this homework assignment are [here](https://cfss.uchicago.edu/homework/webdata/).

## Executing the files

For Part 1 (exploring `gapminder` data), you can find the source code at [gapminder.Rmd](gapminder.Rmd) and the rendered report at [gapminder.md](gapminder.md). 


For Part 2 (creating & analyzing our own dataset), you can find the source code at [hw08_p2.Rmd](hw08_p2.Rmd) and the rendered report at [hw08_p2.md](hw08_p2.md).

You will need to retrive your own unique API key (SPEAK MORE ON THIS) and store it in your own .Rprofile.

There's nothing special about running these files - just open the .Rmd files & knit them to get the .md rendered reports.

## Required packages

You should have the following packages installed:

```r
library(reprex)
library(tidyverse)
library(knitr)
library(lubridate)
library(tidymodels)

library(usemodels)
library(kknn)
library(glmnet)
library(xgboost)
library(vip)

```
2nd chunk of packages are more specialized - most of these are needed for running the specific models we use.
# hw08