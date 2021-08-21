---
title: Session Setup
weight: 10
---

## Before the Session

* Ensure [R](<https://www.r-project.org/>)/[Rstudio](<https://rstudio.com/>) is installed and ready to use, on your machine. Or create a virtual session via [RStudio Cloud](<https://rstudio.cloud/>). Instructions for how to set up and install this software on your ONS device can be found through Yammer or the IT service desk.
* Either open up a blank R script, or download and open a copy of the worksheet from the [Github Repo](<https://github.com/thomasjwise/aRt_with_R>).
* Ensure the following *R Packages* are correctly installed and loaded on your machine, using the following code.

```r

## Install Packages
  install.packages("tidyverse")
  install.packages("caret")
  install.packages("tree")
  install.packages("rpart")
  install.packages("rpart.plot")
  install.packages("e1071")

## Load Packages
  library(tidyverse)
  library(caret)
  library(tree)
  library(rpart)
  library(rpart.plot)
  library(e1071)

```
