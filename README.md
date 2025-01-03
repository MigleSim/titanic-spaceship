# Spaceship Titanic Machine Learning Modelling

#### -- Project Status: In Progress

## Project Intro/Objective

**Business Problem:** 

Using the Titanic Spaceship dataset, this project aims to predict which passengers are likely to be transported and which are not. The workflow includes exploratory data analysis (EDA), data cleaning, feature engineering, and machine learning modeling.

The Titanic Spaceship dataset contains information about passengers, such as their names, departure planets, cabin types, destinations, and expenditures on spaceship services. During EDA, it was observed that the dataset is well-populated, with a 100% uniqueness rate for the identifiers. However, there is approximately 2% missing data across each column. The target column, Transported, is fully populated and exhibits a good balance between the two target classes (50.4% and 49.6%).

Preliminary analysis indicated a potential correlation between transportation likelihood and the amount spent on services such as SPA, RoomService, and VRDeck.

For model selection, AutoML was employed to compare various machine learning models. The LightGBM model emerged as the top performer, achieving the highest F1 score. A feature importance analysis revealed that the top factors influencing the prediction were the cabin number, service expenditures, and passenger age.

A blending approach, incorporating the three best models, was also tested but did not result in a significant performance improvement. Consequently, the LightGBM model is recommended for deployment due to its superior performance and simplicity.

### Technologies
* python
* pandas
* jupyter
* seaborn
* matplotlib
* scikit-learn
* imb-learn
* xgboost
* lgbmboost



## Project Description
Project was compeleted using pandas data manipulation and data transformation, data visualization techniques, inferential statistics, machine learning modelling.

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- writeup/reporting
- data visualizations
- Inferential Statistics
- Machine Learning Fundamentals
