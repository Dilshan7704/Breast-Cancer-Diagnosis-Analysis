# 🩺 Breast Cancer Diagnosis Analysis using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

### 🚀 Machine Learning Project for Breast Cancer Diagnosis Prediction

Predicting whether a breast tumor is **Benign** or **Malignant** using **Exploratory Data Analysis**, **Feature Engineering**, **PCA**, and **Support Vector Machine (SVM)**.

</div>

---

# 📌 Project Overview

Breast cancer is one of the most common cancers affecting women worldwide. Early diagnosis plays a critical role in improving treatment outcomes.

This project focuses on building a complete Machine Learning pipeline capable of classifying tumors as **Benign** or **Malignant** using diagnostic measurements.

The project includes:

🔬 Data Cleaning & Preprocessing

📊 Exploratory Data Analysis (EDA)

🛠️ Feature Engineering

📉 Correlation Analysis

⚙️ Outlier Treatment using Winsorization

🧠 Dimensionality Reduction using PCA

🤖 Support Vector Machine (SVM) Classification

🎯 Hyperparameter Tuning using GridSearchCV

📈 Model Evaluation

💾 Model Serialization using Joblib

🔮 Cancer Prediction System

---

# 🗂️ Project Structure

```bash
BREAST-CANCER-DIAGNOSIS-ANALYSIS/
│
├── 📁 Data Set/
│   └── Breast Cancer.csv
│
├── 📁 Models/
│   ├── best_model.pkl
│   ├── x_train.pkl
│   ├── x_test.pkl
│   ├── y_train.pkl
│   └── y_test.pkl
│
├── 📁 src/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   ├── evaluation.ipynb
│   └── prediction.ipynb
│
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📄 README.md
```

---

# 📈 Visualizations

The project includes multiple visualizations such as:

📊 Benign vs Malignant Countplot

📈 KDE Distribution Analysis

📉 Histograms for All Features

📦 Boxplots for Key Features

🔥 Correlation Heatmap

🎯 Feature Correlation with Diagnosis

---

# 🤖 Machine Learning Models

| Model | Status |
|---------|---------|
| Baseline SVM | 🧪 Tested |
| PCA + SVM Pipeline | 🏆 Best Performance |

---

# 🏆 Best Performing Model

## 🥇 PCA + Support Vector Machine (SVM)

The final model pipeline consists of:

🔹 StandardScaler

🔹 Principal Component Analysis (PCA)

🔹 Support Vector Machine (SVM)

### Techniques Used

🧩 Stratified K-Fold Cross Validation

🎯 GridSearchCV

⚙️ Hyperparameter Optimization

📈 Recall Score Optimization

---

# 📌 Evaluation Metrics

The model was evaluated using:

📊 Accuracy Score

🎯 Precision

📈 Recall

⚖️ F1 Score

📋 Classification Report

🔥 Confusion Matrix

---

# 💾 Model Serialization

```python
joblib.dump(best_model,'best_model.pkl')
```

---

# 🔮 Cancer Prediction System

```python
predict_cancer(input_data)
```

Output:

🟢 Benign Tumor

🔴 Malignant Tumor

---

# 🚀 Future Improvements

🌐 Streamlit Deployment

☁️ Cloud Deployment

⚡ Real-Time Prediction API

🤖 Ensemble Learning Models

📱 Interactive User Interface

🔬 Advanced Feature Engineering

---

# 👨‍💻 Author

## Dilshan Nethmin Wijayarathne

💻 Data Science Undergraduate

🤖 AI & Machine Learning Enthusiast

📊 Data Analytics and Intelligent Systems Developer

🌐 Full Stack Developer

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the project

🛠️ Contribute to improvements

---

<div align="center">

## 🩺 Breast Cancer Diagnosis Analysis using Machine Learning

### PCA + Support Vector Machine (SVM) Classification

🚀 Thanks for Visiting

</div>
