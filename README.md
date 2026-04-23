# 📧 Spam Email Detection System

## 📌 Project Overview
This project focuses on building a machine learning model to classify emails as **Spam** or **Legitimate (Ham)**. It uses text processing techniques and dimensionality reduction to improve performance and accuracy.

---

## 🎯 Objective
To develop a system that can automatically detect whether an email is spam or not based on its content.

---

## 📂 Dataset
- Dataset used: **Spam Email Detection Dataset**
- The dataset contains labeled emails:
  - **Spam (1)**
  - **Not Spam / Ham (0)**

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Remove punctuation and special characters  
- Convert text to lowercase  
- Remove stopwords  
- Tokenization  

### 2. Feature Extraction
- Convert text into numerical format using:
  - TF-IDF (Term Frequency-Inverse Document Frequency)

### 3. Dimensionality Reduction
- Apply **Truncated SVD (Singular Value Decomposition)**  
- Helps reduce feature size and improve efficiency  

### 4. Model Used
- **Weighted K-Nearest Neighbors (WKNN)**
  - Assigns weights to neighbors based on distance  
  - Closer neighbors have more influence  

---

## 🧠 Workflow
1. Load dataset  
2. Preprocess text data  
3. Convert text into vectors (TF-IDF)  
4. Apply Truncated SVD  
5. Train WKNN model  
6. Predict and evaluate results  

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

## 🛠️ Technologies Used
- Python  
- Scikit-learn  
- Pandas  
- NumPy  

---
