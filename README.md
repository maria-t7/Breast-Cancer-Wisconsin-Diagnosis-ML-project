# Breast Cancer Wisconsin Diagnosis — ML Classification Project

A machine learning project that classifies breast cancer tumors as **malignant** or **benign** using the [Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

---

## Overview

Breast cancer is one of the most common cancers worldwide. Early and accurate diagnosis is critical for effective treatment. This project applies and compares multiple supervised learning algorithms to predict whether a tumor is malignant (M) or benign (B) based on features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

---

## Dataset

- **Source:** UCI Machine Learning Repository / Kaggle
- **Samples:** 569
- **Features:** 30 numeric features (mean, standard error, and worst values of radius, texture, perimeter, area, smoothness, etc.)
- **Target:** Diagnosis — Malignant (M) or Benign (B)

---

## What's Inside

```
📓 breast_cancer_diagnosis.ipynb   # Main notebook with EDA, modeling, and results
```

---

## Project Workflow

1. **Exploratory Data Analysis (EDA)**
   - Checked for null values and data types
   - Visualized feature distributions and class balance
   - Explored correlations between features

2. **Preprocessing**
   - Encoded target labels (M → 1, B → 0)
   - Train/test split

3. **Modeling**
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Decision Tree / Random Forest

4. **Evaluation**
   - Compared accuracy scores across all models
   - Identified best-performing classifier

---

## Results

| Model | Accuracy |
|---|---|
| Logistic Regression | ~95–97% |
| SVM | ~96–98% |
| Decision Tree / Random Forest | ~94–97% |

> Exact values are in the notebook.

---

## Tech Stack

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## How to Run

```bash
git clone https://github.com/maria-t7/Breast-Cancer-Wisconsin-Diagnosis-ML-project-.git
cd Breast-Cancer-Wisconsin-Diagnosis-ML-project-
jupyter notebook
```

---

## Authors

**Maria Rahman Tasnim** — [GitHub](https://github.com/maria-t7)

**Binita Agarwal** [Github](https://github.com/Binita20)

**Sanjida Akhter** [Github](https://github.com/sanjida-akhtar)
