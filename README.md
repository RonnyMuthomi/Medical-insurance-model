# 🏥 Medical Cost Personal Dataset – Insurance Forecast using Linear Regression

## 📌 Overview

This project explores the **Medical Cost Personal Dataset** to predict insurance charges using **Linear Regression**. The dataset includes information such as age, BMI, smoking status, region, and other factors that influence medical costs. The goal is to use this data to build a regression model that can **forecast individual insurance costs** accurately.

---

## 📊 Dataset Description

**Source:** Publicly available dataset inspired by *"Machine Learning with R"* by Brett Lantz.

### 🔢 Columns:
| Column     | Description |
|------------|-------------|
| `age`      | Age of primary beneficiary |
| `sex`      | Gender of the insurance policyholder (male/female) |
| `bmi`      | Body Mass Index (kg/m²) — ideally between 18.5 to 24.9 |
| `children` | Number of dependents covered by health insurance |
| `smoker`   | Smoking status (yes/no) |
| `region`   | Residential area in the US (northeast, southeast, southwest, northwest) |
| `charges`  | Medical insurance charges (target variable) |

---

## 🎯 Objective

- Explore the dataset and understand the relationships between features.
- Perform data preprocessing and visualizations.
- Build a **Linear Regression** model to predict `charges` (insurance cost).
- Evaluate the model using appropriate metrics like **R²**, **MAE**, and **RMSE**.
- Communicate insights using visuals and a clean presentation.

---

## 🧰 Tools & Libraries

- **Language:** Python
- **Data Analysis:** pandas, NumPy
- **Visualization:** matplotlib, seaborn
- **Modeling:** scikit-learn (LinearRegression, train_test_split, metrics)
- **Notebook Interface:** Jupyter Notebook / Google Colab
- **Version Control:** Git, GitHub

---

## 📊 Methodology

### 1. Data Preprocessing
- Handled missing values
- Converted numerical features appropriately
- Removed duplicates
- Checked for outliers

---

## 📈 Exploratory Data Analysis (EDA)

- Relationship plots for bmi and smoker features

  <img src="https://github.com/user-attachments/assets/871fea5d-02e1-4ef1-ad34-aa4a50f6e6fd" height="250" />


  
- Barplot to show impact of smoking on medical insurance

  <img src="https://github.com/user-attachments/assets/569abf4d-b9f0-4839-8d3d-112af97e50ed" height="250" />



- Correlation heatmap

<img src="https://github.com/user-attachments/assets/63f4aed2-1f78-450e-9c5e-574579abc694" height="250" />
  
- Insights on how  number of children affect charges

  <img src="https://github.com/user-attachments/assets/931d1342-281f-429c-88a0-8b6ad1e4c13fr" height="250" />
  

---

##     Findings

✅ Family size does not have a consistent impact on medical charges.
✅ Families with 2 and 3 children have the highest medical charges.
✅ Southeast region has the highest medical charges.
✅ Northwest & Southwest regions have almost similar charges, likely due to similar demographic or insurance factors.

## 🏗️ Model Building

- One-Hot Encoding for categorical variables (`sex`, `region`, `smoker`)
- Feature scaling (used StandardScaler)
- Train-Test Split (80/20)
- Linear Regression Model using scikit-learn
- Model Evaluation:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## ✅ Results & Insights

- **Smoking status** is the most significant factor in predicting medical charges.
- **BMI** has a non-linear but noticeable influence, especially among smokers.
- **Age** and **number of children** contribute, but less significantly.

---




