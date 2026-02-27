# 🏠 Melbourne Housing Price Prediction

A Machine Learning project that predicts house prices in Melbourne, Australia using regression models.

---

## 📌 Project Overview

This project aims to build a machine learning model that predicts property prices in Melbourne based on various features such as:

- Number of rooms
- Property type
- Distance from CBD
- Land size
- Building area
- Year built
- Region
- And more...

The dataset used is the **Melbourne Housing Snapshot** dataset.

This is a **Supervised Learning (Regression)** problem where:

- Input → Property features  
- Output → House price  

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess messy real-world data
- Handle missing values
- Perform feature engineering
- Encode categorical variables
- Train multiple regression models
- Compare performance using evaluation metrics
- Improve model using hyperparameter tuning
- Save the final trained model

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle

---

## 📂 Project Structure

```bash
melbourne-house-ml/
│
├── 📁 data/
│   ├── raw/
│   │   └── melb_data.csv
│   └── processed/
│       └── cleaned_data.csv
│
├── 📁 notebooks/
│   └── 01_eda_and_modeling.ipynb
│
├── 📁 src/
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── evaluate_model.py
│
├── 📁 models/
│   └── melbourne_model.pkl
│
├── 📁 app/
│   └── app.py
│
├── 📁 reports/
│   ├── figures/
│   │   ├── price_distribution.png
│   │   └── correlation_heatmap.png
│   └── model_results.txt
│
├── requirements.txt
├── .gitignore
├── README.md
└── LICENSE
```

---

## 📊 Machine Learning Workflow

### 1️⃣ Data Loading
- Import dataset
- Inspect shape, info, summary statistics

### 2️⃣ Exploratory Data Analysis (EDA)
- Target distribution analysis
- Correlation heatmap
- Outlier detection
- Feature relationships

### 3️⃣ Data Cleaning
- Drop irrelevant columns
- Handle missing values
- Remove extreme outliers

### 4️⃣ Feature Engineering
- Create new meaningful features (e.g., property age)
- Transform skewed data if needed

### 5️⃣ Encoding
- Convert categorical variables using One-Hot Encoding

### 6️⃣ Train-Test Split
- Split data into training and testing sets (80/20)

### 7️⃣ Model Training
Models used:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting (optional)

### 8️⃣ Model Evaluation
Metrics used:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### 9️⃣ Model Saving
- Final model saved using Pickle

---

## 📈 Evaluation Metrics

- **MAE** → Average prediction error  
- **RMSE** → Penalizes large errors  
- **R² Score** → Explains how well the model fits the data  

---

## 🧠 Author

Built as part of my Machine Learning journey toward becoming an ML Engineer.

---

## ⭐ If You Like This Project

Give it a star on GitHub and feel free to fork and improve it!
