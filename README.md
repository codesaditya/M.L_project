# Customer Churn Prediction

## Overview

This project is focused on predicting customer churn for a bank, which refers to the likelihood of customers exiting the bank. The dataset used for this project was sourced from Kaggle. A neural network with 3 layers was implemented using TensorFlow in Python to build the predictive model.

## Dataset

The dataset used for this project is available on Kaggle and contains various features about the customers, such as:
- Customer ID
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable)

The target variable is `Exited`, which indicates whether a customer has left the bank (1) or not (0).

## Project Structure

- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks used for data exploration, preprocessing, and model development.
- `README.md`: Project overview and documentation.

## Model Architecture

The neural network model was built using TensorFlow and consists of the following layers:
- **Input Layer**: Matching the number of features in the dataset.
- **Hidden Layer 1**: Dense layer with 6 neurons and ReLU activation.
- **Output Layer**: Dense layer with 1 neuron and sigmoid activation for binary classification.
