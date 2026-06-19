# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project builds a machine learning regression model to predict house prices using various housing characteristics. It demonstrates an end-to-end machine learning pipeline, including exploratory data analysis, feature preprocessing, model comparison, evaluation, and model serialization.

---

## 📊 Dataset

The project uses a housing dataset containing information about residential properties.

### Features

* Median Income (`MedInc`)
* House Age (`HouseAge`)
* Average Rooms (`AveRooms`)
* Average Bedrooms (`AveBedrms`)
* Population (`Population`)
* Average Occupancy (`AveOccup`)
* Latitude
* Longitude

### Target Variable

* House Price

---

## 🔍 Exploratory Data Analysis

The notebook includes:

* Dataset shape and information
* Summary statistics
* Missing value analysis
* Duplicate value analysis
* Unique value analysis
* Correlation heatmap
* Skewness analysis
* Histogram
* Boxplot
* Q-Q Plot
* Scatter plots
* Pairplot visualization

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

* Log transformation of the target variable
* Power Transformation for skewed features
* Robust Scaling
* Standard Scaling for remaining numerical features
* `ColumnTransformer` and `Pipeline` for clean preprocessing

---

## 🤖 Machine Learning Models

The following regression models were trained and compared:

* Ridge Regression
* Lasso Regression
* Random Forest Regressor
* Gradient Boosting Regressor

Model comparison was performed using **5-Fold Cross Validation**.

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Cross Validation R² Score
* Test R² Score
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)

The best-performing model was saved using **Joblib** for future predictions.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Joblib

---

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── house_price_model.pkl
├── requirements.txt
```

---

## 🚀 How to Run

1. Clone this repository.

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

4. Run all cells sequentially to reproduce the results.

---

## 🎯 Project Highlights

* Complete regression workflow
* Data visualization and EDA
* Feature engineering and preprocessing pipeline
* Multiple model comparison
* Cross-validation for reliable performance estimation
* Model persistence using Joblib

---

