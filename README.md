<div align="center">

# 🎗️ Breast Cancer Diagnostic Classification
### **Empowering Healthcare with Machine Learning & Predictive Analytics**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

**"Early detection saves lives."** This project leverages four robust Machine Learning algorithms to classify breast tumors with high precision, providing a reliable second opinion for clinical diagnostics.

[📂 Explore Data](#dataset) • [🧠 Models](#algorithms) • [📊 View Results](#results) • [🚀 Future Scope](#future-work)

---
</div>

## 📌 1. Project Overview
The **Wisconsin Diagnostic Breast Cancer (WDBC)** dataset is used to train models that distinguish between **Malignant** (Cancerous) and **Benign** (Non-cancerous) tumors. The primary focus is achieving high **Recall** to minimize the risk of missing malignant cases.

## 📊 2. Dataset Characteristics
- **Total Samples:** 569
- **Features:** 30 Dimensional numeric vector (Radius, Texture, Perimeter, Area, etc.)
- **Class Distribution:** 357 Benign (62.7%), 212 Malignant (37.3%)

## ⚙️ 3. Technical Pipeline
The project follows a rigorous data science workflow:
1. **Data Cleaning:** Removal of redundant ID columns and handling nulls.
2. **Preprocessing:** Label encoding of target variables.
3. **Feature Scaling:** Applied `StandardScaler` to normalize features for distance-based models.
4. **Splitting:** 80/20 Train-Test split for unbiased evaluation.

## 🧠 4. Benchmarked Algorithms
We compared four distinct architectures to find the optimal boundary:
* **Logistic Regression:** Baseline statistical probability.
* **K-Nearest Neighbors (KNN):** Classification based on spatial proximity.
* **Support Vector Machine (SVM):** Maximum-margin hyperplane separation.
* **Decision Trees:** Interpretable hierarchical logic.

## 📈 5. Key Results & Insights
Our comparative analysis revealed the following performance ranking:

| Algorithm | Accuracy | Best For |
| :--- | :--- | :--- |
| **SVM** | ~98% | High-dimensional precision |
| **Logistic Regression** | ~97% | Efficiency & Baseline |
| **KNN** | ~96% | Clustering patterns |
| **Decision Tree** | ~94% | Interpretability & Logic |

> **Insight:** SVM and Logistic Regression showed the most stable results for this clinical dataset.

## 🛠️ 6. Tech Stack
- **Languages:** ![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python)
- **Libraries:** ![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas) ![NumPy](https://img.shields.io/badge/-NumPy-333333?style=flat&logo=numpy) ![ScikitLearn](https://img.shields.io/badge/-ScikitLearn-333333?style=flat&logo=scikitlearn)
- **Visualization:** ![Seaborn](https://img.shields.io/badge/-Seaborn-333333?style=flat) ![Matplotlib](https://img.shields.io/badge/-Matplotlib-333333?style=flat)

## 🚀 7. Future Work
- [ ] Implement **Neural Networks** (Deep Learning).
- [ ] Perform **Hyperparameter Tuning** via GridSearchCV.
- [ ] Build a **Web Interface** using Streamlit.
- [ ] Integrate **K-Fold Cross-Validation**.

## 👤 8. Author
- **Hala alkhawaldek**
  
- Department of Data Science & AI

---
<div align="center">
⭐ If you find this project useful, give it a star!
</div>
