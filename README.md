# Predicting-the-Sales-price-of-Bulldozers-using-Machine-Learning
In this notebook, we are going through an example machine learning project with the goal of predicting sales price of the bulldozers.
Predicting the Sales price of Bulldozers using Machine Learning
In this notebook, we are going through an example machine learning project with the goal of predicting sales price of the bulldozers.

1. Problem Defintion
How well can we predict the future sales price of a bulldozer , given its charactersistcs and previous examples of how much similar bulldozers have been sold for

2. Data
This data is being downloaded from Kaggle bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/overview

There are 3 main datasets:

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

Note The goal for most regression evaluation metrics is to minimise the error. For example, the goal of this project will be to build a machine learning model which minimises RMSLE.
