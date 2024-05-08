# HOUSE PRICE PREDICTION USING PYTORCH
This repository hosts a PyTorch implementation of a linear regression model aimed at predicting house prices. 
This project is designed to showcase a basic machine learning workflow from data preparation to training and making predictions.

## objective
The primary objective of this project is to build a machine learning model using PyTorch that can predict house prices based on various features. 
This project aims to demonstrate the use of neural networks in regression problems, specifically in predicting real estate prices.

## Data
the data contains 1460 rows and 81 columns.The link for the data is given below
https://github.com/alnxha7/House_price_prediction_using_PyTorch/blob/main/houseprice.csv

## Features and Data Preprocessing
The dataset may contain various features such as:

Basic features: square footage, number of bedrooms, number of bathrooms
Location-based features: neighborhood, proximity to amenities
Other features: age of the house, type of heating, garage size
Data preprocessing steps include:

Handling missing data (imputation or removal)
Converting categorical data to numerical format (one-hot encoding or label encoding)

## Model Development

We will use PyTorch to develop a regression model to predict house prices. The model will consist of:

Input layer corresponding to the number of features
Several hidden layers with appropriate activation functions (e.g., ReLU)
An output layer with a single node for the predicted price
Hyperparameters to consider:

Number of hidden layers and units per layer
Learning rate
Batch size and number of epochs

batch size = 1200
epochs = 5000
test size = 15%

## Model Training
The model will be trained using a suitable loss function, such as Mean Squared Error (MSE) and later used Root Mean Squared Error(RMSE). An optimizer like Adam will be used to adjust the weights during training. The dataset will be split into training and validation sets to evaluate the model's performance during training.

## Model Evaluation
To evaluate the model's effectiveness, we will use metrics such as:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R-squared (coefficient of determination)
Additional validation techniques like cross-validation or hold-out validation can be used to ensure robustness.
### got an RMSE value of 56874.49609375

you can see it in the plot of loss(RMSE)

![Screenshot 2024-05-08 125857](https://github.com/alnxha7/House_price_prediction_using_PyTorch/assets/129566733/ba0437eb-e44e-4a8c-8840-e72340e85676)








