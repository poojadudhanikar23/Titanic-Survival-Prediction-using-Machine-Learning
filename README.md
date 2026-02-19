# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques.
The goal is to analyze passenger data such as age, gender, ticket class, and fare to build a classification model that can estimate survival probability.

--------------------------------

## 📂 Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (Pclass)
* Name, Gender, Age
* Number of Siblings/Spouses (SibSp)
* Number of Parents/Children (Parch)
* Ticket Fare
* Embarked Location
* Survival Status (Target Variable)
  
--------------------------
## ⚙️ Project Workflow

### 1️⃣ Data Loading

* Imported dataset using **Pandas**
* Explored structure using `.head()`, `.info()`, `.describe()`

### 2️⃣ Data Preprocessing

* Handled missing values using **median (numerical)** and **mode (categorical)**
* Dropped irrelevant columns (e.g., PassengerId, Name, Ticket)
* Converted categorical features into numerical format using encoding

### 3️⃣ Exploratory Data Analysis (EDA)

* Analyzed survival patterns based on:

  * Gender
  * Passenger Class
  * Age Distribution
* Identified important factors influencing survival.

### 4️⃣ Feature Engineering

* Selected meaningful features for model training.
* Scaled/cleaned data for better performance.

### 5️⃣ Model Building

* Applied **Logistic Regression** for classification.
* Split data into **training and testing sets**.

### 6️⃣ Model Evaluation

* Evaluated performance using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

## 📊 Outcome

The model successfully predicts passenger survival based on historical data and demonstrates how Machine Learning can be used for real-world classification problems.

## ✅ Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Perform Hyperparameter Tuning
* Deploy model using Flask/Streamlit

## 🙌 Acknowledgement

This project is built for learning purposes to understand the complete Machine Learning workflow from data preprocessing to model evaluation.



