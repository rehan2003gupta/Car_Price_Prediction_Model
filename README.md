# 🚗 Car Price Prediction Using Machine Learning  

This project focuses on predicting car prices based on various automobile specifications such as engine size, weight, brand, mileage, fuel type, and more. The goal is to help customers and businesses estimate the right price for a car using machine learning.  

## 📂 Dataset  

The dataset used for this project was sourced from Kaggle:  
🔗 https://www.kaggle.com/datasets/hellbuoy/car-price-prediction  

It contains 205 rows and 26 features, including:  

Technical specs: horsepower, enginesize, curbweight, mileage, cylinder count  

Categorical attributes: car body, fuel type, drive wheel, brand  

Target variable: price  

## 🧠 Model Used  

We built and evaluated a Linear Regression model to predict car prices.  

## 🔧 Tech Stack  
Technology	Purpose  
Python	Core programming  
Pandas, NumPy	Data preprocessing  
Matplotlib, Seaborn	Data visualization  
Scikit-learn	Machine learning  

## 📊 Project Workflow  

1️⃣ Data Cleaning  
✔ Handling missing values  
✔ Removing irrelevant columns (car_ID)  

2️⃣ Feature Engineering  
✔ Extracting car brand from name  
✔ Fixing spelling errors in brand names  
✔ Label Encoding / One-Hot Encoding categorical variables  
✔ Scaling numeric features using StandardScaler  

3️⃣ Model Training  
✔ Train-test split (80/20)  
✔ Training Linear Regression model  

4️⃣ Evaluation Using:  

MAE: 1942  

MSE: 8283565  

RMSE: 2878  

R² Score: 0.895  

## 🔑 Key Insights  
Feature	Impact on Price  
enginesize	➕ strong positive impact  
curbweight	➕ increases luxury  
wheelbase & carwidth	➕ higher stability → higher price  
premium brands (BMW, Porsche, Buick)	➕ significantly increase price  
hatchback/sedan body style	➖ usually budget-friendly  
Toyota, Nissan, Dodge brands	➖ cheaper market positioning  

## 📈 Visualizations Included    

Correlation heatmap  

Feature importance chart  

Actual vs Predicted comparison scatter plot  


## 🙌 Acknowledgment

Dataset by Ashik on Kaggle.
