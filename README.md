## Project Overview
This repository presents an in-depth analysis of Bitcoin’s historical price data taken from 2010 - 2024, it explores the potential for predicting future prices using various machine learning models. The project involves Exploratory Data Analysis (EDA) to uncover key trends, patterns, and features in Bitcoin's price movements, followed by the development of a price prediction model to forecast future price behavior.

**Key Components:**
1. Exploratory Data Analysis (EDA):

Conduct a thorough exploration of Bitcoin’s historical price data, including analysis of trends, seasonality, volatility, and relationships between different market factors.
Visualizations include time series plots, histograms and correlation matrices to help identify important patterns and insights.
Features analyzed include price, trading volume, opening/closing prices, and volatility or overall change in market movement.

2. Feature Engineering:

Creation of new features that may improve the performance of predictive models, such as Average_Price, Daily_Range, and rolling statistics like Rolling_Mean, Rolling_Std.

3.  Potential building of Price Prediction Model.

# Dataset Overview
The "Bitcoin Price | Daily Price | Weekly Update" dataset is downloaded directly from Kaggle. It provides weekly updates on Bitcoin prices along with related information to aid in cryptocurrency market analysis and trend monitoring. The dataset contains historical Bitcoin prices over several weeks, including key details such as opening price, closing price, highest price, lowest price, and trading volume.

Key Features:
Date: The specific date each price was recorded, corresponding to the day of Bitcoin trading.
Price: Bitcoin’s price at a specific point during the day, represented in USD.
Open: Bitcoin’s opening price at the start of each trading day.
High: The highest price Bitcoin reached during the day’s trading session.
Low: The lowest price Bitcoin reached during the day’s trading session.
Vol. (Volume): The total trading volume (e.g., number of Bitcoins traded) during the day.
Change %: The percentage change in Bitcoin’s price from opening to closing, indicating the relative shift in price during the day.
For more details, you can access the dataset directly from Kaggle:

This is the link to the dataset from kaggle 
https://www.kaggle.com/datasets/dannyrevaldo/bitcoin-price-weekly-update

# Technology Used
* Python
* Google Colab
* pandas, numpy, matplotlib, seaborn, plotly, statsmodel
