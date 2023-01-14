# Boston Housing Dataset

## Problem Statement:
*The Boston housing dataset contains 506 samples and 14 dimensions or
attributes. We developed and tested distinct types of regression models such as linear,
polynomial, Decision tree, Ridge and Lasso on this dataset. To compare the findings, we
utilized cross-validation provided by Scikit Learn*
<br>
<br>
<br>
<br>
## Techniques Used:
Linear Regression: Linear Regression is a machine learning algorithm based on
supervised learning. Linear regression performs the task of predicting a dependent
variable value (y) based on a given independent variable (x). So, this regression
technique finds out a linear relationship between x (input) and y(output). Hence, the
name is Linear Regression. Here the linear regression model was applied over 506 data
samples consisting of 13 feature variables.
<br>
<br>
Decision Tree Regression: This model is used to predict future data as a
continuous output. It operates by breaking down the test data into smaller subsets
while at the same time the decision tree is incrementally developed. They are mostly
used for non-linear datasets. Their performance does not depend on the nature of the
data as it does not use any linear classifier or regressor.
<br>
<br>
Polynomial Regression: This model aims to establish a non-linear relationship
between the independent and dependent variables. To fit our datasets more
appropriately, we have used a second order polynomial regression which has a
quadratic form.
<br>
<br>
Ridge Regression: To handle the problem of multi- collinearity in some data
sets we use the approach of Ridge regression which could produce a lower test means
squared error
<br>
<br>
LASSO (Least absolute shrinkage and selection operator) Regression: This
model is used to avoid over fitting, the basic idea behind Lasso regression is that it
allows us to regularize or shrink the data values towards the mean. Lasso regression is
also called L1 regularization, that it adds a penalty which is equal to absolute value of
the magnitude of coefficient.
<br>
<br>
<br>
<br>
## Scatterplot and Histogram
image.png
<br>
<br>
<br>
<br>
## Comparison:
Linear regression model being a simple model fits straight line to the data and
has the highest mean squared error. This error can be seen reducing, by fitting a
quadratic curve to the data samples using a Polynomial Regression of 2nd order. As
observed, Lasso regression outperforms every other model in terms of RMSE. Whereas
the best cross validation is obtained by implementing the ridge regression model.


