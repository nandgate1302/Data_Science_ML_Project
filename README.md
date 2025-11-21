# Indian Food Calorie Prediction – Data Science & Machine Learning Project

This project builds a machine learning model to predict the calorie content of Indian dishes using two datasets:  
- **Dish-level nutrition dataset**  
- **Ingredient-level nutrition dataset**

It performs data preprocessing, exploratory data analysis, model training, clustering, and allows user-input calorie prediction.

---

## 📊 Features

- Loads and processes dish-level and ingredient-level nutritional data  
- Performs Exploratory Data Analysis (EDA) using Matplotlib  
- Trains multiple ML models:
  - Linear Regression  
  - Ridge Regression  
  - Random Forest  
- Evaluates model performance (R², MAE, RMSE)  
- Performs nutrient-based clustering using KMeans  
- Includes a **user-input calorie predictor**:
  - If the dish exists in the dataset → shows actual calories  
  - Otherwise → predicts based on ingredient-level data  
- Uses a simple nutrient-based estimator as baseline  

---

## 🛠 Tools & Libraries

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  
- Google Colab  

---

## 📁 Datasets Used

### **Dish-level Dataset**
Contains calorie and nutrition values (per 100g) for ~300 Indian dishes including carbohydrates, proteins, fats, sugar, fibre, sodium, calcium, iron, vitamin C, and folate.

### **Ingredient-level Dataset**
Contains nutrient profiles for common Indian ingredients (milk, paneer, pulses, vegetables, rice, ghee, etc.)

---

## 🚀 Usage Instructions

Open the notebook in Google Colab:

1. The notebook automatically loads datasets from GitHub (via raw links).  
2. Run all cells to train the models, view EDA, and use the calorie predictor.

---

## 👤 Author

**Nandana Sasikumar**  
B.Tech Computer Science  & Engineering

---
