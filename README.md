# **📌 Breast Cancer Diagnosis — KNN & K-Means**

This project classifies breast cancer tumors into **Malignant (M)** or **Benign (B)** using **K-Nearest Neighbors (KNN)** and performs clustering using **K-Means**.

Dataset used: Breast Cancer Dataset


## **🚀 Objectives**

The goal of this project is to:

* Convert the diagnosis column: M → 1, B → 0

* Drop unnecessary columns:

- id
- Unnamed: 32
  
- Apply **Min-Max Normalization**

- Split the dataset into:

- **Training: 80%**
- **Testing: 20%**
   
- Apply **K-Means clustering (k=2)** to observe patterns between benign and malignant tumors

- Train a KNN classifier with **k = 5**

- Evaluate the model using:

- Accuracy
- Precision
- Recall
- F1-score
