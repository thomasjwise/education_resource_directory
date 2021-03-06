---
title: Session Setup
weight: 10
---

## Before the Session 

* Ensure [R](<https://www.r-project.org/>)/[Rstudio](<https://rstudio.com/>) is installed and ready to use, on your machine. Or create a virtual session via [RStudio Cloud](<https://rstudio.cloud/>)
* Either open up a blank R script, or download and open a copy of the worksheet from the [Github Repo](<https://github.com/thomasjwise/dataviz_business>). 
* Ensure the following *R Packages* are correctly installed and loaded on your machine, using the following code. 

```r

## Install Packages 
  install.packages("tidyverse")
  install.packages("RColorBrewer")

## Load Packages 
  library(tidyverse)
  library(RColorBrewer)

```

* Ensure you can load and access the data used within the session, this can be downloaded from the [Github Repo](<https://github.com/thomasjwise/dataviz_business>) and can be loaded using the code: 

```r

WDB_1999 <- read.csv("data/WBD_1999.csv")

```

## Additional Note: 

* For those following this workshop via a company, please follow your specific company policy on accessing R & Rstudio. 
* These will be provided by your organization. 