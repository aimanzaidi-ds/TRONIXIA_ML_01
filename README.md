# 🚢 Titanic Survival Prediction (Machine Learning Project)

## 📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques.  
The dataset is taken from the famous Kaggle competition *“Titanic – Machine Learning from Disaster.”*

The goal is to build a classification model that can accurately predict survival based on passenger features.

---

## 📊 Dataset Information
The dataset contains information about passengers such as:

- PassengerId  
- Pclass (Ticket Class)  
- Name  
- Sex  
- Age  
- SibSp (No. of siblings/spouses aboard)  
- Parch (No. of parents/children aboard)  
- Ticket  
- Fare  
- Cabin  
- Embarked  

Training data contains survival labels, while test data is used for prediction.

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:

- Handling Missing Values  
- Filling Age with Mean  
- Filling Embarked with Mode  
- Dropping Cabin column (too many missing values)  
- Encoding Categorical Features (Sex, Embarked)

---

## 🤖 Machine Learning Model
Model Used:

✅ Random Forest Classifier  

Steps:

- Feature Selection  
- Train-Test Split  
- Model Training  
- Prediction  
- Accuracy Evaluation  

---

## 📈 Model Performance
Accuracy Achieved:

*~81% Accuracy*

---

## 📂 Project Files
- Titanic.ipynb → Full ML workflow  
- train.csv → Training dataset  
- test.csv → Testing dataset  
- submission.csv → Final predictions  

---

## 🚀 How to Run
1. Open Jupyter Notebook / VS Code  
2. Install required libraries:

```bash
pip install pandas numpy scikit-learn
