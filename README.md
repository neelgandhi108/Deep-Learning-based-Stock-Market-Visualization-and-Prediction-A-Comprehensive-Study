# Deep-Learning-based-Stock-Market-Visualization-and-Prediction-A-Comprehensive-Study


# Stock Market Visualization and Prediction

This repository contains code and data for performing stock market visualization and prediction using technical indicators and deep learning models.

## Dataset

The dataset used in this project provides historical daily price and volume data for all U.S.-based stocks and ETFs traded on the NYSE, NASDAQ, and NYSE MKT. The data is presented in CSV format and includes information such as date, open, high, low, close, volume, and open interest. Prices have been adjusted for dividends and splits. The dataset is comprehensive and offers high-quality financial data for analysis.

## Stock Market Visualization

The "Stock Market Visualization" notebook focuses on analyzing the provided dataset and visualizing various technical indicators. It includes the following steps:

1.  Reading the data from the Stock folder.
2.  Checking the amount of available data.
3.  Selecting 8 random stock data for analysis.
4.  Reading the data into dataframes.
5.  Adding various technical indicators to the dataframe.
6.  Calculating and adding technical indicators such as Relative Strength Index (RSI), Bollinger Bands, Aroon Oscillator, Price Volume Trend, Acceleration Bands, Stochastic Oscillator, Chaikin Money Flow, Parabolic SAR, Price Rate of Change, Volume Weighted Average Price, Momentum, Commodity Channel Index, On Balance Volume, Keltner Channels, Triple Exponential Moving Average, Normalized Average True Range, Average Directional Movement Index (ADX), MACD, Money Flow Index, Ichimoku Cloud, William %R, MINMAX, and Adaptive Moving Average.
7.  Removing unwanted columns.
8.  Visualizing the technical indicators.
9.  Conducting stock market analysis.

## Stock Price Prediction

The "Stock Price Prediction" notebook utilizes LSTM and GRU based models to predict the movement of stocks. It includes the following steps:

1.  Reading the data from the Stock folder.
2.  Choosing 15 random stock data for analysis.
3.  Reading the data into dataframes.
4.  Adding various technical indicators to the dataframe.
5.  Creating separate dataframes (techindi1, techindi2, techindi3, techindi4) for different sets of technical indicators.
6.  Calculating additional technical indicators for each dataframe.
7.  Dropping unwanted columns.
8.  Implementing LSTM and GRU models for stock price prediction.
9.  Training and evaluating the models using different technical indicator sets.
10.  Stacking recurrent layers for improved performance.
11.  Concluding that LSTM and GRU models do not work well for stock market data.
12.  Using technical indicators for training to analyze price and volume changes and their relationships.
13.  Observing that the accuracy does not increase significantly for any method and is not better than the baseline prediction (50%) in some cases.
14.  Noting that no set of technical indicators performs better than others.

## Conclusion

The analysis concludes that LSTM and GRU models are not effective for stock market data prediction. The use of technical indicators helps understand the relationship between prices and volumes but does not significantly improve accuracy. Additionally, no set of technical indicators outperforms others in terms of predictive performance.

Please refer to the respective notebooks for detailed code implementation and further insights.
