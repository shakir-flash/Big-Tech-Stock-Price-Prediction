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

## Libraries Used
* NumPy
* pandas
* matplotlib
* scikit-learn
* statsmodels

## How to Use
* Clone this repository.
* Ensure you have Jupyter Notebook installed, or use Google Colab to open the .ipynb file.
* Install the required libraries.
* Run the notebook to see the analysis and predictions.

## Project Structure
### Data Importing and Visualization
* Importing necessary libraries and data.
* Visualizing time series of adjusted closing prices to understand trends over the period from 2010 to 2023.

### Exploratory Data Analysis
* Checking for missing values and performing initial analysis to understand the data's distribution and characteristics.

### Predictive Modeling
Implementation of several machine learning models to predict stock prices:
* Linear Regression: Basic regression model to establish a performance baseline.
* Random Forest: A more complex model to capture non-linear relationships.
* Multi-Layer Perceptron (MLP): Neural network model to learn complex patterns for stock price prediction.
* ARIMA: Time series forecasting model specifically for predicting future stock prices.

Each model's implementation is accompanied by visualizations of predicted vs. actual values and the distribution of prediction errors.

## Outputs generated:
### Linear Regression:
![image](https://github.com/shakir-flash/Big-Tech-Stock-Price-Prediction/assets/59859522/6cf0e1f7-9e91-49c1-ace8-98e4f5aad75f)

### Lasso Regression:
![image](https://github.com/shakir-flash/Big-Tech-Stock-Price-Prediction/assets/59859522/58056c72-38e8-48aa-84aa-0692264fc70b)

### Random Forest Regression:
![image](https://github.com/shakir-flash/Big-Tech-Stock-Price-Prediction/assets/59859522/dfb0e3b2-f5f3-49c4-ae36-95539c538a22)

### Multi-Layer Perceptron (MLP) Neural Network:
![image](https://github.com/shakir-flash/Big-Tech-Stock-Price-Prediction/assets/59859522/0476e44e-1830-4dbd-a8e5-657ce13f1bd4)

### ARIMA Time-Series Prediction (Sample):
![image](https://github.com/shakir-flash/Big-Tech-Stock-Price-Prediction/assets/59859522/b2bffe4e-7e19-4988-b13a-93b26de79176)


## Conclusion

This project demonstrates the application of data analysis and machine learning techniques to analyze and predict stock prices. By leveraging historical data and advanced modeling approaches, investors can make informed decisions and mitigate risks in the financial markets.
