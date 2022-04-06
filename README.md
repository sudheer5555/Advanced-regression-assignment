# Advanced-regression-assignment
Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know: Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.

# Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.\

# Data preparation
Converted categorical variables to dummy variables.Imputed missing values with medain and mode. Used MinMax scaler method to convert the continuous variables to same scale(0,1).

# Model building
We build Ridge and lasso regression models and filtered some features with help of lasso regression.

# Conclusion
1)GrLivArea
2)OverallQual
3)Neighborhood_NoRidge
4)Neighborhood_NridgHt
5)GarageCars
these are five most important variables in predicting the price of house.
