# SQL Driven Machine Learning Tutorial: Customer Churn Prediction
In this tutorial, we will walk through an example of using SQL-driven machine learning to predict customer churn. We will be using the [JupySQL](https://github.com/ploomber/jupysql) package to run SQL queries within a Jupyter Notebook and a public dataset available on Kaggle.

Customer churn is a classification problem. In customer churn prediction, the goal is to classify customers into two categories: 
those who will churn (leave the company) and those who will not churn (remain with the company). 

This is a binary classification problem since there are only two possible outcomes (churn or not churn) for each customer.

<p align="center">
  <a href="https://binder.ploomber.io/v2/gh/idomic/ploomber_odsc_east_2023/main?urlpath=lab/tree/odsc.ipynb"> <img src="_static/get-started.svg" alt="Get Started"> </a>
</p>

## Table of Content:
1. Introduction of the problem, use case, and background story. 
2. Introduction to JupySQL and the dataset.
3. EDA + fitting the model 
4. Generating a stakeholder report
5. Questions and Answers

## Prerequisites
- Install and run a Jupyter Lab instance
- Install the JupySQL package using pip:

You can run:

`pip install -r requirements.txt`

Once that's done, you can run the jupyter lab using this command (make sure you're in the main directory):

`jupyter lab`

Once you have the jupyter running, please open `odsc.ipynb` (you can double click it).
<p align="center" style="margin-left: auto; margin-right: auto; max-width: 60%;">
    <img src="_static/QR.png" alt="JupySQL QR Code" style="max-width: 60% !important;">
</p>