# Data Wrangling Exercise 2: Dealing with Missing Values
## Author: Narcel Reedus
## Data: titanic_original.csv
# 1: Port of embarkation: Find the missing values and replace them with "S"
```
titanic_original <-filter(titanic_original, is.na(embarked))
titanic_original$embarked[is.na(titanic_original$embarked)] <- 'S'
```
