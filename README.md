# Capstone Project - Deposits Prediction for a Financial Institution 


## EXPLANATION
A combined model incorporates time series analysis to predict deposit growth, utilizing linear regression to forecast upcoming market interest rates. This fusion of techniques harnesses historical deposit trends to anticipate future balances, employs regression to predict potential market rate shifts, and combines these findings to estimate next-day expenses based on projected deposits. This strategy enhances financial decision-making by harmonizing historical patterns, market dynamics, and predicted costs, resulting in more accurate financial forecasts.

## DATA
The data utilized in this study originates from two distinct sources. Firstly, historical deposit balances are generated through a custom-developed code, enabling the simulation of deposit trends over time. This code produces a synthetic dataset capturing the evolution of deposit amounts daily.
Secondly, historical daily EUR market curves are sourced directly from the European Central Bank (ECB) website. These curves represent the fluctuation of the EUR market rates on a daily basis.

## MODEL 
Linear Regression for Market Rate Prediction:
Linear regression is chosen for market rate prediction due to its ability to model relationships between variables. It's effective when the relationship between predictors and rates is linear, providing insights into how factors influence rates.

Time Series for Deposit Projection:
Time series methods are employed for deposit projection as they excel in capturing temporal patterns. Deposits often exhibit trends and seasonality, which time series techniques, such as ARIMA, can accurately model, enabling reliable future projections. 

## HYPERPARAMETER OPTIMSATION
Grid search is employed to optimize these models due to its ability to systematically explore a range of hyperparameter combinations, helping to identify the best configuration that maximizes model performance.

## RESULTS
Developing these models offers a holistic learning experience by fostering a conceptual understanding of linear regression and time series analysis, honing problem-solving skills, enhancing coding proficiency, enabling informed model selection, and providing practical knowledge in hyperparameter tuning and real-world application.
