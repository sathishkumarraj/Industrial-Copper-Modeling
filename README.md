<h1 align="center">Hi, I'm SATHISH KUMAR R</h1>
<img align="right" alt="Coding" width="300" src="https://miro.medium.com/v2/resize:fit:1400/1*7szjK4i9L5FoEp48DPBMOA.gif">

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/tirumal-s/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/sathishkumarraj/" height="30" width="40" /></a>
<a href="https://www.instagram.com/rajendsathish_sk/?hl=en" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="mr.war_n_ing" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>


# Industrial-Copper-Modeling-Project

Application Link: https://tulasinnd-industrial-copper.streamlit.app/

Demo Video Link: https://www.linkedin.com/posts/tulasi-n-49b6111b0_python-machinelearning-decisiontrees-activity-7058375260022181888-oCFS?utm_source=share&utm_medium=member_desktop

## Introduction
This project aims to develop two machine learning models for the copper industry to address the challenges of predicting selling price and lead classification. Manual predictions can be time-consuming and may not result in optimal pricing decisions or accurately capture leads. The models will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm, to predict the selling price and leads accurately.

## Regression model details
The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, outlier detection and handling, handling data in wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm.

## Classification model details
Another area where the copper industry faces challenges is in capturing the leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer. You can use the STATUS variable with WON being considered as Success and LOST being considered as Failure and remove data points other than WON, LOST STATUS values.

## Solution

The solution includes the following steps:

Exploring skewness and outliers in the dataset.

Transforming the data into a suitable format and performing any necessary cleaning and pre-processing steps.

Developing a machine learning regression model which predicts the continuous variable 'Selling_Price' using the decision tree regressor.

Developing a machine learning classification model which predicts the Status: WON or LOST using the decision tree classifier.

Creating a Streamlit page where you can insert each column value and get the Selling_Price predicted value or Status (Won/Lost).

## Requirements

This project requires the following libraries to be installed:

NumPy

Pandas

Scikit-learn

Streamlit

## Getting Started

Clone the repository.

Install the required libraries.

Run the Streamlit app using the command: streamlit run app.py.

Enter the values for each column to get the Selling_Price predicted value or Status (Won/Lost).
