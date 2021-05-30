## Lesson 10: Time Series

### Homework: A Yen for the Future

#### Time-Series Forecasting

In this notebook, you will load historical CAD-JPY exchange rate data and apply time series analysis and modelling to determine if there is any predictable behaviour.

Follow the steps outlined in the time series starter notebook to complete the following:

1. Plotting the Settle price to check for long or short-term patterns.
   
    * Do you see any patterns, long-term and/or short?
        
        Although there seemed to be no obvious patterns since 1990, with very weak predictability, the exchange price has been dropping over this time period.

2. Decomposition using a Hodrick-Prescott filter (decompose the settle price into trend and noise).
    
     *  Do you see any patterns, long-term and/or short?
         
         Exchange rate prices and Trend were very close with, mostly, minimal but sporadic noise.

3. Forecasting returns using an ARMA model.
    
    * Based on the p-value, is the model a good fit?
       
       No, the p-value is above the threshold of 0.05.

4. Forecasting the exchange rate price using an ARIMA model.
    
    * What does the model forecast will happen to the Japanese Yen in the near term?
        
        There will be a decline in returns.

5. Forecasting volatility with GARCH.
   
    * What does the model forecast will happen to volatility in the near term?
        
        The model forecasts an increasing trend in volatility.

Use the results of the completed time series analysis and modelling to answer the following questions:

1. Based on your time series analysis, would you buy the yen now?
    
    No, having seen more than three decades of exchange rate prices, there seemed to be a downward trend.
    
2. Is the risk of the yen expected to increase or decrease?
    
    With very weak behaviour predictability of the exchange rate prices over a long time period, as shown on the time series analysis, risk will consistenly be expected to increase over this currency. 
    
3. Based on the model evaluation, would you feel confident in using these models for trading?
    
    No, p-values on all models are more than the threshold of 0.05 which means that the results might be misleading with unreliable coefficient.


#### Linear Regression Forecasting

Use the results of the linear regression analysis and modelling to answer the following question:

* Does this model perform better or worse on out-of-sample data compared to in-sample data?
    
    Out-of-sample data seem to indicate a better fit with a lower RMSE compared to in-sample data.



