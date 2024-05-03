# Larsen & Toubro Limited Stock Price Prediction

## Objective

The project aims to identify short-term and long-term trends, and to provide a forecast the stock prices for the next month.

## Dataset Infromation:

We used the Yfinance library to gather the data easily.The data is collected from 1-Jan-2015 to 30-April-2024.
We can also download the data of many listed stocks from Yahoo! Finance Website using the link (https://finance.yahoo.com/quote/LT.NS/history?period1=1420070400&period2=1714608000)

### About the data

Date: Date of trade

Open: Opening Price

High: Highest price on that day

Low: Lowest price on that day

Close: Close price

Adj Close: Adjusted close price adjusted for splits and dividend and/or capital gain distributions.

Volume: Volume of stock trade on that day

## Model Building & Conclusion

In this project we built and evaluated many machine learning models, including SVR, Random Forest, KNN, LSTM, and GRU.

The LSTM model and demonstrated higher accuracy with Train R2 Score of 0.99 and Test R2 Score of 0.98,
followed by GRU with the Train R2 Score of 0.99 and Test R2 Score of 0.97.

R2 score for the testing data of the Random Forest turns out to be negative. This happened as the model is over-fitted.


![image](https://github.com/Harsha-7989/Larsen-Toubro-Limited-Stock-Price-Prediction/assets/86124041/2f58fecc-20a0-4e3b-8031-b9d1a58215d5)

