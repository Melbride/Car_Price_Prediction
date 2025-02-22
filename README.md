# 🚗 Car Price Prediction Model  

## 📌 Overview  
Predicting car prices based on various features such as model, year, mileage, motor_type, and more. The goal is to build a machine learning model that accurately estimates car prices based on vehicle characteristics.

## 📊 Dataset  
- The dataset contains features such as `model`, `year`, `running`, `color`, `type`, `status`, `motor_volume`, `car_age`, and `power_per_liter`.  
- **Target Variable:** `price`  

## ⚙️ Model Approach  
### **🔹 Preprocessing**  
- Converted categorical features into numerical using **label encoding**.
- Applied log transformation to the price column to normalize skewed values.
- Handled outliers by removing extreme values.  
- Feature selection: Removed low-importance features (car_age, type) during hyperparameter tuning.  
- Split the dataset into training and validation sets.  

### **🔹 Training & Evaluation**
### **🔹 Models Used**  
- **XGBoost Regressor** (Primary Model)  
- Linear Regression  
- Random Forest Regressor  

### **🔹 Evaluation Metrics**  
- R² Score: Measures how well the model explains variance in car prices
- Mean Absolute Error (MAE): Evaluates prediction accuracy  

## 🎯 Final Model Performance  
- **Validation R² Score:** `0.7740`  
- **MAE:** (Lower is better)  

## 📂 Project Files  
- 🏆 `car_price_model.pkl` - Trained Model  
- 📜 `Car Price Prediction.ipynb` - Code & Model Training  
- 📊 `train.csv` & `test.csv` - Dataset  

## 🚀 Future Improvements  
- Feature interaction for higher accuracy.  
- Hyperparameter tuning for better generalization.  

## 🔗 How to Run the Model  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/your-repository.git
2. Navigate to the project folder:
   ```bash
   cd your-repository
3. Run the Jupyter Notebook::  
   ```bash
   jupyter notebook
4. Open Car Price Prediction.ipynb and execute the cells.  
   

