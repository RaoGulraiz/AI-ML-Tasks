# AI-ML-Tasks
# 💼 AI/ML Engineering Internship Tasks

This repository contains the three tasks completed as part of my AI/ML Engineering Internship. Each task demonstrates my understanding of core machine learning concepts, data handling, and model evaluation. Every notebook includes code, visualizations, and explanations for practical learning and hands-on practice.

---

## 📁 Task 1: Exploring and Visualizing a Simple Dataset

### 🎯 Objective:
The goal of this task was to gain hands-on experience in **loading, inspecting, and visualizing datasets** using Python libraries. The Iris dataset was used — a classic dataset in machine learning containing measurements of iris flowers and their species.

### 📌 What I Did:
- Loaded the Iris dataset using the seaborn library, which provides it in clean format.
- Used **pandas** to print the shape of the dataset, view column names, and inspect the first few rows with `.head()`.
- Explored the dataset using `.info()` and `.describe()` to understand data types, null values, and summary statistics (mean, std, etc.).
- Created various plots using **matplotlib** and **seaborn**:
  - A **scatter plot** to show relationships between `sepal length` and `sepal width`.
  - **Histograms** to show the distribution of all numerical features.
  - **Box plots** to identify outliers and compare feature values across species.

### ✅ Skills Practiced:
- Reading and understanding datasets using pandas.
- Visualizing data with histograms, scatter plots, and box plots.
- Identifying trends and distributions visually.
- Using `.info()` and `.describe()` for fast dataset summaries.

---

## 📁 Task 2: Stock Price Prediction (Regression)

### 🎯 Objective:
This task focused on building a **regression model** to predict Apple Inc.'s stock price using historical financial data from Yahoo Finance. The goal was to learn how to handle time-series data and apply regression models to predict continuous values.

### 📌 What I Did:
- Used `yfinance` to load Apple stock data from 2020 to 2023.
- Displayed and explored basic price features like **Open, Close, High, Low**.
- Visualized the **Close price** trend over time using a line plot.
- Extracted **feature columns** (like Open, High, Low, Volume) to use as input for prediction.
- Built a **Random Forest Regressor model**, which is an ensemble tree-based model ideal for non-linear problems.
- Split the dataset into training and testing sets.
- Trained the model and predicted the closing price.
- Evaluated the model using:
  - **R² Score**: How well the model explains the variance in the data.
  - **MAE (Mean Absolute Error)**: How far off predictions are from actual prices on average.

### ✅ Skills Practiced:
- Loading real-world financial data.
- Time-series feature selection.
- Training Random Forest models for regression.
- Evaluating performance using R² and MAE.
- Understanding prediction challenges in financial datasets.

---

## 📁 Task 3: Heart Disease Prediction (Classification)

### 🎯 Objective:
The objective was to create a **binary classification model** that predicts whether a patient has heart disease, based on clinical features. The task mimics a real-world medical prediction problem.

### 📌 What I Did:
- Loaded the Heart Disease dataset from Kaggle.
- Verified that there were **no missing values** in the dataset.
- Performed **encoding** of categorical features (like Sex, ChestPainType, etc.) using one-hot encoding, so the model can process them numerically.
- Conducted **EDA (Exploratory Data Analysis)**:
  - Correlation heatmap to see which features are most related to Heart Disease.
  - Bar plots and distribution plots for visual trend analysis.
- Split the dataset into **training and testing sets**.
- Trained a **Logistic Regression model**, which is a baseline classifier good for binary outcomes.
- Evaluated the model using:
  - **Accuracy score**: Percentage of correct predictions.
  - **Confusion Matrix**: Number of True Positives, False Negatives, etc.
  - **ROC Curve**: Visual representation of model's classification performance at different thresholds.
- Identified the **most important features** that influence heart disease prediction.

### ✅ Skills Practiced:
- Binary classification using Logistic Regression.
- Medical data analysis.
- Feature encoding for machine learning models.
- Evaluation using Accuracy, Confusion Matrix, and ROC-AUC.
- Interpreting feature importance in real-life decisions.

---

## ✅ How to View Notebooks

Each notebook is included in `.ipynb` format. You can:
- View directly on GitHub (Jupyter viewer)
- Download and open in Jupyter Notebook or JupyterLab

---

## 🔧 Tools Used

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  
- yfinance

---

## 🧠 Key Learnings

Through these three tasks, I have:
- Practiced both **classification and regression models**
- Learned to perform **EDA, encoding, and model evaluation**
- Improved my ability to **analyze real-world data**
- Built confidence in using **pandas, seaborn, and scikit-learn** for ML tasks

---

> 👏 Thank you for reviewing my internship work! I’m excited to grow further in machine learning and AI.

