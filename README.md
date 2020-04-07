# This repository contains some machine learning projects which I worked on. 
Projects include:
1. Fraud detection 
2. Pnemonia detection
3. Stock Prediction

## Fraud Detection

The PwC global economic crime survey of 2016 suggests that approximately 36% of organizations experienced economic crime. Therefore, there is definitely a need to solve the problem of credit card fraud detection. The task of fraud detection often boils down to outlier detection, in which a dataset is scanned through to find potential anomalies in the data. In the past, this was done by employees  which checked all transactions manually. With the rise of machine learning, artificial intelligence, deep learning and other relevant fields of information technology, it becomes feasible to automate this process and to save some of the intensive amount of labor that is put into detecting credit card fraud.

In this project I train a model with pandas, seaborn and scikit-learn to create a fraud detection classifier.

Build a logistic regression model using Scikit-learn to predict fraudulent transactions by training it on this kaggle dataset. Before training the model, create at least 1 visualization of the data using any seaborn library. 

Jupyter notebook used. 

## Stock Prediction
The project is to build 3 different types of regression lines to predict stock prices using Python, then print out the prediction for the best performing one.

Step 1 - Go to Yahoo Finance and find a stock price that you want to predict. Click on historical data, then download the CSV of that stocks price history https://finance.yahoo.com/quote/AAPL/history?p=AAPL  

Step 2 - Use Scikit learn to try out 3 different types of regression models to predict the price of that stock for a future date. 

Step 3 - Visualize the result using matplotlib or another plotting library of your choice


## Pnemonia detection 

Training a classifier on medical images is a crucial task to aid doctors and provide lower cost services to patients. If we can build a classifier that can diagnosis a given disease and provide it to patients who can't afford a doctor as an app, we have a scalable business. In this homework, we're going to perform transfer learning to predict pneumonia in a patient, given their chest x-ray data.

Retrained the 'inception v3' image classifier on the pneumonia dataset using Tensorflow+Keras. 
Jupter notebook showing 2 examples of it making predictions on images from the testing dataset. 
