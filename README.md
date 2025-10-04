# 🛡️ Web Page Phishing Detection using Machine Learning

## 📌 Overview
This project implements a **Machine Learning model to detect phishing web pages** based on various URL and website features. Phishing is a common cyber-attack where malicious web pages trick users into providing sensitive information. The goal of this project is to build an automated phishing detection system using structured data.

## 📊 Dataset
- **File:** `web-page-phishing.csv`  
- **Description:** Contains features extracted from URLs/web pages, along with labels indicating whether a page is **phishing** or **legitimate**.  
- **Size:** ~10000 × 20 
- **Features Examples:**  
  - URL length  
  - Presence of `https`  
  - Number of subdomains  
  - Special characters (`@`, `-`, `//`)  
  - Domain-based features  
- **Target:**  
  - `1` → Phishing  
  - `0` → Legitimate  

## ⚙️ Workflow
1. **Data Preprocessing**  
   - Handled missing values & inconsistencies  
   - Feature encoding & normalization  

2. **Exploratory Data Analysis (EDA)**  
   - Statistical summary of dataset  
   - Correlation heatmap & feature importance visualization  

3. **Model Building**  
   - Trained ML models (e.g., Logistic Regression, Decision Tree, Random Forest, etc.)  
   - Hyperparameter tuning for better accuracy  

4. **Evaluation**  
   - Metrics used: Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix visualization  

## 📈 Results
- Achieved **high accuracy (e.g., ~95%)** in detecting phishing websites.  
- Random Forest performed best among tested models.  
- Visualization of results included confusion matrix and ROC curve. 
