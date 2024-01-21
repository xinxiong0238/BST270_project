# BST 270 Individual Project

This repository contains my attempt to reproduce figures from FiveThirtyEight's [Congress Today Is Older Than It's Ever Been](https://fivethirtyeight.com/features/aging-congress-boomers/). 

## Compute environment

This project uses the R (≥ 3.6.0) programming language. Five R pacakges are required to run the code:

* dplyr (1.1.4)
* stringr (1.5.1)
* tidyr (1.3.0)
* plotly (4.10.4)
* RColorBrewer (1.1-3)

## Project Structure

The entire reproduction attempt is located in `./code/reproduction.Rmd`. An knitted html version is also included in the `./code` directory.

This repo comes with a `./data` directory including the csv file 'data_aging_congress.csv' required to reproduce the figure. It was originally provided by fivethirtyeight. More detailed documentation about the Congress demographic data can be found in their [github](https://github.com/fivethirtyeight/data/tree/master/congress-demographics) page.
