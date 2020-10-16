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
![NA_values_visualization](https://user-images.githubusercontent.com/47696240/96313024-86642600-1015-11eb-9144-d0880d6d5b35.png)
<br>

![head(df)](https://user-images.githubusercontent.com/47696240/96313011-8106db80-1015-11eb-9cc1-aa807257d406.png)


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


