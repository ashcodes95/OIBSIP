# 🍷 Wine Quality Prediction using Machine Learning

> An end-to-end Machine Learning project that predicts whether a wine is **Good** or **Bad** based on its physicochemical properties using **Random Forest**, **Support Vector Classifier (SVC)**, and **Stochastic Gradient Descent (SGD)**.

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

# 📌 Project Overview

Wine quality depends on several physicochemical properties such as acidity, alcohol content, sulphates, pH, density, etc.

This project uses Machine Learning techniques to predict wine quality by transforming the original multi-class problem into a **Binary Classification Problem**:

- 🍷 **Good Wine** → Quality ≥ 6
- 🍷 **Bad Wine** → Quality < 6

Three machine learning models were trained and compared to identify the best-performing algorithm.

---

# 🚀 Features

✅ Data Cleaning

✅ Exploratory Data Analysis (EDA)

✅ Correlation Heatmap

✅ Class Imbalance Analysis

✅ Feature Engineering

✅ Train-Test Split with Stratification

✅ Feature Scaling

✅ Multiple ML Models

✅ Model Evaluation

✅ Confusion Matrices

✅ Feature Importance Analysis

---

# 🛠️ Tech Stack

- 🐍 Python
- 📊 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 🎨 Seaborn
- 🤖 Scikit-Learn
- 📓 Jupyter Notebook

---

# 📂 Dataset

The dataset contains physicochemical measurements of wine samples including:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality

---

# 📊 Exploratory Data Analysis

The project includes:

- 📌 Dataset Inspection
- 📌 Statistical Summary
- 📌 Distribution Plots
- 📌 Correlation Heatmap
- 📌 Quality Distribution
- 📌 Class Imbalance Discussion

---

# 🧠 Feature Engineering

The original quality labels were converted into binary labels:

```python
quality >= 6 → Good Wine (1)

quality < 6 → Bad Wine (0)
```

This helped reduce class imbalance and improved model performance.

---

# ✂️ Data Preprocessing

- Remove unnecessary columns
- Binary Label Encoding
- Train-Test Split (80:20)
- Stratified Sampling
- Standard Scaling (for SGD & SVC)

---

# 🤖 Machine Learning Models

The following models were trained:

### 🌲 Random Forest Classifier

- Ensemble Learning
- Decision Trees
- Feature Importance

---

### 📈 SGD Classifier

- Linear Classifier
- Fast Training
- Gradient Descent Optimization

---

### 🎯 Support Vector Classifier (SVC)

- Maximum Margin Classifier
- High Accuracy
- Feature Scaling Required

---

# 📈 Model Evaluation

Each model was evaluated using:

- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ F1 Score
- ✅ Confusion Matrix

---

# 🏆 Best Model

According to the experimental results,

🥇 **Random Forest Classifier** achieved the highest overall performance.

### Advantages

- ✅ Highest Accuracy
- ✅ Better Generalization
- ✅ Handles Non-linear Data
- ✅ Less Overfitting
- ✅ Feature Importance Ranking
- ✅ Robust Predictions

---

# 📊 Feature Importance

The Random Forest model identified the following important features:

🥇 Alcohol

🥈 Sulphates

🥉 Total Sulfur Dioxide

⭐ Volatile Acidity

⭐ Density

These features contribute the most toward predicting wine quality.

---

# 📸 Project Screenshots

## 📌 Dataset Inspection

![Dataset Inspection](assets/Screenshot%202026-08-07%20000628.png)

---

## 📌 Dataset Information & Statistics

![Dataset Information & Statistics](assets/Screenshot%202026-08-07%20000640.png)

---

## 📌 Wine Quality Distribution

![Wine Quality Distribution](assets/Screenshot%202026-08-07%20000647.png)

---

## 📌 Exploratory Data Analysis (EDA)

![Exploratory Data Analysis](assets/Screenshot%202026-08-07%20000703.png)

---

## 📌 Correlation Heatmap

![Correlation Heatmap](assets/Screenshot%202026-08-07%20000709.png)

---

## 📌 Class Imbalance Discussion

![Class Imbalance Discussion](assets/Screenshot%202026-08-07%20000714.png)

---

## 📌 Feature Engineering

![Feature Engineering](assets/Screenshot%202026-08-07%20000718.png)

---

## 📌 Train-Test Split & Feature Scaling

![Train-Test Split & Feature Scaling](assets/Screenshot%202026-08-07%20000728.png)

---

## 📌 Training Machine Learning Models

![Training Machine Learning Models](assets/Screenshot%202026-08-07%20000733.png)

---

## 📌 Random Forest Evaluation

![Random Forest Evaluation](assets/Screenshot%202026-08-07%20000740.png)

---

## 📌 Random Forest Confusion Matrix

![Random Forest Confusion Matrix](assets/Screenshot%202026-08-07%20000744.png)

---

## 📌 SGD Classifier Evaluation

![SGD Classifier Evaluation](assets/Screenshot%202026-08-07%20000752.png)

---

## 📌 SGD Classifier Confusion Matrix

![SGD Classifier Confusion Matrix](assets/Screenshot%202026-08-07%20000803.png)

---

## 📌 Support Vector Classifier Confusion Matrix

![Support Vector Classifier Confusion Matrix](assets/Screenshot%202026-08-07%20000811.png)

---

## 📌 Feature Importance - Random Forest

![Feature Importance - Random Forest](assets/Screenshot%202026-08-07%20000816.png)

---

## 📌 Performance Comparison & Final Recommendation

![Performance Comparison & Final Recommendation](assets/Screenshot%202026-08-07%20000830.png)

---


# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Wine-Quality-Prediction.git
```

Move into the project

```bash
cd Wine-Quality-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 🎯 Future Improvements

- 🔹 Hyperparameter Tuning
- 🔹 Cross Validation
- 🔹 XGBoost
- 🔹 LightGBM
- 🔹 CatBoost
- 🔹 Flask Deployment
- 🔹 Streamlit Web App
- 🔹 Model Explainability using SHAP

---

# 👨‍💻 Author

**Akshat Sharma**

📧 Connect with me on LinkedIn

⭐ If you found this project helpful, don't forget to **Star** the repository!
