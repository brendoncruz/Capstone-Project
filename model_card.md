# Model Card



## Model Description 1

**Input:** 

 - Date: Market Date
 - Balance: Balance in the Client's Account
 - Client ID: This identifier uniquely distinguishes different clients.
 - Category: Balance type category (i.e.,Opening balance, Ending Balance, etc)
 - Currency: Currency of the balance

**Output:**

 - Future Balance: Future deposits balance for the next day

**Model Architecture:** Time Series

## Model Description 2

**Input:** 

 - DATE: Market Date
 - EUR RATE: Historical Interest Rate for the Day
 
**Output:**

 - Next Day Rate : Next day interest rate for EUR 

**Model Architecture:** Linear Regression


## Performance

Model 1: RMSE: 5123.926645182073 
Performance: Good, considering balance prediction is around EUR 1.2m
Root Mean Squared Error (RMSE) is a statistical metric that quantifies the average difference between predicted values and actual values in the same unit as the target variable. It gauges the accuracy of a model's predictions, with lower RMSE values indicating better performance.

Model 2: R-squared: 0.9948135479978905
Performance: Good
R-squared (R²) measures how well a regression model fits the data. It quantifies the percentage of variance in the dependent variable explained by the independent variables. 


## Limitations

This model does not consider client behaviours, such as reaction to news, economy, politics, or global events. It also assumes that there is a linear relationship between the variables, which may not be true in all situations.
