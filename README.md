# Linear Regression using Gradient Descent

## Linear Regression

In statistics, linear regression is a linear approach to modelling the relationship between a dependent variable and one or more independent variables. Let X be the independent variable and Y be the dependent variable. We will define a linear relationship between these two variables as follows:

<img src="https://miro.medium.com/max/600/1*p3LTR6GB6g2MpRZzE5JIxw.png" title=""/>


<img src="https://miro.medium.com/max/712/1*ETn5o9GRaF8ZK6wIHvGrJQ.gif" title=""/>

m is the slope of the line and c is the y intercept. Today we will use this equation to train our model with a given dataset and predict the value of Y for any given value of X. Our challenge today is to determine the value of m and c, such that the line corresponding to those values is the best fitting line or gives the minimum error.

##Loss Function
The loss is the error in our predicted value of m and c. Our goal is to minimize this error to obtain the most accurate value of m and c.
We will use the Mean Squared Error function to calculate the loss. There are three steps in this function:
Find the difference between the actual y and predicted y value(y = mx + c), for a given x.
Square this difference.
Find the mean of the squares for every value in X.
