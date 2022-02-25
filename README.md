# Grocery Sales Forecasting

In the past two years, there has been a shift in how supermarket supply chains function. A report by Acosta, a US-based sales and marketing agency, on grocery store trends for 2021 indicates that 46% of people now use online delivery more than they did before the pandemic. 

A shift from physical grocery stores to digital grocery stores is indicative of a shift from traditional shopping practices to demand-driven buying practices. When demand can be anticipated with accuracy, it can be delivered efficiently with demand forecasting techniques. 

Supermarkets have multiple touchpoints when attracting a customer base. These include psychological, social, cultural, and economic touchpoints. Even a moderate variation in any of these factors leads to a varied demand dynamic. Therefore, it is essential to switch to a supply chain model that acts on the forecasted demand to cut down wastages, enhance viability and eliminate bottlenecks.


# Abstract

Product sales forecasting is a major aspect of purchasing management. Forecasts are crucial in
determining inventory stock levels, and accurately estimating future demand for goods has been an
ongoing challenge, especially in the Supermarkets and Grocery Stores industry. If goods are not readily
available or goods availability is more than demand overall profit can be compromised. As a result, sales
forecasting for goods can be significant to ensure loss is minimized. Additionally, the problem becomes
more complex as retailers add new locations with unique needs, new products, ever transitioning
seasonal tastes, and unpredictable product marketing. In this analysis, a forecasting model is developed
using machine learning algorithms to improve the accurately forecasts product sales. The proposed
model is especially targeted to support the future purchase and more accurate forecasts product sales
and is not intended to change current subjective forecasting methods. A model based on a real grocery
store's data is developed in order to validate the use of the various machine learning algorithms. In the
case study, multiple regression methods are compared. The methods impact on forecast product
availability in store to ensure they have just enough products at right time.

# Introduction
In this project, we are trying to forecasts product sales based on the items, stores, transaction and other
dependent variables like holidays and oil prices.
This is a Kaggle Competition called "Corporación Favorita Grocery Sales Forecasting" where the task is to
predict stocking of products to better ensure grocery stores please customers by having just enough of
the right products at the right time.
For this particular problem, we have analyzed the data as a supervised learning problem. In order to
forecasts the sales we have compared different regression models like Linear Regression, Decision Tree,
ExtraTreeRegressor, Gradient Boosting, Random Forest and XgBoost. Further to optimize the results we
have used multilayer perception (MLP: a class of feed forward artificial neural network) and LightGBM (
gradient boosting framework that uses tree based learning algorithms).
