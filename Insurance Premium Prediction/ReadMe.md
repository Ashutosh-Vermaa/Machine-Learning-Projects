## Problem Statement
The purpose of this project is to use seven variables or attributes such as age, smoker, number of children in family, BMI etc., predict the mdeical expenses of a person. It is helpful for the health insurance companies to estimate the expenses for an individual and accordingly charge the premium.

<p align="center">

  <img src="https://images.pexels.com/photos/40751/running-runner-long-distance-fitness-40751.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"  width="700" height="400" />
   
</p>

<p align="center">
  Image by Pixabay from pexels.com
</p>

## Outline
1. Data Cleansing
2. Exploratory Data Analysis
3. Model Building and Training
    - Linear Regression
    - Artificial Neural Network
 4. Model Evaluation
 
 ## Dataset Description
 The dataset was taken from Kaggel.com. It has 7 columns with 1330 entries.There are 6 numerical datatype columns and one object datatype column.  
 
 ## Data Cleansing
 In the data pre-processing step, I explored the null values in the columns and identified and removed the duplicate entries in the dataset. Furthermore, boxplots were generated to check for the outliers in the data which was followed by treating the outliers. Moreover, I replaced the textual entries in the categorical variables with numerical values.
 
 ## Exploratory Data Analysis
 Following data cleaning step, I explored the dataset- relationship between variables, distribution of the variables, correlation between the variables. 
 
 ## Model Architecture 
 After performing EDA on the dataset, the dataset was split into train and test set after standardizing. I used the sklearn libraries LinearRegression() model fit the data and predict the target value. The model gave a mean absolute error score of close to 4000 and predicted the result with around 78% accuracy. 
 
 After training and evaluating the Linear Regression model, I built a neural network model with 25 and 16 nodes in the two hidden layers. The model gave Mean Absolute Error score of around 1564. This model predicted the results with 86% accuracy. 
 
 

