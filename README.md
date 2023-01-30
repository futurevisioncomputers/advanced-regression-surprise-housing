# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
he company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.


## Table of Contents
* [Problem Statement](#problem-statement)
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
House Price Prediction

### Business Understanding

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 


### Business Goal:

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

### Business Risk:

- Predicting the price of a house to buy in low price and sell in high Price.
- Risk cover in business is buy house in high Price and sell in low price.


### Requirement:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.


## General Information
- Steps for creating a Advance linear regression model :
<ol>
    <li>Read and Understand the data</li>
     <li>Data Exploration</li>
      <ol>
        <li>Univariate Analysis</li>
        <li>Bivariate Analysis</li>        
      </ol>
    <li>Feature Engineering</li>
    <li> Data Preprocessing
    <ol>
        <li>Missing Value Treatment</li>
        <li>Dummy Variable Creation</li>
        <li>Outlier Treatment</li>
      </ol>    
    </li>
    <li>Model Building, Tuning & Evaluation
      <ol>
        <li>Split the Data into Dependent and Independent variables</li>
        <li>Train - Test Split</li>
        <li>Scaling numerical columns</li>
        <li>Model 1: Ridge Regression</li>
        <li>Model 2: Lasso</li>
         </ol>
    </li>
    <li>Comparing the two models</li>
    <li>Inferences for 'Surprise Housing'</li>
    <li>Coding for answering the subjective questions</li>
</ol>
<h3>- Data Set : train.csv </h3>


## Conclusions
<div class="alert alert-block alert-danger">
    <span style='font-family:Georgia'>
        <b>Inferences:</b>
        <p>The variables significant in predicting the price of a house are:</p>
        <ol>
            <li>OverallQual_9</li>
            <li>OverallCond_9</li>
            <li>GrLivArea</li>
            <li>Neighborhood_Crawfor</li>
            <li>OverallQual_8</li>
            <li>Neighborhood_StoneBr</li>
        </ol>        
        <b>How well those variables describe the price of a house?</b><br>
        <b>Here will see only top few variables</b>        
        <ol>
            <li><b>GrLivArea:</b> an increase of 1 square foot  of house area above ground, the price will <b>increase by 1.10 to 1.09 times.</b>
            </li>
            <li><b>OverallQual_9:</b> if the overall material and finish of the house is Very Good or Excellent, the price of house will <b>increase by 1.16 to 1.11 times.</b></li>
            <li><b>Neighborhood_Crawfor:</b> if Crawford is a nearby location, then the price of house will <b>increase by 1.09 to 1.12 times.</b>
            </li>
            <li><b>Exterior1st_BrkFace:</b> if the exterior covering on the house is Brick Face, the price of house will <b>increase by 1.09 to 1.06 times.</b></li>
            <li><b>OverallCond_8 :</b> Rates the overall condition of the house, then the price of house will <b>increase by 1.17 to 1.09 times.</b></li>           
        </ol>
    </span>    
</div>


<div class="alert alert-block alert-info">
    <span style='font-family:Georgia'>
        <b>In a similar manner, we can deduct how well each variable describes the price of a house.</b><br>
        <h3>Optimal value of lambda for Ridge Regression = 7</h3>
        <h3>Optimal value of lambda for Lasso = 0.0001</h3>
    </span>    
</div>

## Technologies Used
- pandas - 1.4.4
- numpy - 1.21.5
- matplotlib - 3.2.2
- seaborn - 0.11.2
- plotly - 5.8.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was case study for an online advance course.
- https://seaborn.pydata.org/
- https://plotly.com/
- https://pandas.pydata.org/
- https://learn.upgrad.com/


## Contact
Created by [@futurevisioncomputers] - feel free to contact me!




