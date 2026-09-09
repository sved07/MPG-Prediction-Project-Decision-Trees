# MPG Prediction Using Decision Trees

Predict a vehicle's MPG (miles per gallon) using a Decision Tree Regressor based on features like horsepower, weight, cylinders, acceleration, model year, and origin. Includes a graph comparing predicted vs actual MPG! 

## Project Overview
This project uses a decision tree to predict fuel efficiency. The model learns from vehicle features and predicts MPG, helping analyze which factors most influence fuel consumption.  

## Features
- Predicts MPG based on:
  - Cylinders
  - Horsepower
  - Weight
  - Acceleration
  - Model year
  - Origin
- Compares predicted vs actual MPG with a scatter plot using matplotlib 
- Evaluates model accuracy with RMSE and R² metrics 

## Dataset
Uses `auto-mpg.csv`, containing MPG and vehicle specifications. Missing values are handled automatically.
