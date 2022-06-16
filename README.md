# Regression Diagnostics - Recap

## Introduction

In this section you extended your knowledge of building regression models by transforming the features and identifying ways that your model might be violating the assumptions of linear regression.

## Key Takeaways

* ***Feature transformations*** can be linear or non-linear
  * ***Linear transformations*** include scaling and shifting. They are mainly useful for making your model more interpretable
  * ***Non-linear transformations*** include log transformations, interaction terms, and polynomial regression. These tend to make the resulting model more difficult to interpret, but can help create variables that better fit the assumptions of linear regression
* Linear regression, like any other statistical test, is based on ***assumptions*** about the data and the relationships between the variables
  * These assumptions can be remembered using the LINE acronym: ***linearity***, ***independence***, ***normality***, and ***equal variance (homoscedasticity)***
  * Each assumption can be investigated using ***visualizations*** as well as ***statistical tests***
  * Non-linear transformations and/or choosing different features may help improve how well your model meets the linear regression assumptions
