# 🧠 Model Comparison with and without PCA

## 📋 Project Overview
This project explores how different **Machine Learning models** perform **with and without Principal Component Analysis (PCA)**.  
It helps analyze how dimensionality reduction impacts model **accuracy**, **efficiency**, and **generalization**.

By using PCA, the dataset’s features are compressed while retaining most of their variance — reducing training complexity while maintaining model accuracy.

---

## 🎯 Objectives
- Train and compare multiple ML classifiers on the same dataset  
- Apply **PCA** to reduce dimensionality and analyze its impact  
- Evaluate models based on **Train Accuracy**, **Test Accuracy**, and **Recall**  
- Visualize performance differences between PCA and non-PCA models  
- Identify which algorithms generalize best after feature reduction  

---

## 🧩 Models Used

| Category | Models |
|:----------|:--------|
| **Without PCA** | K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree, Linear SVM, Kernelized SVM, Random Forest |
| **With PCA** | KNN (PCA), Logistic Regression (PCA), Linear SVC (PCA), Kernelized SVC (PCA), Random Forest (PCA), Decision Tree (PCA) |

> Each model was trained and tested separately for a fair comparison.

---

## 🧪 Results Summary

| Model | Train Accuracy | Test Accuracy |
|:------|:---------------:|:--------------:|
| KNN | 0.636 | 0.604 |
| Logistic Regression | 0.941 | 0.725 |
| Decision Tree | 0.769 | 0.604 |
| Linear SVM | 0.897 | 0.747 |
| Kernelized SVM | 0.858 | 0.692 |
| Random Forest | 0.897 | 0.758 |
| **KNN (PCA)** | 0.644 | 0.615 |
| **Logistic Regression (PCA)** | 0.911 | 0.725 |
| **Linear SVC (PCA)** | 0.825 | 0.703 |
| **Kernelized SVC (PCA)** | 0.850 | 0.703 |
| **Random Forest (PCA)** | 0.911 | 0.648 |
| **Decision Tree (PCA)** | 0.780 | 0.571 |

> 🔍 **Insight:**  
> PCA helps certain models (like Logistic Regression and SVM) achieve better **generalization** by reducing noise and avoiding overfitting.

---
