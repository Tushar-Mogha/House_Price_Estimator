# 🏠 Delhi House Price Estimator (ML Project)

This project focuses on building machine learning models to estimate **housing prices in Delhi**, using a dataset with 40+ features such as location, area, bedrooms, amenities, and even Vaastu compliance.

---

## 📌 Project Objective

To build a regression model that can **predict property prices** based on various physical and categorical features of the house.

---

## ✅ Work Completed

### 🔍 Data Analysis & Preprocessing
- Cleaned and handled missing values
- Converted categorical features using one-hot encoding
- Scaled features where necessary

### ⚙️ Models Implemented
- **Linear Regression**  
- **Random Forest Regressor**  
- **XGBoost Regressor**

### 📊 Model Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- R² Score

| Model              | MAE      | RMSE     | R² Score |
|-------------------|----------|----------|----------|
| Linear Regression | 38.1 L   | 54.6 L   | 0.23     |
| Random Forest     | 29.3 L   | 44.2 L   | 0.29     |
| XGBoost           | 27.8 L   | 41.6 L   | 0.32     |

> ✅ XGBoost performed best among the three models.

---

## 📈 Feature Importance

Feature importance plots were generated for:
- Random Forest
- XGBoost

These helped in understanding which features most influence the price prediction.

---

## 🧪 Sample Prediction

- **Input:** A test record with real features from the dataset  
- **Output:** `₹ 2.42 Crores` (predicted price)

---

## 🔄 Next Steps

- 🔧 Deploy as a **web app** for real-time predictions using Streamlit or Flask
- 📉 Try out hyperparameter tuning and cross-validation for better performance
- 🧠 Experiment with more advanced ensemble models

---

## 💬 Feedback Welcome

If you have suggestions on improving the model or deployment ideas, feel free to connect!

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

