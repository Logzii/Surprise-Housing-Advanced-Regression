# Surprise Housing Advanced Regression
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

 Also, determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The Optimum value for lambda in ridge regression is 10
- Optimum value for lambda in lasso regression is 100
- THe features which are having positive coefficients are the ones having positive impact on the sales prices 
- The features which are having negative coefficients are the ones having negative impact on the salse prices

- r2_score in train dataset:
   - r2_score for ridge: 0.89235125467758
   - r2_score for lasso: 0.8999225441409708
   
- r2 score in test dataset:
   - r2_score for ridge: 0.88
   - r2_score for lasso: 0.87
