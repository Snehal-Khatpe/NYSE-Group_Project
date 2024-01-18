# NYSE-Group_Project
This repository showcases my academic group project using R and Machine Learning.
It contains code and documentation for the NYSE stock price prediction project.


This repository serves as a comprehensive showcase of our academic group project for subject Business Analytics with R. It encapsulates the culmination of our collaborative efforts and proficiency in leveraging R and Machine Learning.

**Abstract:**
This repository presents an in-depth analysis of New York Stock Exchange (NYSE) data spanning from 2010 to 2016, aiming to predict stock closing prices using machine learning models. The dataset includes daily stock prices, split-adjusted prices, company descriptions, and financial metrics from SEC 10K filings.

**The project's objectives are two-fold:**
* 		Identify optimal predictors for predicting stock closing prices.
* 		Compare machine learning models to determine the most effective one for predicting closing prices.
  
**Data Summary and Preparation:**
* Four datasets were utilized: Prices, Split Prices, Securities, and Fundamentals.
* Data cleaning involved removing missing and NA values.
* Feature selection was performed using forward and backward stepwise regressions, highlighting opening price, highest and lowest prices, and stock volume as key predictors.
  
Techniques Used/Models Tested:
Five machine learning models were tested:
* 		Ridge Regression
* 		Lasso Regression
* 		Regression Tree
* 		Neural Network
* 		Linear Regression
  
**Results Summary:**
Linear Regression emerged as the most effective model with the lowest Mean Squared Error (MSE) and a high R Squared value (0.99989), closely aligning with actual values. Other models, such as Neural Network and Ridge Regression, exhibited higher MSE and less favorable R Squared values.

**Conclusion:**
This analysis concludes that, for predicting NYSE stock closing prices, Linear Regression is the optimal model. 

**Repository Readme:**
The detailed comparison of models and results can be explored in the repository.

