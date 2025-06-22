# 🎵 Customer Churn Prediction – PlaylistPro

In this project, I took on the role of a Business Analyst at PlaylistPro, a fictional music streaming service aiming to reduce customer churn by building a predictive classification model.

---

## 📦 Project Overview

PlaylistPro’s business challenge is identifying customers who are likely to cancel their subscription (churn).  
To solve this, I built a **Supervised Classification Model** using customer subscription data and listening habits from a dataset of 40,000 users.

This project was developed and executed in a **Kaggle Notebook** using Python, with submission evaluated via F1 score on Kaggle’s platform.

🔗 **View Full Notebook:**  
👉 [Kaggle Project Link](https://www.kaggle.com/code/laelialuong/notebook47f6305f3c)

---

## 🧠 Objectives

PlaylistPro asked me to complete the following tasks:

1. **Model Development:**  
   Build a classification model using `train.csv` to predict customer churn.
2. **Submission & Evaluation:**  
   Predict churn on `test.csv` and submit results to Kaggle to receive an official **F1 score**.
3. **Business Insights Presentation:**  
   Answer these 3 key questions in the notebook:
   - Can we reliably predict which customers will churn?
   - How does the model work?
   - What % of customers in `test.csv` do we expect to retain?

---

## ⚙️ How I Built the Model

- **Tools Used:** Python, Pandas, Scikit-learn, XGBoost, Kaggle Notebook
- **Techniques Applied:**
  - Data cleaning and preprocessing
  - Feature selection and engineering
  - Model training using Logistic Regression and Tree-based models
  - Hyperparameter tuning
  - Evaluation with precision, recall, and F1 score

---

## 📈 Key Outcomes

- Trained multiple models and selected the one with the best F1 score on validation data
- Successfully submitted predictions to Kaggle and received an official score
- Interpreted model outputs and churn probabilities to inform business strategy

---

## 🗂 Project Structure

- `train.csv` – Labeled dataset for training
- `test.csv` – Unlabeled dataset for prediction
- `submission.csv` – Final Kaggle submission
- `notebook.ipynb` – Full code and answers to executive team questions *(on Kaggle)*

---

## 📊 Executive Summary & Business Recommendations

With our model, we cannot reliably predict which customers will churn.  
However, we **can reasonably predict which users will not churn** — with **~85% accuracy**.  
Our current framework lays a solid foundation to explore further modeling and new algorithms to improve predictive power.

We engineered new features aimed at capturing overall listening activity to reduce dimensionality.  
A custom pipeline was built to preprocess the dataset and train the model on previously observed churn outcomes.

**Retention Expectation:**  
Our model suggests PlaylistPro can retain **approximately 74%** of customers in the test data.  
However, this assumption is based on the belief that **price is the primary factor driving churn** — further research into churn motivation is essential for accurate intervention.

---

> Developed by Mai Linh Luong as part of DSC 783 – Advanced Business Analytics Capstone  
> 💡 For questions or collaborations, visit [linkedin.com/in/mai-linh-luong-594765220](https://www.linkedin.com/in/mai-linh-luong-594765220/)
