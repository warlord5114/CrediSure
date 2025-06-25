# CrediSure 🔐  
*A Dual-Model Framework for Credit Scoring and Loan Fraud Detection*

> Developed for the **PSB Hackathon 2025**, organized by **SBI Bank** in collaboration with the **Technical Board, IIT Guwahati**

---

## 📌 Overview

**CrediSure** is a fintech project designed to assess individual creditworthiness and proactively detect fraudulent loan applications. It comprises two major components:

1. A **Credit Score Calculator** built using supervised machine learning algorithms and ensemble methods.
2. A **Loan Fraud Detection Model** trained on anonymized financial datasets to flag potential fraud.

This project demonstrates the application of data science and business logic to enhance credit risk management for public sector banks.

---

## 🗂️ Repository Structure

### 🧪 Notebooks

- **`csc.ipynb`** — *Credit Score Calculator*  
  > A comprehensive tool to compute the credit score of an individual by accepting user-inputted financial and behavioral parameters.  
  > The model leverages **ensemble learning**, combining the strengths of the following classifiers:
  - `LogisticRegression`
  - `RandomForestClassifier`
  - `SVC` (Support Vector Classifier)
  - `KNeighborsClassifier`
  
  The output is a predicted credit score based on a consensus of these models.

- **`fintech.ipynb`** — *Model Evaluation & Benchmarking*  
  > Individually evaluates the four models used in the ensemble for credit scoring.  
  > Includes comparison metrics (accuracy, precision, recall) to assess standalone performance of each algorithm.

- **`fraud_detection.ipynb`** — *Fraud Detection Model*  
  > Final submission notebook for the PSB Hackathon.  
  > Trains a fraud classification model on anonymized transactional and user profile data.  
  > The best-performing model (XGBoost) is selected based on real-world performance metrics (confusion matrix, ROC-AUC, F1-score).

---

## 📄 Documentation

- **`credisure.pdf`** — Final project report including business problem, methodology, model architecture, evaluation results, and impact potential.
- **`credit score calculator.pdf`** — Technical description and working logic of the credit score calculator (corresponding to `csc.ipynb` and `fintech.ipynb`).

---

## 🧠 Technology Stack

- Programming: **Python 3.x**
- Libraries:  
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`, `xgboost`
- Environment: **Jupyter Notebook**

---

## 🎯 Objectives

- To provide a **data-driven, adaptable, and transparent** approach to individual credit scoring.
- To build a **robust fraud detection system** that enhances trust and safety in loan disbursal mechanisms.

---

## 📊 Results Snapshot

* **Credit Scoring**

  * Ensemble model achieved higher consistency and generalizability across varied user inputs.
  * Parameters include transaction behavior, repayment history, account age, etc.

* **Fraud Detection**

  * XGBoost classifier delivered the highest recall and AUC score on test data.
  * Efficient at identifying hidden fraud patterns in anonymized logs.

---

## 🏁 Contribution & Impact

This repository was submitted as part of the **PSB Hackathon 2025**, organized by **State Bank of India** in partnership with **IIT Guwahati**.
The solution proposes a scalable and insightful tool that can be integrated into banking workflows to improve financial inclusion and reduce fraud risk.

---


