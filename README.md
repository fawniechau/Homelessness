# Homelessness
The primary objectives of this project is to:
- identify market factors that have established effects on homelessness
- construct and evaluate empirical models of community-level homelessness

## Sources of the Data
Data is from U.S. Department of Housing and Urban Development (HUD) Market Indicators of Homelessness Report
Link(s): https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf

Also can be found under: 
- 05b_analysis_file_update.csv
- HUD TO3 - 05b Analysis File - Data - Dictionary.csv

## Data Preparation
To prepare the raw data for analysis, the following steps were taken:
- explored the raw data (general shape, columns, data types etc)
- selected relevent subsets of the data
- renamed columns
- removed missing data
- derived new, relevant variables as new columns

The file used to prepare the data can be found as: 
- chau_homelessness_data_prep.ipyn 

The clean data can be found as: 
- clean_homelessness_data-2.csv

## Data Analysis 
To conduct the analysis, the following steps were taken:
- created test and train splits
- scaled predictor data
- created a OLS model
- used kfold cross validation testing on Ridge, Lasso, and XGBoost models
- use root mean square error to evaluate effectiveness of a model

The file used to analyze the data can be found as: 
- chau_homelessness_data_analysis.ipyn 

The slides to display and communicate the results can be found as: 
- homelessness_slides.pdf

## Author 
Tina Chau 

## License 
The contents of this repository are available for use, but proper credit must be given to Tina Chau.
