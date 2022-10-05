# Ordinary Least Square Multiple Linear Regression on mtcars
Learning ML algos (linear regression) with mtcars dataset

## INTRODUCTION

In this project, we will create a statistic model. The statistic model should be able to answer how the given feature explain the fuel consumption(mpg) of a car.<br>

## TL-DR; Summary
- From the multiple linear regression analysis of mtcars data, we found our model, that is:
<p align="center">
  $mpg = 9.62 - 3.92(wt) + 1.23(qsec) + 2.94(am)$
</p>

- The diagnostic test of the final model satisfy all the condition of application.
- In conclusion we can interpret the model as follow:<br>
The Miles/(US) gallon ( mpg ) data is negatively dependent on the Weight (1000 lbs) of the car ( wt ), positively correlated with 1/4 mile time ( qsec ) and Transmission (0 = automatic, 1 = manual) ( am ).

## Sources
- https://statsandr.com/blog/multiple-linear-regression-made-simple/
- https://www.kaggle.com/code/elsapuspa/dataset-mtcars-multiple-linear-regression-python
- https://www.kaggle.com/code/hamelg/python-for-data-27-linear-regression/notebook
- https://medium.com/@abhilash.sirigari/a-complete-model-diagnostics-of-multivariate-linear-regression-90aace20ecaf
- https://medium.com/swlh/interpreting-linear-regression-through-statsmodels-summary-4796d359035a
- https://statisticsbyjim.com/regression/multicollinearity-in-regression-analysis/
