# Predict-if-a-client-will-make-a-fixed-deposit
-by Arushi Mahwar, student from Birla Institute Of Technology, Mesra, Jaipur campus

This is my project on machine learning. Languages included : Python          

Goal : To predict whether the client will make a fixed deposit in a bank or not.

## Problem Statement: 
Your client is a retail banking institution. Term deposits are a major source of income for a bank. A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing and digital marketing. Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.
You are provided with the client data such as : age of the client, their job type, their marital status, etc. Along with the client data, you are also provided with the information of the call such as the duration of the call, day and month of the call, etc. Given this information, your task is to predict if the client will subscribe to term deposit.

## The project has the following parts :
1. Data Visualization : In this I pre processed the raw data into a meaningful numeric data and plot some graph for better understanding.
2. Univariate Analysis : In this part of my project I have analyze the independent variables individually. 
3. Bivariate Analysis : In this we have analyze the relation between various independent variables and the target variable.
4. Correlation : In this part we saw the correlation between each of the variables and the variable which have high negative or positive values are correlated.
5. Model Building : Here I split the train data into training and validation set so that it become easy to validate the results of our model on the validation set. We will keep 20% data as validation set and rest as the training set.
6. Machine Learning algorithm : To check the performance of my dataset I have used two machine learning techniques i.e Logistic regression (which has a linear boundary) and Decision tree (if our data have non-linearity). 

### Here we are provided with the following files : 

train.csv : Use this dataset to train the model. This file contains all the client and call details as well as the target variable “subscribed”. You have to train your model using this file.

test.csv : Use the trained model to predict whether a new set of clients will subscribe the term deposit.

## Dataset Attributes
Here is the description of all the variables :

Variable: Definition
ID: Unique client ID
age: Age of the client
job: Type of job
marital: Marital status of the client
education: Education level
default: Credit in default.
housing: Housing loan
loan: Personal loan
contact: Type of communication
month: Contact month
day_of_week: Day of week of contact
duration: Contact duration
campaign: number of contacts performed during this campaign to the client
pdays: number of days that passed by after the client was last contacted
previous: number of contacts performed before this campaign
poutcome: outcome of the previous marketing campaign

### Output variable (desired target):
Subscribed (target): has the client subscribed a term deposit?


## Tools and Algorithms Used for Analysis
Python
Numpy
Pandas
Seaborn
Logistic Regression
Decision Tree Classifier

## References 
Kaggle Datasets
