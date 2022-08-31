# suprise-housing-ridge-lasso-regression
> We use Linear regression model to predict the target variable and then use ridge and lasso regularization techniques to tackle overfitting and to select the final set of predictor variables.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


## Business Understanding
- The objective is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
- We encounter the problem of overfitting if we use the Linear Regression model. To tackle this, we are using ridge and lasso regularization tecnhiques
- Since the objective of the model building is to get all the predictor variables, we would be using Lasso regression.
- Lasso regression has an accuracy of 87.5% on train data and 84.75% on test data when alpha (lambda) = 0.004.
- Based on the model we have 65 predictors that are important and are used to predict the target variable.


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn


## Acknowledgements
- This project was created by Leon Richard D'souza as part of curriculum by IIIT-B ML & AI course


## Contact
Created by [@dsouzaleon] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->