# Real Estate Price Prediction using Machine Learning
An end-to-end Machine Learning project that predicts Bangalore house prices based on **location, square footage, number of bedrooms (BHK), and bathrooms**.

## Dataset Overview       
**Name**: bengaluru_house_prices          
**Source**: Kaggle datasets                 
**Description**: Bengaluru Home Prices Dataset is a real estate dataset sourced from Kaggle containing approximately 13,000 property listings in Bengaluru with features such as location, area type, size , total square footage, bathrooms, balconies, and price.             
**Number of records**: 13321       
**Number of features**: 8           

## Project Includes
- Data cleaning & feature engineering  
- ML model training in Jupyter Notebook  
- Model serialization using Pickle  
- Flask REST API backend  
- Interactive HTML/CSS/JS frontend  
- Deployment ready server configuration
    
## Problem Statement
Real estate prices vary significantly based on location and property features.  
This project builds a Machine Learning model to estimate house prices in Bangalore using structured housing data and exposes the model through a web interface for predictions.

## The Machine Learning WorkFlow
- Raw dataset preprocessing  
- Handling missing values  
- Location feature reduction  
- Outlier removal  
- One-hot encoding for locations  
- Model training using regression  
- Model evaluation & validation  
- Model export as pickle file  

## Features
- Predict house prices using ML model  
- Location-based pricing intelligence  
- REST API endpoints  
- Frontend UI for user input  
- Model served via Flask  
- JSON prediction response  
- Production server configuration included  

## How the Web App Works
**Model Inputs:**
- Square feet  
- Location  
- BHK  
- Bathrooms
  
**Flow:**
1. Frontend sends request to Flask API  
2. Flask loads trained model  
3. Model predicts price  
4. Result displayed instantly
    
## Results
The trained regression model successfully predicts Bangalore house prices based on:
- Location  
- Total square footage  
- BHK  
- Number of bathrooms

    The model was evaluated using standard regression performance metrics and showed strong predictive capability on unseen validation data. The model achieved an R² score of approximately 0.85–0.90, indicating that it can explain most of the variance in house prices based on the selected features.
  
## Benefits
- Instant house price estimation  
- Data-driven property valuation  
- Reduces manual estimation errors  
- Demonstrates full ML lifecycle  
  
## Future Improvements
- Add advanced models (XGBoost, Gradient Boosting)  
- Feature importance visualization dashboard  
- Automated retraining with new market data  
- Use latest real estate datasets  
- Add time-based price trends  
- Convert Flask API to FastAPI for better performance
  
