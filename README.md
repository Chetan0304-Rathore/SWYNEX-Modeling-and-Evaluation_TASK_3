# Titanic Survival Prediction - Modeling and Evaluation

This repository contains the code and documentation for **Task 3: Modeling and Evaluation**[cite: 4] as part of my data science internship at **SWYNEX Technologies**.

## 📋 Project Overview
The objective of this task is to build a baseline predictive machine learning model to classify whether a passenger survived the Titanic disaster based on socio-economic and demographic features.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Libraries:** 
  * `pandas`, `numpy` for data manipulation
  * `scikit-learn` for preprocessing, model training, and performance evaluation
  * `seaborn`, `matplotlib` for data visualization

## 🔍 Workflow Steps
1. **Data Loading & Cleaning:** Loaded the built-in Seaborn Titanic dataset, dropped redundant or sparse columns, filled missing values in `age`, and cleaned rows with missing embarkation data.
2. **Encoding:** Converted categorical attributes (`sex`, `embarked`) into numerical formats using `LabelEncoder`.
3. **Train-Test Split:** Split the dataset into training and testing sets (67% train, 33% test).
4. **Feature Scaling:** Standardized the feature distributions using `StandardScaler`.
5. **Model Training:** Trained a **Logistic Regression** baseline classification model.
6. **Model Evaluation:** Evaluated performance using metrics such as:
   * **Accuracy Score:** ~81.6%
   * **F1-Score:** ~0.75
   * **Confusion Matrix & Classification Report** (Precision & Recall breakdown)

## 📈 Evaluation Results Summary
* The baseline Logistic Regression model achieves a strong overall accuracy of **82%**, demonstrating that features like passenger class, sex, and fare are strong indicators of survival probability.

## 📂 Repository Structure
* `task3_modeling.ipynb`: Jupyter Notebook containing the full pipeline code.

---
*Developed by Chetan Rathore*

