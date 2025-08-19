✈️ Flight Delay Prediction Model

This project implements a linear regression model with gradient descent to predict total flight arrival delays using historical U.S. flight data (2013–2023).

🔹 Key Features

  Data Preprocessing:
  
    Cleaned and filtered the dataset (reduced from ~171k to ~99k rows).
    
    Encoded categorical values (carrier names, airport codes) using hash maps.
    
    Normalized features for improved gradient descent performance.
  
  Model Implementation (C++):
  
    Custom CSV reader and preprocessing pipeline.
    
    Gradient descent–based linear regression implementation.
    
    Outputs model weights, Mean Squared Error (MSE), Mean Absolute Error (MAE), and predicted total delays.
    
    Allows user input for year and month to generate targeted predictions.
  
  Python / Jupyter Notebook:
  
    Scikit-learn linear regression for comparison.
    
    Data visualization (actual vs. predicted delays, delay type distributions).
    
    Feature engineering with polynomial expansion and feature selection.

📊 Results

C++ Implementation: Achieved low MSE and MAE values, showing effective learning from the dataset.

Scikit-learn Comparison: Used as a benchmark but produced slightly different results.

Visualizations: Graphs highlighting the relationship between predicted vs. actual delays and delay causes.
