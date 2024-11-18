# Laptop Price Prediction  

## Problem Statement  
This project aims to predict the price of a laptop based on its specifications using regression machine learning models.  

## Data Preprocessing and Cleaning  
To ensure high-quality predictions, the dataset underwent the following preprocessing steps:  
1. **Handling Missing Values**: Missing values were imputed or dropped based on their significance.  
2. **Feature Encoding**: Categorical features, such as brand and processor type, were encoded using techniques like One-Hot Encoding.  
3. **Scaling and Normalization**: Numerical features were standardized to improve model performance.  
4. **Feature Engineering**: New features like price-per-performance ratio were derived to enhance prediction accuracy.  
5. **Outlier Removal**: Extreme outliers were removed to avoid skewing the regression models.  

## Model Training  
The cleaned and preprocessed data was split into training and testing sets. Various regression models were trained and evaluated:  

1. **Linear Regression**  
2. **Ridge Regression**  
3. **Lasso Regression** 
4. **Decision Tree Regression**  
5. **Random Forest Regression**  
6. **K-Nearest Neighbors (KNN) Regression**  

Among these models, **Random Forest Regression** delivered the best performance with high accuracy and robust predictions.  

## Model Evaluation  
The models were evaluated using metrics like:  
- Accuracy 
- Precision 
- Recall
- F1 Score

Random Forest Regression consistently outperformed others across these metrics, making it the model of choice.  

## Web Application  
A web application was developed using **Flask** to make the model accessible to users. The app allows users to:  
1. Input laptop specifications (e.g., RAM, processor type, storage).  
2. Receive a predicted price real time for the specified laptop.  

### UI




