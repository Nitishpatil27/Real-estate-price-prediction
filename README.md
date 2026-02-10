# Real Estate Price Prediction using Machine Learning

An end-to-end Machine Learning project that predicts Bangalore house prices based on location, square footage, number of bedrooms (BHK), and bathrooms.

#This project includes:
*Data cleaning & feature engineering
*ML model training in Jupyter Notebook
*Model serialization using Pickle
*Flask REST API backend
*Interactive HTML/CSS/JS frontend
*Deployment ready server 

# Problem Statement
Real estate prices vary significantly based on location and property features. This project builds a Machine Learning model to estimate house prices in Bangalore using structured housing data and exposes the model through a web interface for predictions.

#The ML workflow includes:
*Raw dataset preprocessing
*Handling missing values
*Location feature reduction
*Outlier removal
*One-hot encoding for locations
*Model training using regression
*Model evaluation & validation
*Model export as pickle file

#Features
*Predict house prices using ML model
*Location-based pricing intelligence
*REST API endpoints
*Frontend UI for user input
*Model served via Flask
*JSON prediction response
*Production server config included

#How the Web App Works
*Model Inputs:[Square feet,Location,BHK,Bathrooms]
*Frontend sends request to Flask API
*Flask loads trained model
*Model predicts price
*Result displayed instantly

#Results
*The trained regression model successfully predicts Bangalore house prices based on key property features such as location, total square footage, BHK, and number of bathrooms.

#Benefits
*Instant house price estimation
*Data-driven property valuation
*Reduces manual estimation errors
*Demonstrates full ML lifecycle

#Future Improvements
*Add advanced models (XGBoost, Gradient Boosting)
*Feature importance visualization dashboard
*Automated retraining with new market data
*Use latest real estate datasets and add time-based price trends
*Convert Flask API to FastAPI for performance

