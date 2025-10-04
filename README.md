# 🛡️ Web Page Phishing Detection using Machine Learning

## 📌 Overview
This project implements a **Machine Learning model to detect phishing web pages** based on various URL and website features. Phishing is a common cyber-attack where malicious web pages trick users into providing sensitive information. The goal of this project is to build an automated phishing detection system using structured data.

## 📊 Dataset
- **File:** `web-page-phishing.csv`  
- **Description:** Each row represents one website’s URL. The features are numerical counts of certain symbols or characteristics in the URL 
- **Size:** 100,077 × 20 
- **Target:**  
  - `1` → Phishing  
  - `0` → Legitimate  

## ⚙️ Models and Performance

| Model                | Accuracy | ROC-AUC |
|-----------------------|----------|---------|
| Logistic Regression   | **85.63%** | 0.93 |
| Random Forest         | **89.09%** | 0.95 |
| XGBoost (Best Model)  | **89.18%** | 0.96 |

**XGBoost provided the most balanced performance across precision, recall, and F1-score.**

---

## 📈 Results
- Achieved **~89% accuracy** with the best model (XGBoost).  
- Metrics Used: Accuracy, Confusion Matrix, Classification Report, ROC-AUC.
- Findings: Ensemble models (Random Forest, XGBoost) outperform linear models.
