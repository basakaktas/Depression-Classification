# 📊 Student Depression Analysis (ML Project)

Machine learning project analyzing how academic, lifestyle, and psychological factors affect student depression.

---

## 🚀 Overview

This project uses classification algorithms to predict whether a student is depressed and to identify the most important contributing factors.

- 🎯 Goal: Binary classification (Depressed / Not Depressed)
- 📦 Dataset: ~27,900 student records
- 🤖 Models: Logistic Regression, Naïve Bayes, Random Forest

---

## 📁 Dataset

- Source: Kaggle – Student Depression Dataset  
- Target: `Depression` (0 = No, 1 = Yes)

### Features:
- Academic → CGPA, Academic Pressure, Study Satisfaction  
- Lifestyle → Sleep, Diet, Work/Study Hours  
- Psychological → Suicidal Thoughts, Financial Stress  
- Demographic → Age, Gender, City  

---

## ⚙️ Workflow

```text
Data → Preprocessing → Encoding → Train/Test Split → Model Training → Evaluation
