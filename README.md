# Project Name : House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.The company is looking at prospective properties to buy to enter the market.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.The company is looking at prospective properties to buy to enter the market.
-Background: The project is being submitted as partial fulfilment of Advanced Certificate in Machine Learning and Deeping Learning course conducted jointly by IIIT, Bangalore and Upgrad.
- Business Problem: The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables.
- Dataset Used: train.csv : The dataset contains the details of various attributes of the houses.


## Conclusions
- The optimal lambda value in case of Ridge and Lasso is as below: 
1) Ridge - 4
2) Lasso - 0.0001

- Top Five Predictors of Ridge are
1) OverallCond_9
2) Neighborhood_Crawfor
3) OverallQual_9
4) OverallCond_8
5) Neighborhood_StoneBr

- Top Five Predictors of Lasso are
1) OverallQual_10
2) OverallQual_9
3) OverallCond_9
4) FullBath_3
5) BsmtFullBath_2

## Technologies Used
- Python 3.8.8 Pandas 1.2.4 Numpy 1.20.1 Matplotlib 3.3.4 Seaborn 0.11.1 Sklearn 0.24.1


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by IIIT, Bangalore and Upgrad, Bangalore..
- References if any...
- Python Documentation
- Upgrad Study Material
- https://stackoverflow.com/

## Contact
Created by [@githubusername] - feel free to contact me!
