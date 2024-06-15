# GOOGL Stock Price Analysis

## Project Overview

This project focuses on analyzing and predicting the daily log returns of Google stock using various advanced statistical and machine learning models. The analysis includes comprehensive feature engineering and the application of multiple prediction models to gain insights into the stock's behavior.

## Data Sources

The data for this project was collected from three main sources:
1. **Fama-French Website**: Provides data on market, size, and value factors used in asset pricing models.
2. **FRED API**: Federal Reserve Economic Data (FRED) offers a wealth of economic data series.
3. **Ads Index Most Current Vintage**: This data source includes relevant advertising index information.

## Feature Engineering

Feature engineering is a critical step in this project. The following transformations and techniques were applied to the raw data:

- **Log Transformations**: Applied to normalize the data and stabilize the variance.
- **Interaction Terms**: Identified and included to capture the combined effects of different variables.

## Predictive Models

Several models were utilized to predict the log daily return for Google stock:

### Statistical Models
1. **CAPM (Capital Asset Pricing Model)**: Used to describe the relationship between systematic risk and expected return for assets.
2. **Fama-French 3 Factor Model**: Extends CAPM by adding size and value factors to better explain returns.
3. **Augmented Autoregression**: Enhances autoregressive models by including additional predictors to capture more complex patterns.

### Machine Learning Models for Feature Importance
1. **XGBoost**
2. **ElasticNet**
3. **Lasso (Least Absolute Shrinkage and Selection Operator)**
4. **Ridge Regression**
