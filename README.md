# CSE351 Final Project

Contributors: [Leila Pan](https://github.com/leipan1), [Wesley Mui](https://github.com/wesleymui), [Alan Thai](https://github.com/alanzthai)

Presentation: 

## Background

In the United States, use of deadly force by police has been a high-profile and contentious issue. 1000 people are shot and killed by US cops each year. The ever-growing argument is that the US has a flawed Law Enforcement system that costs too many innocent civilians their lives. In this project, we will analyze one of America’s hottest political topics, which encompasses issues ranging from institutional racism to the role of Law Enforcement personnel in society.

## Datasets
The datasets on [Kaggle](https://www.kaggle.com/code/oliafedyshyn/fatal-force) provide the data of victims of police brutality from 2015-2017. Data from 2015-early 2017 is the training set and data from
early 2017-mid 2017 is the testing set.

## Dependencies

- Pandas - Data Analysis
- Matplotlib - Data Visualization
- scikit-learn - Machine Learning

## Exploratory Data Analysis

- Merge and clean the data, removing any outliers.
- Which state has the most fatal police shootings? Which city is the most dangerous?
- What is the most common way of being armed?
- What is the age distribution of the victims? Compare age distribution of different races.
- Compare the total number of people killed per race. Compare the number of people killed per race as a proportion of respective races. What difference do you observe?

## Modeling and Question Answering

- For this project we have chosen to use K-Nearest Neighbors, Neural Networks, and Linear Regression Algorithms to try and predict.
- K-nearest neighbors: This is a simple algorithm for both regression and classification problems, which works by finding the K nearest samples to a given query point in the input feature space, and making predictions based   on the average (for regression) or mode (for classification) of their output values.
- Neural Networks: This is a machine learning algorithm inspired by the structure of the brain. It consists of layers of interconnected neurons that learn to extract useful features from the input data and make predictions   based on them. The process of learning involves adjusting the weights of the connections between the neurons based on the errors between the predicted and actual values.
- Linear regression: This is a simple algorithm for regression problems, which tries to find the best linear relationship between a set of input features and a continuous output variable. Linear regression works by minimizing the sum of squared differences between the predicted values and the actual values.
