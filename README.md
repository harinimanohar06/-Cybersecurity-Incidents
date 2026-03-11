## 🔍 Project Overview

Modern cybersecurity systems generate a large number of alerts every day. Security analysts must analyze these alerts and determine the **severity level of each incident** in order to respond quickly to potential threats. However, manually analyzing thousands of alerts can be time-consuming and may delay the response to critical incidents.

This project develops a **Machine Learning–based Incident Grade Prediction system** that automatically classifies cybersecurity alerts based on their severity level. By analyzing multiple alert attributes such as device information, detector IDs, network message IDs, and organizational identifiers, the model predicts the **incident grade** of a security alert.

### 🎯 Objective
The main objective of this project is to build a model that can accurately classify incidents into different severity levels:

- 🟢 **Grade 0 — Low Severity**
- 🟡 **Grade 1 — Medium Severity**
- 🔴 **Grade 2 — High Severity**

### 📊 Dataset
The dataset used in this project contains **100,000 cybersecurity alert records** with **24 features** describing various attributes of incidents.

These features include:

- 🏢 Organization information
- 🚨 Alert identifiers
- 🛠 Detector details
- 💻 Device identifiers
- 🌐 Network message information
- 🔑 Security hashes and URLs
- 📅 Time-based features

### ⚙️ Machine Learning Pipeline

The project follows a complete **machine learning workflow**:

1️⃣ 📥 Data Loading  
2️⃣ 🧹 Data Preprocessing  
3️⃣ 🧠 Feature Selection using ANOVA (SelectKBest)  
4️⃣ 🔀 Train-Test Data Splitting  
5️⃣ 🤖 Model Training  
6️⃣ 📈 Model Evaluation  
7️⃣ 💾 Model Saving for Deployment  

### 🤖 Models Implemented

Three machine learning models were evaluated:

- 🌲 **Random Forest Classifier**
- 📉 **Logistic Regression**
- 🌳 **Decision Tree Classifier**

### 🏆 Best Model

After evaluation, the **Decision Tree Classifier** achieved the best performance with an accuracy of approximately **91%**, making it the final model selected for prediction.

### 🚀 Application

The trained model can be integrated into a **Python Notebook**, allowing users to input incident details and instantly receive the predicted **incident severity level**.

This system demonstrates how **Machine Learning can help cybersecurity teams prioritize threats efficiently and automate incident classification.**
---
##Overview 
<img width="1920" height="1080" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/6e487566-8f3f-4318-8459-06222a8f41b3" />
<img width="1920" height="1080" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/6bade9c4-de82-4024-8f38-85706e8dd7ce" />

