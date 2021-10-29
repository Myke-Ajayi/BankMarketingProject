# OX Bank Marketing Campaign 

## Overview

In this project we focused on making machine learning models to help a predict a future bank marketing campaign. We are looking for a certain set of features that the bank we are working for ,OX Bank, can translate into business ideas for their marketing campaign. OX Bank wants to boost the number of clients doing business with them. They want to do this by having clients subscribe term deposits with OX. We are not delivering a model here but rather an analysis based on the model used. 

## Busines Problem and Data Understanding 

The marketing team of OX bank is working with us, the data science divsion, to achieve the goal of increasing the number of term deposits through the use of a marketing campaign. Marketing campaigns can be costly and time consuming so the marketing team wants to make sure they are putting resources into the right places when running the campaign. The dataset used contains client information from the bank. This includes data such as client job, client marital status , duration of contact with client, last time client was contacted. The target variable of our predictions will be whether or not they suscribe a term deposit with the bank as this is the main overall goal of OX's marketing team. 


## Modeling 

For modeling we did three different types of models. A Decision Tree Classfier, Logistic Regression and Random Forest Model. We first ran a model less evaluation of the target variable. From there we were able to make our train test splits and begin to model. We focused on the precision metric becasue a good precision metric score means there will be less false postives which would mean we predicted a client to do a term deposit when in reality they did not. We also edited the main data set to drop a few of the columns that did not appear to be useful for our models. While modeling we used piplines to make running the models more streamlined. There were also quite a few columns that had to be one hot encoded as they were categorical. 


## Evaluation 

The best of our models was the Random Forest Classifier. We used grid searching on most of the models to find the best hyperparameters and then tested the data on the training and hold out sets. We performed a confusion matrix on all models ran to visualize whether or not the models could be used for furthur analysis. The Random Forest Classifier had a precision metric of .68. Which was the highest of all the models. We also came up with a list of top features based on our model. 

## Conclusion 

The features we found to be the most important were duration of time spent with the customer, the amount of money in their account, the age of the client and the days when they are contacted. When the marketing team begins to reach out to people for the campaign they can tailor it to meet these needs. We also concluded that our model continually needs to be optimized for future campaigns through the continual gathering of data. We also recommended that the campaign be changed from a soley phone based campaign.  It's easier to get information if you widen you ways of data collection. Social media polls and mail questionaires could be other avenues of data collection. 