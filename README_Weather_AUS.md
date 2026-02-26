# 🌦 Weather in Australia - Rain Prediction

## Logistic Regression Classification Project

![Python](https://img.shields.io/badge/Python-3.9+-blue) ![Machine
Learning](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

------------------------------------------------------------------------

## 📌 Project Overview

This project builds a **Logistic Regression model** to predict whether
it will rain tomorrow (`RainTomorrow`) using the Weather Australia
dataset.

The project follows a complete Machine Learning pipeline including:

-   Exploratory Data Analysis (EDA)
-   Data Cleaning
-   Feature Engineering
-   Encoding
-   Feature Scaling
-   Model Training
-   Classification Metrics Evaluation
-   ROC Curve & AUC Analysis

------------------------------------------------------------------------

## 📊 Dataset

The dataset contains daily weather observations from multiple locations
in Australia.

### Key Features:

-   Location\
-   MinTemp / MaxTemp\
-   Rainfall\
-   WindGustSpeed\
-   Humidity9am / Humidity3pm\
-   Pressure9am / Pressure3pm\
-   RainToday\
-   RainTomorrow (Target Variable)

### Target Variable:

RainTomorrow\
- 1 → Rain\
- 0 → No Rain

------------------------------------------------------------------------

## 🛠 Data Preprocessing

### 1️⃣ Handling Missing Values

-   Columns with excessive missing values were removed.
-   Numerical features → filled using median.
-   Categorical features → filled using mode.

### 2️⃣ Feature Engineering

-   Extracted Year, Month, and Day from the Date column.
-   Removed original Date column.

### 3️⃣ Encoding

-   RainTomorrow → Binary Encoding (Yes=1, No=0)
-   RainToday → Binary Encoding
-   Other categorical variables → One-Hot Encoding

### 4️⃣ Feature Scaling

Standardization (Z-score scaling) was applied:

X_scaled = (X - mean) / standard_deviation

This improves convergence and model stability.

------------------------------------------------------------------------

## 🧠 Logistic Regression Model

Logistic Regression uses the Sigmoid function:

sigmoid(z) = 1 / (1 + e\^(-z))

It outputs a probability between 0 and 1.

If probability ≥ 0.5 → Predict Rain\
If probability \< 0.5 → Predict No Rain

------------------------------------------------------------------------

## 📈 Model Evaluation

The model was evaluated using:

-   Confusion Matrix\
-   Accuracy\
-   Precision\
-   Recall\
-   F1-Score\
-   ROC Curve\
-   AUC Score

ROC-AUC measures the model's ability to distinguish between rainy and
non-rainy days.

------------------------------------------------------------------------

## 📁 Repository Structure

Weather-AUS-Logistic-Regression/ │ ├──
Weather_AUS_Project_Professional_Krollos_Ayad.ipynb\
├── weatherAUS.csv\
├── README.md

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone the repository:

git clone
https://github.com/your-username/Weather-AUS-Logistic-Regression.git

2.  Open the notebook in Jupyter Notebook or VS Code.
3.  Run all cells.

------------------------------------------------------------------------

## 🎯 Key Learning Outcomes

✔ End-to-end ML workflow\
✔ Logistic Regression mathematics\
✔ Handling missing data\
✔ Feature engineering\
✔ Classification metrics analysis\
✔ ROC-AUC interpretation

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Apply Regularization (L1 / L2)\
-   Hyperparameter tuning\
-   Handle class imbalance\
-   Compare with other models (Random Forest, XGBoost)\
-   Deploy as interactive dashboard

------------------------------------------------------------------------

## 👤 Author

**Krollos Ayad**\
Machine Learning Engineer
