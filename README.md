# 🚢 Titanic Data Analysis (Task-02)

## 📌 Overview
This project is part of the **Prodigy InfoTech Data Science Internship (Task-02)**.  
The goal is to perform **Data Cleaning & Exploratory Data Analysis (EDA)** on the Titanic dataset.

---

## 🔎 Key Steps
- Handle missing values (`Age`, `Embarked`, `Cabin`)
- Feature engineering (`FamilySize = SibSp + Parch`)
- Exploratory Data Analysis with **Seaborn & Matplotlib**
  - Survival distribution
  - Survival by Gender
  - Survival by Passenger Class
  - Age distribution of survivors vs non-survivors
  - Correlation heatmap

---

## 📂 Dataset
- `train.csv` → used for EDA  
- `test.csv` → test data (not used in this task)  
- `gender_submission.csv` → sample submission (not used in this task)  

Dataset Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

---

## ⚙️ Requirements
```bash
pip install pandas matplotlib seaborn
