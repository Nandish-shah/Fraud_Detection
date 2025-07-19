# 💳 Fraud Detection using Machine Learning

## 📌 Objective

This project aims to develop a machine learning model that can **accurately detect fraudulent transactions** using transaction data by analyzing behavioral patterns and anomalies. The system is built using **supervised classification techniques** like Logistic Regression and Random Forest, with a strong emphasis on handling **class imbalance** using SMOTE.

---

## 🧠 Key Features

- 📊 **Data Simulation:** Synthetic transaction dataset generation (99% normal, 1% fraudulent).
- 🧼 **Data Preprocessing:** Outlier handling, correlation checks, and class distribution balancing.
- 📈 **Exploratory Data Analysis:** Visualizations to uncover hidden patterns and trends.
- 🏷️ **Feature Engineering:** Extract meaningful variables from transaction data.
- 🤖 **Modeling:** Logistic Regression and Random Forest classifiers to detect fraud.
- ⚖️ **Class Imbalance Handling:** Applied **SMOTE** to balance rare fraud cases.
- 📉 **Model Evaluation:** Metrics like Accuracy, Precision, Recall, F1 Score, and ROC-AUC Curve.

---

## 🛠️ Technologies Used

| Tool | Description |
|------|-------------|
| **Python** | Programming Language |
| **Pandas / NumPy** | Data Manipulation and Analysis |
| **Matplotlib / Seaborn** | Data Visualization |
| **Scikit-learn** | ML Modeling & Evaluation |
| **imblearn (SMOTE)** | Handling Class Imbalance |

---

## 🧪 Workflow Summary

### 1. **Import Required Libraries**
Standard Python ML stack, including tools for modeling, evaluation, and visualization.

### 2. **Generate Synthetic Dataset**
A function creates a simulated credit card dataset with:
- 99% normal transactions
- 1% fraudulent transactions
- Features: `Time`, `V1`–`V10`, `Amount`, and `Class` (label)

### 3. **Data Exploration**
- Checks dataset structure, null values, and class distribution
- Uses plots to show amount/time distribution, class frequency, and feature correlations

### 4. **Visualization Highlights**
- **Bar plot** of class balance
- **Histograms** of transaction amounts and times
- **Boxplot** for amount comparisons
- **Heatmap** for correlation between features

### 5. **Data Preprocessing & Balancing**
- Uses **SMOTE** to handle imbalance in the dataset
- Scales features if necessary

### 6. **Model Training**
Applies:
- ✅ **Logistic Regression** – Baseline model
- ✅ **Random Forest Classifier** – Advanced ensemble model for better accuracy

### 7. **Model Evaluation**
- Classification Report (Precision, Recall, F1)
- Confusion Matrix
- ROC-AUC Score and Curve

---

## 📊 Results

- The **Random Forest** model achieved high precision and recall for fraudulent transaction detection.
- The system can be extended to real-world scenarios with minimal changes to accommodate live datasets.

---

## 🚀 Future Improvements

- Integrate real-world transaction datasets
- Test additional models like XGBoost, LightGBM
- Deploy the model using a web app (e.g., Streamlit)
- Enable real-time fraud detection with APIs


