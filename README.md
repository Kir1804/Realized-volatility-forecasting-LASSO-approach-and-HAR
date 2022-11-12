# Realized-volatility-forecasting-LASSO-approach-and-HAR-
Based on the approaches which are presented in "Forecasting Realised Volatility: Does the LASSO approach outperform HAR?" (Yi Ding, Dimos Kambouroudis &amp; David G McMillan, 2021) I predict realized volatility for different indices (UK, USA, Germany and others).  
First of all I used BTC-USD data (from 2018-11-06 to 2022-11-03), because it was much easier to got this data.  
The main difficulty was to correctly calculate RV.   
The fisrst step included some data preperations: log returns and sum of squares of log returns.  
The second was to calculate logarithmic RV.   
To implement HAR-models it is necessary to calculate daily, weekly and monthly realized volatility. To do this task I use Yahoo! Finance (https://finance.yahoo.com/quote/BTC-USD/history?period1=1541462400&period2=1667433600&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true) to obtain some essential data.   
The main difficult is to calculate daily, monthly and weekly returns.  
