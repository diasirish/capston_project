# capston_project
Predicting stock prices. Last project for Udacity's Machine Learning Nanodegree


Necessary packages
Python 3.x
Pandas
NumPy
Keras
TesnorFlow
MatplotLib
AlphaVantage
Sklearn



1 Background 
Since the stock market was invented people have tried to come up with creative solutions to ”beat it”. With the invention of computers people have tried to use it’s computational power to try and make a leverage on the stock market. Different areas of mathematics have given the rise to the quantitative analysis, where certain smart individuals have created tools and theories to predict the behaviour of the stock markets for their benefit. Today, according to some [1], up to 70% of trading is performed through the ”trade-bots” and the algorithmic trading. Unlike basic algorithms (basic linear regressions and such) today algo- rithmic trading is way more sophisticated and wide range of machine learning algorithms can be used for different sets of data. For this project we will explore how deep neural networks can be applied to try and predict future behaviour of the stock market. 

2 Problem 
The goal of this project is to Predict stock prices using deep neural networks. Specifically, we will create a user-interface to predict a value of a user-specified stock from the list of NASDAQ indices. Machine Learning algorithms that we will use for this is LSTM Neural Networks and Linear Regression. 

3 Dataset and Inputs 
After some googling and considering different data sources (yahoo finance api, google finance api, and bloomberg api), we chose to use data provided by the service named Alpha Vantage [2]. This service provides us with the historical daily data on NASDAQ stocks for the past 20 years. The data contains infor- mation on open, high, close, low, volume values of different indices, and value of the stock. 
Registration on the website will be required to obtain free API. With the API code, we can access ’json’ files and download ’csv’ files as well. These datasets are already optimized to be used with python and pandas. However most probably some basic manipulations will have to be performed in order to input these datasets in the deep neural networks (such as cleaning, splitting data, scaling). 
