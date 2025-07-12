# 🚢 Titanic Survival Prediction with Interactive Visualizations

This project predicts passenger survival on the Titanic using machine learning — enriched with interactive visualizations built using **Plotly** and a user-friendly **Streamlit web app**.

---

## 🧠 Problem Statement

Given passenger features like age, sex, class, fare, and more — can we predict who survived the Titanic disaster?

This is a **binary classification** problem where:
- `1` = Survived
- `0` = Did not survive

---

## 📂 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- Files: `train.csv`, `test.csv`

**Important Columns:**
- `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`
- `Survived` (target)

---

## 🔧 Tech Stack

- Python 3.x
- **Pandas**, **NumPy** — Data handling
- **Plotly**, **Seaborn**, **Matplotlib** — Visualizations
- **Scikit-learn** — ML models
- **Streamlit** — Web app
- **Jupyter Notebook** — EDA & experimentation

---

## 📊 Key Features

### ✅ Exploratory Data Analysis (EDA)

- Missing data handling
- Title extraction from names
- Age & Fare binning
- Correlation heatmaps

### 📈 Interactive Visualizations with Plotly

- Survival by gender, class, embarkation
- Age vs. Fare scatter with hover
- Dynamic histograms and bar charts


## 🎯 Model Training

Models used:
- Logistic Regression
- Random Forest
- SVM
- Gradient Boosting

Best model achieved:
- **~62% Accuracy**
- Strong predictors: `Sex`, `Pclass`, `Fare`, `Age`



