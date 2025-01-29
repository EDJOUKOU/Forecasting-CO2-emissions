# Forecasting-CO2-emissions

## Project Overview
This project aims to forecast carbon emissions using statistical methods, including SARIMA, Holt-Winters, and the Baseline Naïve Approach.
## Data source
The dataset used for this project was collected in January 2025 and sourced from Kaggle. It is available for download at the following link: <a href='https://www.kaggle.com/datasets/ucsandiego/carbon-dioxide'>pizza sales</a>
## Tools
- Jupyter Notebook IDE for data analysis

## Data cleaning and preparation
In the initial phase, the following tasks were performed:
1. Data loading and inspection
2. Handling data types
3. Addressing missing values
4. Renaming the target variable

## Exploratory Data Analysis
1. Basic information and statistics about the dataset
2. Visualization of the target variable (CO2 emissions)
3. Splitting the data into training and testing sets

## Data Analysis (Modelling)
1. SARIMA model
2. Triple exponential smoothing model
3. Comparison of forecasts with actual values, using the test set as a reference

## Results
# Forecasting CO2 Emissions

## Project Overview
This project aims to forecast carbon emissions using statistical methods, including SARIMA, Holt-Winters, and the Baseline Naïve Approach.

## Data Source
The dataset used for this project was collected in January 2025 and sourced from Kaggle. It is available for download at the following link: [Carbon Dioxide Emissions Dataset](https://www.kaggle.com/datasets/ucsandiego/carbon-dioxide).

## Tools
- Jupyter Notebook IDE for data analysis

## Data Cleaning and Preparation
In the initial phase, the following tasks were performed:
1. Data loading and inspection
2. Handling data types
3. Addressing missing values
4. Renaming the target variable

## Exploratory Data Analysis
1. Basic information and statistics about the dataset
2. Visualization of the target variable (CO2 emissions)
3. Splitting the data into training and testing sets

## Data Analysis (Modeling)
1. SARIMA Model
2. Triple Exponential Smoothing Model
3. Comparison of forecasts with actual values, using the last season of the training set as a reference

## Results
Both SARIMA and Triple Exponential Smoothing models demonstrated similar performance, outperforming the Naïve Baseline model, which relied on the last season of the data.
