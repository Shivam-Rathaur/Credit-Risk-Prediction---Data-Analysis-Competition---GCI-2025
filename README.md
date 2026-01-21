# Credit Risk Prediction — Data Analysis Competition (GCI 2025)

## Overview
This repository contains my solution to a **Credit Risk Prediction** problem undertaken as part of a **Data Analysis Competition (GCI 2025)**.  
The objective is to build a **binary classification machine learning pipeline** to predict **loan default risk** using a large, real-world **tabular financial dataset**.

The project focuses on handling practical data challenges such as missing values, categorical variables, and noisy financial features, while following a disciplined **train–validation–test workflow**.

---

## Problem Statement
Given historical loan applicant data, predict whether a borrower is likely to **default on a loan**.  
This is framed as a **binary classification problem**, with performance evaluated using a competition-specific leaderboard metric.

---

## Approach & Methodology

### 1. Data Preprocessing
- Handled **missing values** using appropriate imputation strategies  
- Encoded **categorical variables** for tree-based models  
- Managed **noisy and skewed financial features**  
- Ensured no data leakage during preprocessing  

### 2. Feature Engineering
- Created meaningful derived features to capture financial behavior  
- Removed low-importance or redundant features  
- Optimized features for gradient boosting models  

### 3. Modeling
- Trained **gradient boosting models** (LightGBM)
- Performed **iterative hyperparameter tuning**
- Used **model ensembling** to improve generalization
- Followed a strict **train–validation–test split**

### 4. Evaluation
- Evaluated models using the competition leaderboard metric  
- Achieved a **final leaderboard score of 0.7527**, indicating strong predictive performance in a competitive setting

---

## Tech Stack
- **Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - LightGBM  
- **Techniques:**  
  - Binary Classification  
  - Feature Engineering  
  - Gradient Boosting  
  - Model Ensembling  
  - Hyperparameter Tuning  

---
## 👤 Author

**Shivam Rathaur**  
B.Tech Undergraduate | Materials Science & Metallurgical Engineering  
Interests: Machine Learning, Data Science, Computational Modeling  

🔗 GitHub: https://github.com/Shivam-Rathaur

