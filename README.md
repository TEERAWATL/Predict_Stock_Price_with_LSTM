# Predict Stock Price with LSTM

Predict stock prices using an LSTM model.

## Description

This project aims to predict stock prices using an LSTM (Long Short-Term Memory) model. The model allows users to input data to predict future stock prices.


## Usage

Open the notebook in Google Colab and run the cells in order to execute the project.

## Dependencies

The project requires the following libraries:

- numpy
- pandas
- matplotlib
- scikit-learn
- keras

Dataset Preparation
Collect historical stock price data.
Load the dataset using pandas.
Data Preprocessing
Preprocess the data by handling missing values and scaling the data using MinMaxScaler from scikit-learn.
Prepare the data for the LSTM model by creating time-series windows.
Model Training
Create an LSTM model using the Sequential API from Keras.
Add LSTM and Dense layers to the model.
Train the model using the prepared training set.
Model Evaluation
Evaluate the model's performance using the test set.
Calculate the mean squared error using the mean_squared_error function from scikit-learn.
Visualize the actual stock prices and the predicted stock prices using matplotlib.
User Input Prediction
Create a function to accept user input for new stock price data.
Preprocess the user input data and prepare it for the LSTM model.
Use the trained LSTM model to predict the future stock prices based on the user input.
