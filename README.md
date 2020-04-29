# Predicting Rainfall in Australia

## Group Members
* Hanumasri Bollepalli
* Madhuri Pawle
* Pavanitha Jampala

## Research Question

Exploratory data analysis will be used to visualize imporant trends in the data. EDA will also provide input into the need for feature pre-processing such as dimensionality reduction, null handling and feature scaling. The pre-processed data (pertinent features) will be used to analyze the research question: Will it rain tomorrow?

## Source & Domain

* Domain: Weather forecasting. Precisely to predict whether it will rain tomorrow or not?

* Source: Kaggle, https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

* We stored the data on BigQuery in Google Cloud Platform.

## Target Audience

The target audience would be the general public of respective areas in Australia. The dataset consists of 49 locations so people living in those 49 locations can have the benifit of knowing if it will rain the next day or not and plan their day accordingly.

## Data Preprocessing

The data cleaning steps that we are going to follow are :
* Make sure the datatypes are correct.
* Replace missing numerical values with Median of the column.
* Handle outlier using top-coding approach.
* Replace missing categorical data with the most frequent label.
* Encode Categorical data using One Hot Encoding as Logistic Regression cannot handle categorical data.

## Tentative Plan

* Load Data onto BigQuery
* Exploratory Data Analysis and Data Preprocessing using AI Platform
* Dashboard for User group, Dashboard for Data Engineers
* Apply Logistic Regression Model on the dataset.
* Evaluation of Results
* Steps for production model
* Final Dashboard for User Group
