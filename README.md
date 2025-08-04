# 🚧 PMGSY Rural Infrastructure Classification – IBM Cloud

This project leverages **IBM Watsonx.ai**, **Cloud Object Storage**, and **machine learning** techniques to classify rural infrastructure projects under the **Pradhan Mantri Gram Sadak Yojana (PMGSY)** schemes using publicly available data from **AI Kosh**.

---

## 📌 Problem Statement

The Pradhan Mantri Gram Sadak Yojana (PMGSY) aims to provide all-weather road connectivity to rural India. It has multiple schemes/phases like PMGSY-I, II, III, RCPLWEA, and PM-JANMAN. 

Manually classifying thousands of projects is time-consuming and error-prone.  
This project uses machine learning to **automatically classify** each project into its respective scheme based on physical and financial attributes.

---

## 🧠 Proposed Solution

- Clean and preprocess the PMGSY dataset
- Train a **Random Forest Classifier** to learn from the dataset
- Deploy the model on **IBM Watsonx.ai**


---

## 🏗️ Technologies Used

- **IBM Watsonx.ai** (Lite Plan)
- **IBM Cloud Object Storage (COS)**
- **Python, Pandas, Scikit-learn**
- **Seaborn, Matplotlib** (for visualization)
- **Joblib** (for model serialization)


---

## 🧪 Model & Accuracy

- Model: **Random Forest Classifier**
- Accuracy: **~89%** on test data
- Performed well across all major PMGSY schemes
- Visualized confusion matrix for deeper evaluation

---



