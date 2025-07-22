# Diabetes Prediction Using Decision Tree Regressor

This project uses a Decision Tree Regressor model to predict diabetes progression based on diagnostic measurements. The dataset is sourced from `sklearn.datasets`, specifically the Diabetes dataset.

## 📁 Project Structure


## 📌 Objective

The goal of this project is to build a regression model using Decision Tree Regressor that can predict the diabetes progression metric based on several medical features such as age, sex, BMI, blood pressure, and blood serum measurements.

## 🧠 Machine Learning Algorithm

- **Model Used**: `DecisionTreeRegressor`
- **Library**: `scikit-learn`

## 📊 Dataset

- **Source**: `sklearn.datasets.load_diabetes()`
- **Features**: 10 numerical features (e.g., age, sex, BMI)
- **Target**: A quantitative measure of disease progression one year after baseline

## 🧪 Steps Performed

1. Data loading and exploration
2. Feature selection and preprocessing
3. Train-test split
4. Model training using Decision Tree Regressor
5. Performance evaluation using R² score and Mean Squared Error
6. Visualization of predictions vs actual values

## 📈 Results

- Model is evaluated using regression metrics like:
  - Mean Squared Error (MSE)
  - R² Score
- Graphs/plots included to visualize model performance

## 🛠️ Requirements

Make sure you have the following Python libraries installed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
