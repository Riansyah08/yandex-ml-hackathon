# Yandex ML Hackaton
This repository contains a solution for the **Yandex ML Hackaton** with **Jakarta travel time prediction Dataset**.  
The task is to build a regression model to predict the **travel time** of car trips in Jakarta based on route features, weather conditions, and traffic data.
<br><br>

### 📌 Problem Statement
The goal is to predict the numerical target variable **travel_time** for a given test dataset using features extracted from trip data.
<br><br>

### 📂 Dataset
- Training set: Includes features and target variable (travel_time)
- Test set: Includes features only (predictions required)
- Features may include:
  - Start and end locations
  - Traffic conditions
  - Weather data
  - Other trip characteristics
<br><br>

### 🚀 Approach
1. Data Preprocessing: Cleaning, feature transformation, scaling, and encoding categorical features.
2. Model Training:
   - Linear Regression, Ridge, Lasso
   - MLP Regressor (Neural Network)
   - Tree-based models: XGBoost, LightGBM, CatBoost
3. Evaluation: Mean Squared Error (MSE) and R² Score on validation data.
4. Submission File: A single-column .csv file containing predictions for each trip in the test dataset.
<br><br>

### 🛠️ Dependencies
The following Python libraries are required:  
numpy  
pandas  
matplotlib  
seaborn  
plotly  
xgboost  
lightgbm  
catboost  
tensorflow  
scikit-learn  
<br>
Install all dependencies:  
**pip install** -r requirements.txt
<br><br>

### 📜 How to Run
1. Clone the repository:  
**git clone** https://github.com/yourusername/jakarta-travel-time-prediction.git  
**cd** jakarta-travel-time-prediction  
2. Open the notebook:
jupyter notebook Machine_Learning_Hackaton.ipynb
3. Run all cells to:
   - Load and preprocess data
   - Train models
   - Generate predictions
   - Export submission file
<br><br>

### 📂 Output
submission.csv → Contains predictions in a single, non-indexed column matching the test set order.
