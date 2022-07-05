# MPIDR Geocomputation Workshop

This repository contains code, data, and images for a workshop on geocomputation in R.

All presentation materials and code are in the Rmarkdown file `demo.Rmd`. To run this file from start to finish, ensure the following packages are installed:

  * `tidyverse`
  * `tidycensus`
  * `sf`
  * `nngeo`
  * `patchwork`
  * `censusxy`
  
Also, to access data from tidycensus, complete this two step process:

  1. Apply for a Census api key [at this link](http://api.census.gov/data/key_signup.html)
  2. Register it in R with `tidycensus::census_api_key("[your_key]", install = TRUE)`
