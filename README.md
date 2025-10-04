# NYC-data-analysis
Analysing Nyc Taxi Trip data to maximizing the revenue of taxi drivers using python.
## Table of Contant:
- [Project Overview](#project-Overview)
- [Business Problem](#Business-Problem)
- [Dataset](#Dataset)
- [Structure](#Structure)
- [Tools and Techniquise](#Tools-and-Techniquise)
- [Data Cleaning and Preparations](#Data-Cleaning-and-Preparations)
- [Final Data](#Final-Data)
  

  
## Project Overview:
In this project we analyse the NYC Taxi Trip data with the purpose of increasing the revenue of taxi drivers.
The complite analysis is done by using python programing language.To archieve this goal we analyse the valueable
data to make data driven decisions to maximize the revenue of taxi drivers.

## Business Problem:
There is lot of taxi booking companies and wants increase their revenue which is very important for long term
success of a company. This analysis aims to 

- identify the relationship between payment methods and fare amount.

- Also identifying the relation between paymnet methods and trip distance.

## Dataset:
Dataset of 2020_Yellow_Taxi_Trip_Data.csv source is [kaggle](https://www.kaggle.com/)

## Structure:
```
D:.
|   
\---nyc-data-analysis
    |   2020_Yellow_Taxi_Trip_Data.csv
    |   
    +---notebooks			# Jupyter Notebook
    |       nyc taxi project.ipynb
    |       
    \---reports				# Presentation PDF
            Nyc Taxi Analysis Report.pdf
```

## Tools and Techniquise
The project is implemented using Python with the following libraries:

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
import scipy.stats as st
```
## Data Cleaning and Preparations
- Removed unnecessory collumns.
- Removed missing values with (>0.01% missing).
- converted datetime columns in correct formate.
- Detecting outliers with IQR method and removed extream outliers to prevent skewness of data.
- used feature engineering methods to create new column duration by extracting month, year, time from datetime columns.
- Standardized text fields like payment_type and vendor_id for consistency.
- Ensured all text columns are in lowercase.
  ### Final Data
  - after cleaning the dataset contains [3554379] rows and [5] columns
  - Ready for Analysis and visualisation

## Exploratory Data Analysis

- Analyzed the impact of different payment methods on fare amount and trip distance.
- Used bar charts to compare fare amount and trip distance across payment types.
- Checked customer preferences between card and cash payments using a pie chart.
-  Analyzed passenger count (1, 2, 3, 4, 5) to find which category uses taxis the most.

## Visualization

Fare amount and Trip distance distribution by paymnet method



  







 

