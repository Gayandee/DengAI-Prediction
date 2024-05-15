# DengAI-Prediction

## Problem Definition
Predict the number of dengue fever cases reported weekly in San Juan, Puerto Rico, and Iquitos, Peru, using environmental data to aid in public health initiatives.

## Proposed Solution
We propose to utilize the dataset for a predictive task, as a regression task, to forecast the total cases of dengue fever. 
Mapping the Problem: The solution involves mapping environmental factors to disease incidence, aiding in resource allocation and research efforts to combat pandemics.
(Resource: https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/page/80/)

## The Process
The process begins with importing necessary libraries and reading the training and testing datasets. 
The project also includes detailed visualizations such as histograms, time series plots, correlation matrices, pair plots, and boxplots to understand the relationships between features and the target variable.
Data preprocessing involves converting temperature features to Kelvin, visualizing feature trends over time, and extracting additional temporal features. Descriptive statistics and null value counts are generated to understand the dataset's distribution and identify missing values. 
Advanced preprocessing techniques like interpolation are applied to handle missing data, and new features are engineered, including rolling means and interaction terms. Label encoding is used for categorical variables, and the data is split into separate datasets for different cities. 
The project uses Support Vector Regression (SVR) and Random Forest Regression models to predict dengue cases, evaluating its performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
By the error we proved Random Forest Regression is way more efficient for this.

