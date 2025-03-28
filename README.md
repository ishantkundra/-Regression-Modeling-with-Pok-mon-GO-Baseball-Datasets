# 📘 Regression Modeling with Pokémon GO & Baseball Datasets

This project implements **Linear Regression** and **Logistic Regression** from scratch using real-world datasets — one from **Pokémon GO** and one from **Major League Baseball**. It was completed as part of **CSCE 633: Machine Learning** at **Texas A&M University**.

---

## 📂 Repository Structure

<pre>
📦 regression-modeling-pokemon-baseball
│
├── code/
│   └── CSCE_633_HW1_Starter_Notebook.ipynb   # Full implementation and results
│
├── dataset/
│   ├── hw1_q1_data.csv   # Pokémon GO dataset
│   └── hw1_q2_data.csv   # Hitters (baseball) dataset
│
└── README.md
</pre>

---

## 🧠 Project Overview

| Part | Dataset         | Task                          | Model               |
|------|------------------|-------------------------------|----------------------|
| A    | Pokémon GO       | Predicting Combat Points (CP) | Linear Regression    |
| B    | Hitters (Baseball) | Classifying League (A/N)     | Logistic Regression  |

---

## 🧪 Part A: Linear Regression (Pokémon GO)

- 🎯 Goal: Predict a Pokémon's **Combat Points (CP)** using features like:
  - Stamina, Attack, Defense, Capture Rate, Flee Rate, Spawn Chance
- ✅ Implemented **Ordinary Least Squares (OLS)** from scratch
- 📈 Correlation analysis and interaction features
- 🔁 Evaluated using **5-Fold Cross-Validation**

---

## ⚾ Part B: Logistic Regression (Hitters Dataset)

- 🎯 Goal: Predict a player's league (A/N) based on performance stats
- 🧹 Preprocessed missing and categorical data
- 🧠 Implemented **Logistic Regression** from scratch
- 📉 Metrics: **ROC Curve**, **AUC**, **F1 Score**
- 🔁 **Stratified 5-Fold Cross-Validation**
- 📏 Confidence intervals for AUC and F1

---

## 📈 Key Concepts

- Linear Regression via Gradient Descent  
- Binary Logistic Regression  
- Cross-Validation & Performance Metrics  
- ROC, AUC, F1 Score, and Confidence Intervals  
- Feature Engineering & Interaction Terms

---

## ⚙️ Libraries Used

- Python 3.10  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn (for evaluation utilities only)

---

## 👨‍💻 Author

**Ishant Kundra**  
M.S. Computer Science, Texas A&M University  
📬 [ishantkundra9@gmail.com]
