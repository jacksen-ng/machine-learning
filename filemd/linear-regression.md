## Linear Regression

- What is Linear Regression
    - In statistics, linear regression is a statistic model which estimates the linear relationship between a scalar response and one or more explanatory variables.
    - Or you can said linear regression is a machine learning model that used to predict a continuous value.
    - This section is a note on my learning of the linear regression model in Python using scikit-learn.

- In math
    - First, let's use a simple math formula to understand the linear regression model. We know that a linear function is given by $y=mx+c$
        - $y$ is the dependent value(the value we are trying to predict)
        - $x$ is the independent value
        - $m$ is the slope of the line(indicating how much y changes with x)
        - $c$ is the y-intercept(the value of $y$ when $x$ is 0) 
    - In a simple dataset, if $(x,y) = (2,8), (3,11)$, we can see that the model is represented by the function $y=3x+2$. But in most datasets, there are not just two data points; there are many data points. We need to fit these data points and find the best function to represent the model. This is typically done using methods like **ordinary least squares (OLS)**.

    - What is **Ordinary Least Squares(OLS)** ?
        - **OLS** is a method used in linear regression to estimate the parameters (coefficient) of a linear function that best fits a given set of a data points. This sentence might be a bit difficult to understand. To clarify, I understand it as follows: when we have a lot of data in a dataset, we need to create the best function using the equation $y=mx$ and the OLS method.
        - Ordinary Least Squares can represented by *Ordinary* and *Least Squares*. "**Ordinary**" refers to the standard, basic version of the least squares method, where the objective is simply to minimize the sum of the squared residuals (differences between observed and predicted values) without any additional adjustments or complexities. "**Least Squares**" refers to the mathematical approach of minimizing the sum of the squares of the residuals to find the best-fitting line in a linear regression model.