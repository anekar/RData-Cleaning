# Project Name

## Table of contents
* [General-info](general-info)
* [Screenshots](screenshots)
* [Technologies](technologies)
* [Setup](setup)
* [Libraries](libraries)
* [Code-Examples](code-examples)



## General-info
1. In order to get familliar with the *library (janitor)*, i developed this data cleaning project.
2. About the data. 
    * The csv file was downloaded from Kaggle
    * Includes data from AIRBNB in the city of New York such as
        1. host_id
        2. host_name
           
 
## Screenshots

![NA values](NA_Values_Visualization.png)



![head](head(df).png)

##Technologies
* The project was developed with RStudio.

## Libraries
```R
library(naniar)
library(tidyverse)
library(dplyr)
library(readr)
library(visdat)
library(janitor)
```
##Setup
```R
setwd('')
df = read_csv('AB_NYC_2019.csv')
```



##Code - Examples
```aidl
glimpse(df) # getting a sense of the data 
class(df)
options(scipen = 99) # for scientific notation
```


