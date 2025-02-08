# Data Science Coding Challenge

## Overview
My task was to forecast ticket sales for the next season 2022/2023, covering the period from December 10, 2022, to April 15, 2023 (10.12.2022 - 15.04.2023).

# Key deliverables
predictions.csv
eda_and_model.ipynb

## Task questions

# What do you see (patterns/potential issues)? The raw data consisted of two columns: Date and Number of Tickets Sold.

Corona: The impact of the pandemic on sales
Abnormal visitor flows: Disruptions in normal attendance patterns
The model should consider different scenarios:
For a "normal" situation without restrictions, the model should be built using data from December 2016 to February 2020.
Two scenarios need to be considered based on the pandemic situation: "normal" and with restrictions.
For this task, a "normal" development is assumed.
# Which forecasting model did you choose and why?
As a baseline model, linear regression was chosen. The metric used is mean squared error.

# Are there steps you were unable to finish? 
Yes, except for step 6 under the bonus section.

# Suggest 3 additional steps/features to add:

Experiment with other models, such as boosting algorithms.
More feature engineering, particularly with weather data and macroeconomic indicators.
A deeper exploratory data analysis (EDA).

# How did you use AI to help you in the process? 
AI assisted by creating specific functions and documentation.

## How to set up and run

Clone the repository and navigate to the project folder.

Set up virtual env and install dependencies


## Install dependencies
Python 3.12.7
```bash
pip install -r requirements.txt
```


## Author
- Eugen Gabriel