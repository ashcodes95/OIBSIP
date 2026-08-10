# 🚀 OIBSIP — Oasis Infobyte Summer Internship Program

**Track:** 📈 Data Analytics · **Level:** 2 · **Tasks Completed:** 1, 2 & 3

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Internship](https://img.shields.io/badge/Oasis%20Infobyte-SIP-purple)

---

## 👋 About This Repository

This repository contains my project submissions for the **Oasis Infobyte Summer Internship Program (OIBSIP)**, under the **📈 Data Analytics** track.

> 📝 *"Learning is the only thing the mind never exhausts, never fears, and never regrets." — Leonardo da Vinci*

Per the internship's completion rules for Data Analytics, interns must complete **at least 3 tasks from Level 1 or Level 2 combined**. I chose to complete **all 3 tasks from Level 2**, which involved end-to-end machine learning pipelines — from data cleaning and EDA to model training, evaluation, and business interpretation.

---

## 🗂️ Repository Structure

Following OIBSIP's required naming convention `OIBSIP/[TrackName]-[Level/Task]-[ProjectName]/`, this repo is organized as:

```
OIBSIP/
│
├── DataAnalytics-L2-HousePricePrediction/
│   ├── house_price_prediction.ipynb
│   ├── README.md
│   └── screenshots/
│
├── DataAnalytics-L2-WineQualityPrediction/
│   ├── wine_quality_prediction.ipynb
│   ├── README.md
│   └── screenshots/
│
├── DataAnalytics-L2-FraudDetection/
│   ├── fraud_detection.ipynb
│   ├── README.md
│   └── screenshots/
│
└── README.md   ← you are here 📍
```

Each task folder contains its own source code, a dedicated `README.md`, and supporting screenshots/output files, as required by the program guidelines.

---

## 📋 Task Summaries

### 1️⃣ 🏠 Predicting House Prices with Linear Regression

**Folder:** [`DataAnalytics-L2-HousePricePrediction`](./DataAnalytics-L2-HousePricePrediction)

**🎯 Objective:** Build and evaluate a linear regression model that predicts house prices based on features such as area, location, number of rooms, and age — covering the full pipeline from data cleaning to model interpretation.

**🛠️ Tech Stack:** Python, pandas, scikit-learn, matplotlib, seaborn, Jupyter Notebook

**✅ What was done:**
- 🔍 Exploratory Data Analysis (null checks, descriptive stats, target distribution)
- 🧩 Feature selection & categorical encoding (One-Hot Encoding)
- 🔥 Correlation heatmap to identify top price-driving features
- ✂️ 80/20 train-test split
- 📈 Trained a **Linear Regression** model
- 📊 Evaluated using **MSE, RMSE, and R² score**
- 📉 Actual vs. Predicted scatter plot & residual plot analysis
- 🧠 Coefficient analysis to interpret feature impact on price

---

### 2️⃣ 🍷 Wine Quality Prediction

**Folder:** [`DataAnalytics-L2-WineQualityPrediction`](./DataAnalytics-L2-WineQualityPrediction)

**🎯 Objective:** Train and compare multiple classification models to predict wine quality scores based on physicochemical properties like acidity, density, and alcohol content.

**🛠️ Tech Stack:** Python, pandas, numpy, scikit-learn (Random Forest, SGD, SVC), seaborn, matplotlib, Jupyter Notebook

**✅ What was done:**
- 🔍 EDA on chemical features + class distribution analysis
- ⚖️ Discussed class imbalance across quality scores
- 🏷️ Feature engineering — binned quality scores into meaningful categories
- ✂️ Stratified train/test split to preserve class ratios
- 🤖 Trained **3 classifiers**: Random Forest, SGD, and SVC
- 📊 Evaluated each with accuracy, classification report & confusion matrix
- 🌟 Feature importance chart (Random Forest)
- 🏆 Compared all models side-by-side and selected the best performer

---

### 3️⃣ 💳 Fraud Detection

**Folder:** [`DataAnalytics-L2-FraudDetection`](./DataAnalytics-L2-FraudDetection)

**🎯 Objective:** Build a machine learning pipeline to detect fraudulent transactions in a heavily **imbalanced dataset** (only ~0.17% of transactions are fraud), addressing class imbalance as the core challenge.

**🛠️ Tech Stack:** Python, pandas, scikit-learn, imbalanced-learn (SMOTE), matplotlib, seaborn, Jupyter Notebook

**✅ What was done:**
- 📊 Analyzed extreme class imbalance (**0.173% fraud rate**)
- 🔍 EDA on transaction amounts & time-of-day fraud patterns
- ⚠️ Explained why **accuracy is a misleading metric** here
- ⚖️ Applied **SMOTE** oversampling to balance training data
- ✂️ Stratified train/test split to preserve fraud ratio in both sets
- 🤖 Trained **Logistic Regression** & **Random Forest**
- 📈 Evaluated with **Precision, Recall, F1-Score & ROC-AUC**
- 🎯 Discussed the **Recall vs. Precision trade-off** for fraud use cases
- 🔍 Feature importance analysis (top features: `V14`, `V10`)
- 🚀 Discussed scalability for handling **1 million transactions/hour**

---

## 🧠 Key Learnings Across All 3 Tasks

- 📐 **Accuracy alone is not enough** — metrics like Precision, Recall, F1, and ROC-AUC give a fuller picture, especially on imbalanced data.
- ⚖️ **Class imbalance handling** (SMOTE, stratification, class weighting) is critical for reliable fraud/quality classifiers.
- 🔎 **EDA first, modeling second** — understanding data distributions and relationships before modeling leads to better feature choices.
- 🤝 **Model comparison matters** — no single algorithm wins every time; comparing multiple models with the right metrics reveals the best fit for the problem.
- 💬 **Communicating results** — translating model outputs (coefficients, feature importances) into plain-language business insights is as important as building the model itself.

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/ashcodes95/OIBSIP.git
cd OIBSIP

# 2. Navigate to a task folder
cd DataAnalytics-L2-HousePricePrediction

# 3. Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn jupyter

# 4. Launch the notebook
jupyter notebook
```

> 📌 Datasets are sourced from Kaggle/UCI as per each task's guidelines and are not included in this repo due to size — see each task's individual README for the dataset link.

---

## 🏅 About Oasis Infobyte SIP

The **Oasis Infobyte Summer Internship Program** is a hands-on internship where interns build real-world projects across various tech domains (Web Dev, Android, Java, Graphics Design, Data Science, Python, **Data Analytics**, and Cyber Security), submit them via GitHub, and demo them on LinkedIn.

- 🌐 Website: [oasisinfobyte.com](http://www.oasisinfobyte.com)
- 💼 LinkedIn: [Oasis Infobyte](https://in.linkedin.com/company/oasis-infobyte)

---

## 📬 Connect With Me

Feel free to explore each task folder for detailed notebooks, visualizations, and write-ups. Feedback and suggestions are always welcome! 🙌

<p align="center">Made with ❤️, Python 🐍, and a lot of pandas 🐼 during #oasisinfobyte</p>
