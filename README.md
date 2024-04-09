House Price Prediction
Overview
This repository contains code for predicting house prices using various machine learning models. The goal is to develop accurate models that can predict the price of a house based on its features.

Dataset
The dataset used in this project is included in the repository as data.csv. It contains information about various houses including features like number of bedrooms, bathrooms, square footage, etc.

Models
1. Linear Regression
A basic linear regression model is used as a baseline for predicting house prices.

2. Ridge Regression
Ridge regression is employed with hyperparameter tuning to improve performance.

3. Lasso Regression
Lasso regression with feature selection is utilized to potentially improve interpretability and performance.

4. Random Forest Regression
A random forest regression model is trained with hyperparameter tuning to capture non-linear relationships in the data.

5. Deep Neural Network
A deep neural network model is implemented using TensorFlow for more complex modeling of the data.

Evaluation
The models are evaluated based on Mean Squared Error (MSE) and R2 Score metrics to assess their performance in predicting house prices accurately.

Results
The results of the model evaluation are visualized using bar plots showing the MSE and R2 Score for each model.
