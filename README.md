# DS-Starbucks-Capstone

## Table of Contents

  1 - Project Overview\
  2 - Methodology\
  3 - Results\
  4 - Conclusion\
  5 - Medium Article\
  6 - Acknowledgements

## 1 - Project Overview and Motivation

The project aims to analyze customer behavior of the Starbucks rewards program and develop a machine learning model to predict when a customer would complete different promotional offers.

The motivation behind this projects consists on the desire to analyze customer behaviour and get insights. The datasets has customer demographics, offer characteristics, and user interactions with offers data

## 2 - Methodology

* Exploratory Data Analysis (EDA): Analyzed patterns to gain insights.
* Data Cleaning and Preprocessing: To handle missing values, encode categorical variables, and perform feature engineering.
* Model Development: Developed machine learning model, considering feature correlation with target and predicting accuracy.
* Evaluation: Utilized metrics of accuracy and F1 score to assess the model's performance.

## 3 - Results

* Analysis of transactional data, user demographics and offer characteristics.
* Developed machine learning using 3 different models to predict completed offers. Ada Boost algorithm showed to be the most effective.
* Utilized GridSearchCV and ensemble algorithms for optimizing model hyper parameters.

## 4 - Conclusion

As there was just a small improvement on the models with the hyper parameters, Ada Boost proves to be the best solution with an accuracy of 74.18% and F1-score of around 74%. 

The biggest challenges were related to the extensive EDA and ETL processes, as we were dealing with 3 diffent datasets and some transformation (i.e.: Successful Offer colum) had to be done.

All the models used on this project had a performance above 70% that would be acceptable. In order to improve it further, other features could be used in the models or another machine learning approach (i.e.: NLP) could be used.

## 5 - Medium Article

The post explaining the development of the project can be found on the following [Medium post](https://medium.com/@karlheinz.cirne/a-starbucks-rewards-program-breakdown-customer-demographic-analysis-and-offers-use-35607ba5c4dd)

## 6 - Acknowledgements
Udacity for providing an excellent Data Scientist training program and Starbucks to provide the datasets that were analyzed

