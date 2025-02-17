# 🛍️ Otto Group Product Classification

## 📌 Overview
This repository contains a classification model built to predict **product categories** for the **Otto Group Product Dataset**. We leverage various **machine learning algorithms** and a **deep learning model** to achieve high accuracy in classifying products into **nine distinct classes**.

📍 **Original Notebook:** [Kaggle Notebook](https://www.kaggle.com/code/senasudemir/otto-group-product-classification#Conclusion)

---

## 📊 Dataset Description
The dataset consists of numerical features representing various product attributes and a categorical **target variable**.

- **🔢 Features:** `feat_1` to `feat_93` (Numerical features)
- **🏷️ Target Variable:** `target` (One of `Class_1` to `Class_9`)
- **🆔 Identifier:** `id` (Unique ID for each observation)

---

## 🎯 Goal
The objective is to train classification models that **accurately predict** the product class based on the given feature set.

---

## 🚀 Models & Accuracy Scores

| Model | Accuracy Score |
|--------|--------------|
| **KNeighbors Classifier** | 🎯 **0.999677** |
| **Gradient Boosting Classifier** | 🎯 **0.999677** |
| **Decision Tree Classifier** | 🎯 **0.999677** |
| **Random Forest Classifier** | 🌲 **0.993293** |
| **Gaussian NB** | 🔵 **0.813752** |
| **Logistic Regression** | ➕ **0.777796** |
| **Bernoulli NB** | 🔴 **0.614415** |
| **Deep Learning Model** | 🧠 **0.979072** |

---

## 🔑 Key Takeaways
✅ **Top Performers:**  
- **KNeighbors, Gradient Boosting, and Decision Tree classifiers** reached an exceptional **99.96%** accuracy.  
- **Random Forest** followed closely with **99.33%** accuracy.  

⚠️ **Weaker Models:**  
- **Naïve Bayes models (Gaussian NB & Bernoulli NB)** had significantly lower performance, indicating the dataset may not align well with probabilistic approaches.  
- **Logistic Regression** achieved a modest **77.78%**, suggesting linear models are not the best fit.  

🧠 **Deep Learning Model:**  
- The **neural network** performed well with **97.90%** accuracy but was slightly outperformed by traditional models.  
- Further **hyperparameter tuning** and **advanced architectures** could improve its performance.
- 
---
