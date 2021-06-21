## Table Contents
* [General-info](general-info)
* [Screenshots](screenshots)
* [Technologies](technologies)
* [Setup](setup)
* [Libraries](libraries)
* [Code-Samples](code-examples)

## General-Info
To get familliar with the *library (janitor)*, i developed this  project.

## Dataset 
The csv file was downloaded from Kaggle. 
Includes data from AIRBNB platoform for the city of New York
 ```
            1. host_id
            2. host_name
```
           
 
## Images
![NA_values_visualization](https://user-images.githubusercontent.com/47696240/96313024-86642600-1015-11eb-9144-d0880d6d5b35.png)


![head(df)](https://user-images.githubusercontent.com/47696240/96313011-8106db80-1015-11eb-9cc1-aa807257d406.png)


## Languages
* The project was developed with R programming language.

## Environment
* RStudio

## Libraries
```R
library(naniar)
library(tidyverse)
library(dplyr)
library(readr)
library(visdat)
library(janitor)
```
## Setup
```R
setwd('')
df = read_csv('AB_NYC_2019.csv')
```

## Code_Samples
```
glimpse(df) 
class(df) 
options(scipen = 999) 
summary (df)
# turning off scientific notation
```


