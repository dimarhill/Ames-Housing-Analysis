# Project 2 - Ames Housing Data and Kaggle Challenge
---

### Author: Matthew Hill
---

## **Problem Statement**
---

 I am working with a Real Estate company in Ames Iowa and I am tasked with creating a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale.The Ames Housing Dataset is an exceptionally detailed is a dataset with over 70 columns of different features relating to houses in Ames, Iowa.The train dataset has all of the columns and I will refine my model to show the features with the best correlation the best correlations of the features provided to sale price. I am tasked with generating a regression model using the training data and predict the values for your target column in the test dataset and submit my predictions to Kaggle to see how your model does against unknown data.
 
 ## Processing and Modeling
 ---
 
 In processing the first method i used was a train/test split method. In using that used a simple imputer to get rid of null values and also a standard scaler to scale the data. the next model I used was a ridge method which also had to be scaled. The last method used was the LASSO method. All three methods were very useful but in the end. The train/test split method had the best predictive results.
 
  ## Recommendations
 ---
 
 ![](images/linearregressionimage)
 
 
This model shows the predicte values versus the actual price of the houses in Ames, Iowa.This model also proves that the features seletected by me were very much so correlated to the actual price that came from the data set. In the end there were many features that had a positive correlation to the housing sale price in Ames, Iowa. the top five features that correlatated with a higher sale price include the overall quality of the house, the total square footage of the basement, the garage area, the total square footage of the first floor, and also the general living area. The feature that negatively effected the homes worst were having enclosed porches so definetly do not recommend this feature when looking into a house.
 
 
 
 ## Data Links
 ---
 ##### Train Data set
 http://localhost:8849/edit/project_2/datasets/train.csv
 
 ##### Test Data Set 
 http://localhost:8849/edit/project_2/datasets/test.csv
 
 #### Data Dictionary
 https://www.kaggle.com/competitions/dsir-919-project-2/data
 
 
 
