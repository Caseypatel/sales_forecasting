# sales_forecasting

## Project Overview

### Context
The Senior Management team from the retail company is seeking to optimize their sales strategy and improve their forecasting capabilities.

Their proposal is to leverage advanced quantitative methods, including Time Series Models and Causal Models, to analyze the sales data of their products and make accurate predictions about future sales trends. This will enable the company to make informed decisions about inventory management, supply chain optimization, and marketing strategies, ultimately driving business growth and revenue.

### Actions
- **Time Series Analysis:** A comprehensive analysis of the sales data was conducted to identify patterns, seasonality, and anomalies, and to calculate key metrics such as mean, variance, and autocorrelation.
- **Multiple Forecasting Models:** Four models (ARIMA, ES, Prophet, and LSTM) were trained on the training dataset and evaluated using metrics such as MAE, MSE, and MAPE.
- **Model Selection:** The best-performing model (e.g. ARIMA) was selected based on its performance on the training dataset, with a MAE of 19.2%, and was used to generate forecasts for the test dataset.

### Conclusion

#### Time Series Forecasting Model Selection

In our analysis, we evaluated various time-series models alongside a regression model for sales forecasting. The results indicated that the linear regression model outperformed the other time-series models. Consequently, we conclude that a regression model is a suitable choice for forecasting sales in this dataset, rather than relying on traditional time-series models.

#### Rationale for Model Selection

One of the fundamental assumptions underlying regression models is that historical patterns will persist in the future. In our case, the data exhibited strong seasonality and a linear trend, which explains why the linear regression model achieved superior performance compared to the other models. This outcome suggests that the regression model is well-suited to capture the underlying patterns in the data, thereby enabling accurate sales forecasts.
