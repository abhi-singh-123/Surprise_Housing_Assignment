# Surprise housing prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Surprise housing company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

### Goal
- To build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

#### Dataset - data_description.txt

## Steps

The solution is divided into the following sections:

- Data understanding and exploration
- Data cleaning
- Data preparation
- Model building and evaluation


## Conclusions

##### Optimal alphas

   - Ridge - 2.0
   - Lasso - 0.0001

##### R2 values

 - Ridge 
     - Train = 93.05 , Test = 89.67
 - Lasso
     - Train = 92.72 , Test = 90.35
     
#####  Mean Squared error 

 - Ridge - 0.0029
 - Lasso - 0.0028

##### Numbers show Lasso has done a bit better compared to Ridge

##### TOP 5 Predicted variables are based on Lasso Regression:--

The house price increase with increase in
- OverallQual 
- GrLivArea 
- YearBuild 
- Total_sqr_footage 
- Neighborhood_StoneBr 



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- sklearn
- Pandas
- Matplotlib
- Numpy

