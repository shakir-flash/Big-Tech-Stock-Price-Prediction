# Big Tech Stock Prediction
This repository contains the Jupyter notebook for the SIE 533 final project by Sarthak Miglani, Shakir Ahmed, and Udit Chaudhary. The project focuses on predicting the stock prices of major technology companies using several machine learning models.

## Dataset Overview
The dataset was derived from Tidytuesday GitHUB Repository: https://github.com/rfordatascience/tidytuesday/tree/master/data/2023/2023-02-07

The dataset consists of daily stock prices and volumes for 14 tech companies from 2010 to 2023, including major names like Apple (AAPL), Amazon (AMZN), Alphabet (GOOGL), and Meta Platforms (META). The dataset features the following columns:

* stock_symbol: Identifier for the stock.
* date: Date of the record.
* open: Opening price of the stock for the day.
* high: Highest price of the stock for the day.
* low: Lowest price of the stock for the day.
* close: Closing price of the stock, adjusted for splits.
* adj_close: Adjusted closing price, accounting for splits and dividend distributions.
* volume: Number of shares traded.

## Project Structure
### Data Importing and Visualization
* Importing necessary libraries and data.
* Visualizing time series of adjusted closing prices to understand trends over the period from 2010 to 2023.

###Exploratory Data Analysis
* Checking for missing values and performing initial analysis to understand the data's distribution and characteristics.

###Predictive Modeling
Implementation of several machine learning models to predict stock prices:
* Linear Regression: Basic regression model to establish a performance baseline.
* Random Forest: A more complex model to capture non-linear relationships.
* Multi-Layer Perceptron (MLP): Neural network model to learn complex patterns for stock price prediction.
* ARIMA: Time series forecasting model specifically for predicting future stock prices.

Each model's implementation is accompanied by visualizations of predicted vs. actual values and the distribution of prediction errors.

### Libraries Used
* NumPy
* pandas
* matplotlib
* scikit-learn
* statsmodels

### How to Use
* Clone this repository.
* Ensure you have Jupyter Notebook installed, or use Google Colab to open the .ipynb file.
* Install the required libraries.
* Run the notebook to see the analysis and predictions.

### Authors
* Sarthak Miglani
* Shakir Ahmed
* Udit Chaudhary
