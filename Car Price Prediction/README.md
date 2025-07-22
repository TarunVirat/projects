# 🚗 Used Car Price Prediction

This project aims to predict the price of used cars in India using machine learning models. The dataset was collected from **cardekho.com** and includes various features such as model, year, fuel type, transmission type, kilometers driven, and more.

---

## 📌 1. Problem Statement

- Predict the selling price of used cars based on relevant features.
- Help sellers determine competitive pricing based on market data.
- Useful for online car resale platforms and data-driven price forecasting.

---

## 📊 2. Data Collection

- Data scraped from **cardekho.com**.
- Dataset includes **15,411 rows** and **13 columns**.
- File used: `cardekho_imputated.csv`

---

## 🧹 3. Data Cleaning

- Handled missing values and duplicates.
- Dropped unnecessary columns (`car_name`, `brand`).
- Inspected data types and unique values in features.
- Separated features into:
  - Numerical Features
  - Categorical Features
  - Discrete vs Continuous Features

---

## 🧮 4. Feature Engineering

- Label Encoding for `model` feature.
- One-Hot Encoding for `seller_type`, `fuel_type`, and `transmission_type`.
- Standard Scaling applied to numerical features.
- Feature transformation done using `ColumnTransformer`.

---

## 🔀 5. Train-Test Split

- 80% training and 20% testing split.
- `X_train`, `X_test`, `y_train`, `y_test` created using `train_test_split`.

---

## 🤖 6. Model Training & Evaluation

Trained and compared the following regression models:

- Linear Regression
- Lasso
- Ridge
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost

### ✅ Evaluation Metrics:

- **MAE**: Mean Absolute Error  
- **RMSE**: Root Mean Squared Error  
- **R² Score**: Coefficient of Determination

---

## 🔧 7. Hyperparameter Tuning

Used **RandomizedSearchCV** to tune:

- **Random Forest**  
  - `max_depth`, `max_features`, `min_samples_split`, `n_estimators`
- **XGBoost**  
  - `learning_rate`, `max_depth`, `n_estimators`, `colsample_bytree`

---

## 🔁 8. Final Model Evaluation (After Tuning)

Retrained:
- **Random Forest Regressor**
- **XGBoost Regressor**

Performance was evaluated again on train and test sets to check for overfitting and generalization.

---

## 📦 Dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost
```

---

## 📁 Files

- `cardekho_imputated.csv` – Cleaned dataset
- `used_car_price_prediction.ipynb` – Complete notebook

---


