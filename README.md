📈 Stock Price Prediction Pipeline
This repository contains a complete end-to-end Machine Learning pipeline developed for Task 2 of the Month 1 Data Science Internship at Arch Technologies. The project focuses on fetching live historical market data, analyzing trends, and utilizing regression techniques to forecast future asset values.
🚀 Project Overview
The objective of this project is to build a predictive model that estimates future stock closing prices based on historical financial metrics. By leveraging automated data ingestion tools and robust machine learning libraries, this workflow streamlines everything from raw data extraction to final evaluation metrics.
Key Features
📊 Automated Ingestion: Integrates Python's yfinance API to fetch real-time and historical financial market data.
🧹 Data Pipeline: Comprehensive preprocessing including missing value handling, datetime indexing, and target variable alignment.
📉 Exploratory Data Analysis (EDA): Visualizes stock trends, volume volatility, and moving averages using Matplotlib and Seaborn.
🤖 Machine Learning: Implements a Scikit-Learn LinearRegression engine to build time-series forecasting models.
🛠️ Tech Stack & Dependencies
The project is built entirely in Python inside a Jupyter Notebook (.ipynb) environment. The core libraries used include:
import numpy as np              # Numerical computing
import pandas as pd             # Data manipulation and analysis
import matplotlib.pyplot as plt # Core data visualization
import seaborn as sns           # Advanced statistical plotting
import yfinance as yf           # Yahoo Finance live data extraction
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error
📂 Project Structure
├── .gitignore                          # Standard Git ignore file
├── README.md                           # Project documentation (this file)
└── stock_price_prediction.ipynb       # Main Jupyter Notebook with code and analysis
📈 Methodology
Data Collection: Pulling specific stock tickers (e.g., Apple, Google, or indices) across custom time horizons.
Feature Engineering: Creating rolling windows, shift values, and technical indicators to help the model learn trend behavior.
Model Training: Splitting sequential data cleanly into training and testing arrays to prevent look-ahead bias.
Evaluation: Evaluating prediction intervals using Mean Squared Error (MSE) and R^2 scores to analyze forecasting accuracy.
🎓 Internship Acknowledgement
This project was successfully submitted as part of the official Month 1 Data Science Internship curriculum at Arch Technologies. All evaluation criteria, visualization parameters, and predictive thresholds have been fulfilled according to project requirements.