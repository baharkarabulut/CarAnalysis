# Car Price Prediction Using Neural Networks

This project predicts used car prices based on various features using a neural network built with TensorFlow and Keras. The dataset contains Mercedes car listings with attributes such as year, mileage, tax, mpg, and engine size.

## Project Overview

- Dataset has 13,119 Mercedes cars with details like year, price, transmission, mileage, tax, mpg, and engine size.
- Exploratory Data Analysis (EDA) was performed to visualize distributions and correlations.
- Outliers (top 1% most expensive cars) were removed to improve model performance.
- Data preprocessing includes dropping the 'transmission' feature, normalization using MinMaxScaler, and train-test split (70%-30%).
- The model is a deep neural network with 4 hidden layers (12 neurons each, ReLU activation) and an output layer for price prediction.
- Mean Squared Error (MSE) is used as the loss function, and Adam optimizer is applied.
- The model is trained for 300 epochs with a batch size of 250.

## Dataset

- File: `merc.xlsx`
- Features used: year, mileage, tax, mpg, engineSize
- Target variable: price

## How to Run

1. Clone the repository.
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow openpyxl
