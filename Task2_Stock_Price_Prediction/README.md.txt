# Task 2 – Predict Future Stock Prices

## ✅ Objective
Build a model that predicts the next day's stock closing price using historical data such as Open, High, Low, and Volume.

---

## 📊 Dataset
- **Source:** Yahoo Finance (via `yfinance` library)
- **Stock Symbol:** AAPL (Apple Inc.)
- **Period:** Jan 2020 – Dec 2023
- **Columns Used:**
  - **Features:** Open, High, Low, Volume
  - **Target:** Close

---

## 🧪 Tools & Libraries
- Python, pandas
- yfinance
- scikit-learn
- matplotlib, seaborn

---

## 🤖 Model
- **Type:** Random Forest Regressor
- **Train/Test Split:** 80/20
- **Hyperparameters:** n_estimators=100

---

## 📈 Evaluation
| Metric | Value |
|--------|-------|
| Mean Absolute Error (MAE) | ~2.1 |
| R² Score                  | ~0.96 |

---

## 📌 Key Results
- The model shows strong prediction accuracy for daily stock prices.
- Data visualization revealed trends and outliers before training.
- Boxplots and scatterplots provided useful insights into feature distributions.
- Evaluation confirms the model predicts well on unseen data.

---

## 📁 Files Included
- `Task2_Stock_Price_Prediction.ipynb` – Full notebook with code, output, and analysis
- `README.md` – Summary report of the task

---
