# Stock-Price-Prediction using RNN and LSTM

## Introduction

As of April 2018, the Stock Exchange of Hong Kong (SEHK) is Asia's 3rd-largest stock exchange ranked by market capitalisation, 
and also the 7th largest in the world. 
With over 2,100 companies listed on the SEHK, there is a wealth of company performance and financial data that can
be used to explore the concept of deep learning and prediction models using various Python libraries.


## Project Overview

This project aims to explore 2 different approaches in which deep learning models and statistical techniques can be
implemented to predict stock prices trends. 

Specifically, the aforemetioned approaches to predict stock price trend and price, respectfully, is as follows:

1. Use an RNN model or Long-short term memory (LSTM) network that would predict the price trend of a stock (Up, down or neutral); and

2. Predict the future price of a company's stock using a seasonal ARIMA model.

Once the above is completed, we built a website that mimicked an individual's stock portfolio with the purpose of linking (1) and (2) together. The link to the website is: [*]


## Methodology

### Predicting stock price trend using an LSTM network

[*]

### Predict the future price of a company's stock using an ARIMA model.

1. Import relevant libaries
2. Extract historical closing price data of each SEHK listed stock from 1 January 2014 to [*] using fix_yahoo_finance
3. Preprocess data    
    a. Set data into a pandas dataframe  
    b. Group price data by average monthly closing price  
    c. Ensure data has no missing values  
4. Explore timeseries data and its individual compositions as a visualisation 
5. Implement a gridsearch to identify optimum paramaters (p,d,q)(P,D,Q) that produces best fit model for timeseries data  
6. Build model, enforce stationarity on stock data     
7. Validate and visualize model performance   
8. Use seasonal ARIMA model to forecast future values 

## Results and Achievements

* Successfully built an LSTM network algorithm that could predict a company's stock price trend with approximately 80% accuracy.
* Succesfully built an ARIMA model that could predict the future values of a stock's price for the upcoming 10 periods (months)
* Created a website that extracts relevant data from APIs and presents it to the websites registered user as a website function.

Website link:

## Software and Libraries

Python 3.6  
NumPy   
Pandas  
Keras       
Tensorflow  
Jupyter Notebook    
Statsmodel  
Plotly  
    
