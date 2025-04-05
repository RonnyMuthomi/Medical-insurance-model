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

## 📈 Exploratory Data Analysis (EDA)

- Distribution plots for numeric features
- Boxplots for detecting outliers
- Correlation heatmap
- Insights on how smoking, BMI, and number of children affect charges

---

## 🏗️ Model Building

- One-Hot Encoding for categorical variables (`sex`, `region`, `smoker`)
- Feature scaling (if needed)
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

## 📂 Folder Structure


