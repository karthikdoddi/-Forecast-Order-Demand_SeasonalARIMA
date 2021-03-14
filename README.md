# Forecast-Order-Demand_SeasonalARIMA

The objective of this kernel is to forecast demand for customer orders using an appropriate model.

There are multiple ways of forecasting demand, with linear models being one of the most popular choice (tried/tested) for data that exhibits a linear trend and/or when the residuals have a normal distribution.

The following dataset is highly skewed and lacks a normal distribution thus one needs to look at alternate models for building accurate forecasts. Either by transforming the data using box-cox or log transformation which 'normalizes' the data. Alternatively, a model that does not require a linear trend on continuous features can be used too. Some models include the grand dad ARIMA model or the newer ones including facbook's prophet or even deep learning. I will implement them in subsequent commits. For now, ARIMA is done end to end.

I have gone with a tried and tested ARIMA model to forecast the order demand.


STEPS/Work Flow :

- Import data and libaries: Self Explanatory
- Explore the Dataset: Check Nulls, Skew, Data Types, Univariate and Bivariate Analysis.
- Explore the Dataset as a Time Series: Min/Max Dates, Check Seasonality, Trends etc.
- ARIMA Model - Some Theory, Choose Best Params (Grid Seach), Build/Fit, Validation, Forecast Accuracy.
  - The END.
