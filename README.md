Goal: Detect anomalous credit card transactions with an autoencoder trained on legitimate data, compare against ML baselines, and deploy a usable system.

Deliverables:

EDA and feature engineering notebook
Baseline ML models (LogReg, RandomForest, XGBoost)
Deep autoencoder with thresholding
FastAPI inference service
Streamlit monitoring dashboard
Interview‑ready documentation and demo


# Credit Card Fraud Detection Using Autoencoder & Machine Learning

This project builds a **complete end-to-end Fraud Detection System** using  
**EDA + Feature Engineering → ML Models → Autoencoder → Real-time API → Streamlit Dashboard**.

It is designed for **production-grade deployment**, **interview excellence**, and **portfolio impact**.

---

## 🚀 Project Workflow
1. **Exploratory Data Analysis (EDA)**
2. **Feature Engineering**
3. **Machine Learning Models**  
   - Random Forest  
   - XGBoost
4. **Deep Learning Autoencoder**
5. **Threshold Optimization**
6. **Model Evaluation**
7. **FastAPI Fraud Detection API (Real-time)**
8. **Streamlit Fraud Monitoring Dashboard**
9. **Docker Deployment**
10. **Documentation + LinkedIn Posts + Demo Recording**

---

## 📊 Dataset
Source: Kaggle – Credit Card Fraud (284,807 transactions, 492 frauds)

Class imbalance: **0.172% fraud cases**

---

## 🧠 ML & Deep Learning Models

### ✔ RandomForestClassifier
- Handles imbalanced data using class weights  
- Good interpretability (feature importance)

### ✔ XGBoost
- Works excellent with tabular & imbalanced data
- Tuned using RandomizedSearchCV

### ✔ Autoencoder (Deep Learning)
- Learns normal transaction patterns
- High reconstruction error → Fraud

Architecture:
- Encoding: 29 → 14 → 7  
- Bottleneck: 7  
- Decoding: 7 → 14 → 29

Loss: MSE  
Optimizer: Adam  

---

## 🧪 Evaluation Metrics
- AUC-ROC  
- Precision-Recall Curve  
- F1-Score  
- Confusion Matrix  
- Reconstruction Error Distribution  
- Threshold optimized using Youden’s J statistic

---

## ⚡ Real-time Fraud Detection API (FastAPI)

### Endpoints:


The API loads the trained **Autoencoder + Threshold** and predicts fraud instantly.

---

## 📈 Streamlit Fraud Monitoring Dashboard

Features:
- Real-time fraud stats
- Transaction-level drilldown
- Reconstruction error visualization
- Model confidence score
- System monitoring (API health, logs)

---

## 🏗️ Project Structure

(Already provided above)

---

## 🐳 Deployment (Docker)
Two containers:
- `fraud-api`
- `fraud-dashboard`

Or deploy API to:
- AWS EC2  
- Render  
- Azure App Service  

---

## 📌 Demo Video
Includes:
- Project motivation  
- Architecture explanation  
- API demo  
- Dashboard walkthrough  

---

## 🧾 License
MIT License

---

## 📲 Connect With Me
LinkedIn | GitHub

