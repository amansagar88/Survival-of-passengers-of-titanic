# 🚢 Titanic - Machine Learning from Disaster 🧠

Welcome to this comprehensive notebook that tackles the classic **Titanic survival prediction** problem from [Kaggle's Titanic competition](https://www.kaggle.com/c/titanic). This project covers the end-to-end data science workflow: from data exploration to model evaluation.
[View Notebook Here](https://github.com/amansagar88/Survival-of-passengers-of-titanic/blob/main/titanic-competition-eda-and-prediction.ipynb)

---

## 📌 Project Overview

The goal of this notebook is to **predict whether a passenger survived or not**, based on features like age, gender, class, and more.

We apply:
- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Preprocessing
- 🔍 Feature Engineering
- 🤖 Multiple ML Models
- 📈 Evaluation & Interpretation

---

## 📁 Files Used

- `train.csv` - Contains labeled data to train the model
- `test.csv` - Unlabeled data used for final prediction

---

## 🔍 EDA Highlights

- Visualized survival rates by **gender**, **class**, **family size**, and more
- Explored **missing values** and handled them intelligently
- Gained insights into how different features impact survival

---

## 🛠️ Feature Engineering

✔️ Created new features like:
- FamilySize  
- Title extraction from names  
- Age group bins  

✔️ Handled missing data using strategies like:
- Median imputation
- Mode filling for categorical columns

---

## 🤖 Models Implemented

- Logistic Regression
- K-Nearest Neighbors
- Decision Trees
- Random Forest
- Support Vector Machine
- Gradient Boosting
- XGBoost

Each model was trained and evaluated using standard metrics. The best-performing model was selected based on accuracy and interpretability.

---

## 🧪 Evaluation Metrics

I used:
- ✅ Accuracy
- 📊 Confusion Matrix
- 📝 Classification Report

**Cross-validation** and **grid search** were applied for hyperparameter tuning (where applicable).

---

## 📌 Results Summary

The notebook concludes with:
- A **model comparison**
- Insights on which features were most influential
- Final prediction output for submission

---

## 🚀 How to Use

1. Clone this repo or download the notebook
2. Upload it to Kaggle or run locally with the Titanic dataset
3. Walk through each section to understand the full ML pipeline

---

## ✨ Author

**Aman Sagar**  
📫 [View kaggle Profile](https://www.kaggle.com/sagaraman8)  
🔍 Data Scientist | ML Enthusiast

---

## 📎 Acknowledgments

Thanks to:
- Kaggle community for discussions
- Open-source libraries: `pandas`, `sklearn`, `xgboost`, `matplotlib`, and `seaborn`

---

## 🧠 Takeaway

This notebook not only builds a strong Titanic survival predictor, but also demonstrates how to think like a data scientist — from hypothesis to validation. A must-practice problem for ML beginners!


