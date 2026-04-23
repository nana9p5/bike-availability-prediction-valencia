# Bike Availability Prediction in Valencia

## 📌 Project Overview
This project was developed as part of my Master's in Artificial Intelligence & Big Data Analytics at UPV.

The goal is to predict the number of available bikes at bike-sharing stations in Valencia with a 3-hour forecast horizon.

This is a real-world machine learning problem with practical applications for both users and the bike rental company.

## 🎯 Business Context
A bike rental company recently expanded its number of bike stations in Valencia. Since the new stations have only been operating for one month, the company wants to anticipate how bike traffic will evolve in the coming months.

Accurate predictions can help:

- Users know whether bikes or free docks will be available in advance
- The company avoid full or empty stations
- Operations teams plan bike redistribution more efficiently

## 🎯 Objective
Predict the number of available bikes at test stations 3 hours ahead.

## 📊 Evaluation Metric
The model is evaluated using Mean Absolute Error (MAE).

📈 Results  
The model achieved a Mean Absolute Error (MAE) of:  
MAE = 2.989  
This means that, on average, the prediction error is around 3 bikes per station.  

💡 Interpretation  
This level of accuracy is relevant for real-world operations:  
It allows the company to anticipate station saturation or shortages  
It supports better planning of bike redistribution  
It improves user experience by providing reliable availability forecasts  

```text
MAE = average absolute difference between predicted and real bike availability


