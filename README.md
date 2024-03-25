# Code Description

`code/01_data_cleaning.R`
- reads `data/covid_sub.csv`
- dichotomizes `classification` variable on whether patient has covid (value 1-3) or not (value 4+)
- makes a new variable for Death that is dichotomized: 0 for no death and 1 for death (date is present)
- adds labels for all variables
- creates `data/data_clean.rds`


`code/02_making_tables.R`


`code/03_making_plots.R`


`code/04_making_models.R`
- reads `data/data_clean.rds`
- creates a model based on patient respiratory health for patients hospitalized
- creates a model based on patient medical history and demographics
- creates `output/both_models.rds` and `output/both_regression_tables.rds`
