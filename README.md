# Surprise Housing - Advanced Regression

## Table of Contents
* [Problem Statement](#problem-statement)
* [General Info](#general-info)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
### Business Understanding
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

* Which variables are significant in predicting the price of a house, and

* How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## General Info
Steps for Advanced Regression:

Read and Understand the data<br>
Data Exploration<br>
        1. Univariate Analysis<br>
        2.  Bivariate Analysis<br>
Feature Engineering<br>
Data Preprocessing<br>
        1.  Missing Value Treatment<br>
        2.  Dummy Variable Creation<br>
        3.  Outlier Treatment<br>
Model Building, Tuning & Evaluation<br>
        1. Split the Data into Dependent and Independent variables<br>
        2. Train - Test Split<br>
        3. Scaling numerical columns<br>
        4. Model 1: Ridge Regression<br>
        5. Model 2: Lasso Regression<br>
        6. Comparing the two models<br>
Conclusion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Conclusions

The variables significant in predicting the price of a house are: 
    GrLivArea, OverallQual_9, OverallCond_9, OverallQual_8, Neighborhood_Crawfor, Functional_Typ, Exterior1st_BrkFace, SaleCondition_Alloca, CentralAir_Y, TotalBsmtSF, Neighborhood_Somerst, TotalBsmtSF and Condition1_Norm.

How well those variables describe the price of a house?
Here will see only top few variables

1. GrLivArea:an increase of 1 square foot of house area above ground, the price will increase by 1.09 to 1.11 times
2. OverallQual_9 & OverallQual_8: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.08 to 1.13 times
3. Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 1.07 to 1.09 times
4. Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.07 to 1.08 times
5. Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.07 to 1.08 times.
6. In a similar manner, we can deduct how well each variable describes the price of a house.

* Optimal value of lambda for Ridge Regression = 10
* Optimal value of lambda for Lasso Regression = 0.001

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
    pandas - 1.3.4
    numpy - 1.20.3
    matplotlib - 3.4.3
    seaborn - 0.11.2
    Scikit-learn - 1.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was group case study for an online advance course.
- https://www.geeksforgeeks.org/
- https://seaborn.pydata.org/
- https://pandas.pydata.org/
- https://learn.upgrad.com/


## Contact
Created by [@vkarkera]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
