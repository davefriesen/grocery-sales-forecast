# Grocery Store Sales Forecast
This is the final project for the University of San Diego’s ADS 506 Applied Time Series Analysis course. The technical workbook can be found at the [main GitHub repository](https://github.com/davefriesen/grocery-sales-forecast).

#### -- Project Status: [In Progress]

## Project Introduction and Objective
The purpose of this project aims to describe grocery store sales behavior and forecast these sales across a range of product families using data-driven and model-based approaches. The project’s overarching business goal is to establish, in practical terms, the feasibility of using – and potentially automating – one or more of these approaches in a real-world scenario. Note that while the expected outcome is a generalized approach, the study uses representative secondary data from a public data source.


### Methods Used
* Data Preprocessing
* Data Visualization
* Exploratory Data Analysis
* Modeling

### Technologies and Resources
* RStudio

## Project Description
* The [store sales](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) dataset is provided by Kaggle.
*	The following model-based and data-driven models are used:
    * Naive Forecast
    * Holt-Winter's Exponential Smoothing
    * Exponential Smoothing (ANN: Additive error, no trend, no seasonality)
    * Exponential Smoothing (AAN: Additive error, additive trend, no seasonality
    * Exponential Smoothing (MMN: Multiplicative error, multiplicative trend, no seasonality)
    * Exponential Smoothing (MMdN: Multiplicative error, multiplicative damped trend, no seasonality)
    * Simple Regression
    * First-Order Autoregression (AR(1))
    * ARIMA
    * Neural Network Autoregression
    
## Getting Started
1. Clone this repository (For help, refer to this [tutorial](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository))
2. Raw data is kept in the GitHub repository and [Kaggle](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data).
    * [Train data](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data?select=train.csv)
    * [Test data](https://github.com/davefriesen/grocery-sales-forecast/blob/main/data/test.csv)
3. Data preprocessing, exploratory data analysis, and models are in the [GitHub respository](https://github.com/davefriesen/grocery-sales-forecast/blob/main/src/ads506-team5-final-project.Rmd).

## Featured Notebook
* [Notebook](https://github.com/davefriesen/grocery-sales-forecast/blob/main/src/ads506-team5-final-project.Rmd)

### Authors
* Dave Friesen
* Christine Vu
