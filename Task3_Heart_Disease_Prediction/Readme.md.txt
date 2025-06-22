# Task 3 – Heart Disease Prediction

## ✅ Objective
Build a classification model that predicts whether a person is at risk of heart disease using health-related features like age, cholesterol, blood pressure, and more.

---

## 📊 Dataset
- **Source:** UCI Heart Disease Dataset (via Kaggle)
- **Filename:** `heart.csv`
- **Rows:** 918
- **Target Column:** `HeartDisease` (0 = No, 1 = Yes)

---

## 🧪 Features Used
| Feature            | Description                           |
|--------------------|---------------------------------------|
| Age                | Patient age in years                  |
| Sex                | Male or Female                        |
| ChestPainType      | Type of chest pain                    |
| RestingBP          | Resting blood pressure                |
| Cholesterol        | Serum cholesterol in mg/dl            |
| FastingBS          | Fasting blood sugar (0 or 1)          |
| RestingECG         | ECG results at rest                   |
| MaxHR              | Maximum heart rate achieved           |
| ExerciseAngina     | Angina during exercise (Yes/No)       |
| Oldpeak            | ST depression induced by exercise     |
| ST_Slope           | Slope of ST segment                   |

---

## 🛠️ Tools & Libraries
- Python
- pandas, matplotlib, seaborn
- scikit-learn
- StandardScaler (for scaling features)

---

## 🔧 Preprocessing Steps
- Checked for and confirmed no missing values
- One-hot encoded categorical features: `Sex`, `ChestPainType`, `RestingECG`, `ExerciseAngina`, `ST_Slope`
- Scaled features for Logistic Regression using `StandardScaler`
- Split data into 80% training and 20% testing sets

---

## 🤖 Models Applied
| Model                | Description                           |
|----------------------|---------------------------------------|
| Logistic Regression  | Scaled data, max_iter=1000            |
| Decision Tree        | Non-scaled, depth-limited (max_depth=4) |

---

## 📈 Evaluation Metrics
| Metric              | Logistic Regression | Decision Tree |
|---------------------|---------------------|----------------|
| Accuracy            | ~0.85               | ~0.82          |
| AUC Score           | ~0.91               | ~0.88          |
| Confusion Matrix    | ✅ Yes               | ✅ Yes          |
| ROC Curve           | ✅ Plotted           | ✅ Plotted      |

---

## 🧠 Feature Importance
- **Logistic Regression:** Most influential features included Age, Cholesterol, and ExerciseAngina_Yes.
- **Decision Tree:** Prioritized Age, Oldpeak, ChestPainType, and ST_Slope.

---

## 📁 Files Included
- `Task3_Heart_Disease_Prediction.ipynb` – Full notebook with all steps and results
- `heart.csv` – Dataset file used
- `README.md` – Task overview and results summary

---

## ✅ Final Insight
The models were able to predict heart disease presence with high accuracy and reliability. Both AUC and confusion matrix suggest the models are trustworthy for binary classification. Logistic Regression provides explainability, while Decision Tree handles non-linear splits well.

