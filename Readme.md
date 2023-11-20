# Power Outage Insight: Feature Engineering in Time Series Analysis


## Project Overview

This project aims to analyze power outage data in conjunction with weather conditions to uncover underlying patterns and relationships. The focus is on power outages in Lee County, Florida, from 2018 to 2022, and how various weather conditions might influence these outages.

## Dataset:

The dataset used is the Eagle-I power dataset from the SMC dataset challenge 2023. 
The dataset consists of 4 years of power outage data between 2018 and 2022 for each county of united states with an interval of 15 mins,collected it through a process of ETL from public outage maps of utility. The columns present in this dataset are ‘fips_code’, ‘county’, ‘state’, and ‘sum’ 
indicating the power outage and the total number of rows are 1689460. 

The other dataset that we will use to integrate with the former dataset is the weather dataset from Kaggle dataset of US Weather Events (2016 - 2022). 
This dataset consists of 7 years of weather events data between January 2016 and December 2022 for each county of 49 states in the US
which is collected from 2071 airport-based weather stations nationwide. 

Datasets link:

Eagle-I power dataset: https://smc-datachallenge.ornl.gov/eagle/

Weather dataset: https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events/data

## Methodology
1. *Data Preprocessing*: Combining power outage and weather datasets and handling missing values.
2. *Exploratory Data Analysis (EDA)*: Visualizing time series trends and analysing the correlation between power outages and weather conditions.
3. *Feature Engineering*:
   - Time-based features: Year, month, day.
   - Rolling statistics: Calculating rolling means and standard deviations.
   - Lag features: Creating lags of the time series.
   - Cyclical features: Encoding cyclical nature of day and month.
4. *Seasonal Decomposition & Fourier Transform*: Analyzing seasonal components and frequency domains of the time series.
5. *Model Implementation and Evaluation*:
   - Time Series Models: ARIMA, SARIMA.
   - Regression Models: Linear Regression, XGBoost.
   - Evaluation Metrics: RMSE, MAE, R².

## Results and Conclusion
The project includes the detailed analysis, visualizations, highlighting key patterns in power outage data and its relation to weather conditions. 

Model evaluations indicate the performance of various predictive models in understanding and predicting the power outages.
