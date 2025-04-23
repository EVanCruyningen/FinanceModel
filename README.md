# FinanceModel

  We aim to make an accurate predictor of NASDAQ: COST Dayt stock prices using predictors that can all be found on Dayt-1. We will train on five years of stock data, with daily periods, to get 1255 days of trading. We continue with some calculations for moving averages, RSI, and other indicators to better enhance our model. Finally, we will train an LSTM to calculate the Dayt price using historical data and Dayt-1 data. Our goal is to maximize the return of our model on new data, and only allow it to buy and sell, without shorts or options.

Our LSTM ended up returning about 1/2 of what you would have gotten if you simply bought and held the data. This is because LSTMs are incapable of predicting the stock market, which has been proven to be a stochastic random walk. Despite this result, this project was still fun to implement and pushed my financial and machine learning knowledge.
