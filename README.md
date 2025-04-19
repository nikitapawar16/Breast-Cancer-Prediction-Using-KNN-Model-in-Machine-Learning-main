# 🧠 Breast Cancer Prediction using K-Nearest Neighbors (KNN)

## 📋 Project Overview
This project aims to predict whether a tumor is benign or malignant using the Breast Cancer Wisconsin dataset and the K-Nearest Neighbors (KNN) algorithm. It combines a machine learning backend with a Streamlit-based frontend that allows users to input tumor characteristics and receive real-time predictions.

---

## 🔍 Dataset
The project uses the Breast Cancer Wisconsin dataset, which includes several numerical features that describe tumor characteristics such as:
- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Marginal Adhesion
- Single Epithelial Cell Size
- Bare Nuclei
- Bland Chromatin
- Normal Nucleoli
- Mitoses

---

## 🚀 Features
- Machine Learning Model: Built using a KNN classifier to predict tumor type (benign or malignant).
- Frontend Application: Developed with Streamlit for easy user input and instant predictions.
- Model Optimization: Explored multiple k values (3 to 9) to determine the optimal model configuration.

---

## 🛠️ Project Components

### 🔧 Data Preprocessing
- Handled missing values using median imputation
- Feature scaling using StandardScaler
- Data split: 80% training / 20% testing

### 📈 KNN Model
- Trained KNN classifiers with various k values (3 to 9)
- Best performance achieved with k=6, k=7, and k=8
- Evaluation metrics: Confusion Matrix, Accuracy, Precision, Recall, F1-Score

---

## 🌐 Streamlit Frontend
- Simple UI for users to input tumor features like clump thickness, cell uniformity, and more
- Predicts tumor type using the trained KNN model in real-time

---

## 📊 Model Results

**Best Accuracy**: 97.86% (with k=6 and k=7)

- Precision: 97.65%
- Recall: 97.65%
- F1-Score: 97.65%
- Null Accuracy: 60.71%

---

## 🤖 Technologies Used
- Python – Core programming
- Scikit-learn – ML model, scaling, evaluation
- Streamlit – Frontend UI
- Pandas & NumPy – Data manipulation
- Matplotlib & Seaborn – Data visualization

---

## 📌 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Model validation with K-Fold Cross-Validation
- Cloud deployment of the Streamlit app for wider accessibility
