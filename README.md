# Machine Learning Deployment using AWS SageMaker

This was my introduction to sentiment analysis and in turn Natural Language Processing.
This project was a part of my Machine Learning nanodegree at Udacity.
The main idea was to learn AWS cloud functionality.
I got to learn everything about how Amazon Sagemaker and Lambda functions and how a deployed model can be fixed if input data is modified.


Code and associated files 

This repository contains code and associated files for deploying ML models using AWS SageMaker. 

## Table Of Contents

* [IMDB Sentiment Analysis - XGBoost - Web App](https://github.com/udacity/sagemaker-deployment/blob/master/Tutorials/IMDB%20Sentiment%20Analysis%20-%20XGBoost%20-%20Web%20App.ipynb) creates a sentiment analysis model using XGBoost and deploys the model to an endpoint. Then describes how to set up AWS Lambda and API Gateway to create a simple web app that interacts with the deployed endpoint.
* [IMDB Sentiment Analysis - XGBoost (Batch Transform)](https://github.com/udacity/sagemaker-deployment/tree/master/Mini-Projects/IMDB%20Sentiment%20Analysis%20-%20XGBoost%20(Batch%20Transform).ipynb) is a notebook that is to be completed which leads you through the steps of constructing a model using XGBoost to perform sentiment analysis on the IMDB dataset.
* [IMDB Sentiment Analysis - XGBoost (Hyperparameter Tuning)](https://github.com/udacity/sagemaker-deployment/tree/master/Mini-Projects/IMDB%20Sentiment%20Analysis%20-%20XGBoost%20(Hyperparameter%20Tuning).ipynb) is a notebook that is to be completed and which leads you through the steps of constructing a sentiment analysis model using XGBoost and using SageMaker's hyperparameter tuning functionality to test a number of different hyperparameters.
* [IMDB Sentiment Analysis - XGBoost (Updating a Model)](https://github.com/udacity/sagemaker-deployment/tree/master/Mini-Projects/IMDB%20Sentiment%20Analysis%20-%20XGBoost%20(Updating%20a%20Model).ipynb) is a notebook that is to be completed and which leads you through the steps of constructing a sentiment analysis model using XGBoost and then exploring what happens if something changes in the underlying distribution. After exploring a change in data over time you will construct an updated model and then update a deployed endpoint so that it makes use of the new model.

### Project

[Sentiment Analysis Web App](https://github.com/udacity/sagemaker-deployment/tree/master/Project) is a notebook and collection of Python files to be completed. The result is a deployed RNN performing sentiment analysis on movie reviews complete with publicly accessible API and a simple web page which interacts with the deployed endpoint. This project assumes that you have some familiarity with SageMaker. Completing the XGBoost Sentiment Analysis notebook should suffice.

![alt text](https://raw.githubusercontent.com/Monica-Kulkarni/Amazon-SageMaker-Lambda/IMDB Review Sentiment Analysis/good_review.jpg)

![alt text](https://raw.githubusercontent.com/Monica-Kulkarni/Amazon-SageMaker-Lambda/IMDB Review Sentiment Analysis/bad_review.jpg)


