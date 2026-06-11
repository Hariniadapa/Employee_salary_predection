# 💼 Employee Salary Classification using Machine Learning

This project predicts whether an individual earns **≤50K or >50K per year** based on demographic and work-related attributes from the **Adult Income Dataset**. It applies multiple machine learning models, compares their performance, and deploys the best model using a Streamlit web application.

---

## 🚀 Project Overview

- Cleaned and preprocessed the Adult Income dataset
- Handled missing values and removed irrelevant categories
- Applied feature encoding and scaling (Label Encoding + MinMaxScaler)
- Trained and evaluated multiple machine learning models:
  - K-Nearest Neighbors (KNN)
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Multi-Layer Perceptron (MLP Classifier)
  - Random Forest Classifier
  - Gradient Boosting Classifier (Best Model)
- Compared models using accuracy and classification metrics
- Saved trained model and scaler using `joblib`
- Built an interactive web app using Streamlit
- Enabled batch prediction using CSV upload
- Deployed locally using Pyngrok

---

## 🏆 Best Performing Model

- **Model:** Gradient Boosting Classifier  
- **Accuracy:** ~86%  
- Selected based on overall performance across evaluation metrics

---

## 🧠 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Streamlit
- Joblib
- Pyngrok

---

## 📊 Features

- 🔮 Predict salary class from user input
- 📁 Upload CSV for batch predictions
- 📊 Compare multiple ML models
- 🧹 Clean preprocessing pipeline
- 💾 Saved model for reuse (joblib)
- 🌐 Interactive Streamlit UI

---

## 📁 Project Structure
