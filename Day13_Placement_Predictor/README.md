# 🎯 Day 13 — Mini Project: Placement Predictor

This project is part of my **100 Days of Machine Learning Challenge** inspired by the [CampusX 100 Days of ML Playlist](https://www.youtube.com/playlist?list=PLKnIA16_Rmvb1RYR-iTA_hzckhdON1A6R).

---

## 🧠 Project Objective

The goal of this mini project is to **predict whether a student will get placed** based on their **CGPA** and **IQ score**.  
It’s a simple **binary classification** problem built using **Logistic Regression**.

---

## 📂 Files in this Folder

| File | Description |
|------|--------------|
| `Placement__Predictor.ipynb` | Jupyter Notebook containing the full code |
| `placement.csv` | Dataset used in the project *(from CampusX resources)* |
| `README.md` | Project description (this file) |

---

## ⚙️ Workflow Summary

### 1️⃣ Importing Libraries
Used essential libraries such as:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### 2️⃣ Data Preprocessing
- Loaded dataset `placement.csv`
- Removed unnecessary columns
- Checked for null values, data types, and statistics

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualized the relationship between:
  - CGPA vs Placement
  - IQ vs Placement  
- Observed that higher CGPA and IQ improve placement chances

### 4️⃣ Model Building
- **Algorithm:** Logistic Regression  
- **Features:** `CGPA`, `IQ`  
- **Target Variable:** `Placement`  
- Performed Train-Test split and trained the model

### 5️⃣ Model Evaluation
- Evaluated performance using accuracy score  
- Achieved around **90–92% accuracy**

### 6️⃣ Prediction Example
```python
model.predict([[8.0, 120]])
