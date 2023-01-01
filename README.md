#Implementation of Linear regression from Sctrach using pyTorch

Linear regression performs a regression task on a target variable based on independent variables in a given data. It is a machine learning algorithm and is often used to find the relationship between the target and independent variables. The Simple Linear Regression model is to predict the target variable using one independent variable. When one variable/column in a dataset is not sufficient to create a good model and make more accurate predictions, we’ll use a multiple linear regression model instead of a simple linear regression model The line equation for the multiple linear regression model is:

 y = w1x1 + w2x2 + ... + wnxn + b
We'll create a model that predicts crop yields for apples and oranges (target variables) by looking at the average temperature, rainfall, and humidity (input variables or features) in a region. Here's the training data:

table.PNG

In a linear regression model, each target variable is estimated to be a weighted sum of the input variables, offset by some constant, known as a bias :

yield_apple = w11 * temp + w12 * rainfall + w13 * humidity + b1
yield_orange = w21 * temp + w22 * rainfall + w23 * humidity + b2

tabgraph.PNG

