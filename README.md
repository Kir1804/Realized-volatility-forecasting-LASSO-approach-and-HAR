# Realized-volatility-forecasting-LASSO-approach-and-HAR
Based on the approaches which are presented in "Forecasting Realised Volatility: Does the LASSO approach outperform HAR?" (Yi Ding, Dimos Kambouroudis &amp; David G McMillan, 2021) I predict realized volatility for different indices (UK, USA, Germany and others).  
My project starts with BTC-USD data analysis (from 2018-11-06 to 2022-11-03), because it was much easier to got this data.    
* The fisrst step included some data preperations: log returns and sum of squares of log returns.  
* The second was to calculate logarithmic RV.   
* To implement HAR-models it was necessary to calculate daily, weekly and monthly realized volatility. To complete this task I aggregated returns by days to obtain some essential data.   
* After the data preparation I used OLS-regression to get coefficients for daily, weekly and monthly logarithmic RV.    
* In the end I calculated MSE, MAE and R-squared. Using this metrics it is possible to conclude that the explanatory variables explain of the variance of the dependent variable out-of-sample.
