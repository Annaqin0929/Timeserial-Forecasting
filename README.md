## Time Serial Methods 

### RegARIMA (X-13 Methods) & ARMX & Seasonal Prediction

### Regression Time Serial Analysis
Regression time series analysis, a branch of time series modeling, integrates traditional regression techniques with time-serial data. Unlike standard time series models that solely rely on historical observations of past values and errors, regression time series methods incorporate external variables, capturing their impact on the dependent variable. Regression Time serial models are very helpful when a big part of the change from period to period or residuals cannot be well explained by past values and past errors alone. This approach is also beneficial when the relationship between the time serial variables of interest and external factors needs to be explored and leveraged for forecasting. 

### ARMAX Model
In the ARMAX model, exogenous variables are defined as additional time series data that can influence the original time serial 𝑌𝑡. The values of exogenous time serial are also required in modeling and forecast tasks, which means the regression impact of the exogenous time serial datasets could be propagating and slowly changing over time. This project takes New Zealand's total visitor data from 2020 to 2023 as an example to analyze how the exogenous time serial data could help explain the underlying data pattern of total visitors by improving the model performance and reducing errors.

###  RegARIMA model- X13 Workflow in R
In terms of the RegARIMA model, this project takes a longer time series dataset of New Zealand’s total visitors from 1980 to 2023 as an example to explore the RegARIMA function, which is incorporated in the X13-ARIMA-SEATS (X13) workflow in R. X13 workflow is an extensive time series modeling and model selection capabilities for linear regression models with ARIMA errors (RegARIMA models). It is particularly powerful when the time series data exhibits complex seasonality and has known or hypothesized regression relationships with external variables. 

