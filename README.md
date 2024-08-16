
# House Price Prediction: EDA and Linear Regression Model

This repository contains a project aimed at predicting house prices using Exploratory Data Analysis (EDA) and Linear Regression modeling. The goal is to understand the relationships between different features and the target variable (house prices) and then build a predictive model.

Before running the code, ensure you have the following Python libraries installed:

pandas
numpy
matplotlib
seaborn
scikit-learn

#DATA   
The dataset (Housing.csv) is included in the data/ directory. This dataset should contain various features like the number of bedrooms, bathrooms, basement, etc., and the corresponding house prices.

#Project Overview

Exploratory Data Analysis

1)Data Cleaning: 
 Missing values are handled, and irrelevant features are removed.
2)Visualization: Various plots (histograms, scatter plots, correlation heatmaps) are generated to understand the relationships between features and house prices.  
3)Feature Engineering: New features may be created based on the insights gained during the EDA.

Linear Regression Model

1)Model Training: The dataset is split into training and testing sets. The model is trained on the training set.  
2)Model Evaluation: The model's performance is evaluated using metrics like Mean Squared Error (MSE) and R-squared.
