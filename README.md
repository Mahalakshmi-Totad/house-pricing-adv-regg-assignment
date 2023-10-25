# House Pricing Assignment (Advance Regression)
> build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> What is the background of your project?

Surprise Housing uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. So build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
Specifically, The company is looking at prospective properties to buy to enter the Australian market.

> What is the business probem that your project is trying to solve?

The company wants to know:Which variables are significant in predicting the price of a house and how well those variables describe the price of a house.

> What is the dataset that is being used?

Surprise Housing dataset


## Conclusions
Ridge R2 Score (Test) ---> 0.900895
Lasso  R2 Score (Test) ----> 0.905213

R2 score of Lasso Regression for test data is slightly higher(to a hundredth decimal) than Ridge regression so let's analyze Lasso coefficients for our model

Looking at coefficients we got for Lasso Regression the variables that are significant in predicting the price of a house are as follows:

- LotArea: Lot size in square feet 
- OverallQual: Rates the overall material and finish of the house
- OverallCond: Rates the overall condition of the house
- YearBuilt: Original construction da
- BsmtFinSF1: Type 1 finished square feette
- TotalBsmtSF: Total square feet of basement area
- GrLivArea: Above grade (ground) living area square feet
- GarageCars: Size of garage in car capacity

## Technologies Used
- sklearn
- matplotlib
- seaborn


## Contact
Created by [https://github.com/Mahalakshmi-Totad] - feel free to contact me!
