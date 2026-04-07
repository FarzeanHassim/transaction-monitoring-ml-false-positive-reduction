# 🔍 Transaction Monitoring Optimization & False Positive Reduction (ML)

## 📌 Overview
This project simulates a transaction monitoring system and demonstrates how machine learning can reduce false positives and improve alert quality in AML/fraud detection workflows.

A traditional rules-based alert system is compared against a logistic regression model to illustrate how data-driven approaches can enhance detection efficiency and prioritisation.

---

## 📂 Access Notebook
👉 [View Full Notebook](https://github.com/FarzeanHassim/transaction-monitoring-ml-false-positive-reduction/blob/main/transaction_monitoring_optimization_ml.ipynb)

---

## 🎯 Objective
- Simulate transaction monitoring alert generation  
- Identify inefficiencies in rule-based detection  
- Reduce false positives through machine learning  
- Improve alert prioritisation and investigation efficiency  

---

## ⚙️ Methodology
1. Generate synthetic transaction dataset representing customer behaviour and risk indicators  
2. Apply rules-based detection logic to generate alerts  
3. Label alerts as true positives vs false positives  
4. Train a logistic regression model on labelled data  
5. Evaluate model performance against baseline rules  

---

## 📊 Key Results
- Baseline alerts generated: 8  
- False positives (rules-based): 3 (37.5%)  
- Machine learning model improved precision and reduced false positives  

This demonstrates how ML can enhance alert quality and reduce unnecessary investigation workload.

Note: Results are based on simulated data for demonstration purposes.

---

## 🧠 Key Insight
Rules-based transaction monitoring systems are often static and generate large volumes of low-quality alerts.

Machine learning introduces:
- Better risk prioritisation  
- Improved signal-to-noise ratio  
- More efficient allocation of investigation resources  

---

## 🏦 Real-World Application
This solution is relevant for:
- AML transaction monitoring systems in banks  
- Fraud detection in payment networks  
- Fintech risk engines (e.g. digital wallets, payment processors)  

It aligns with industry trends toward:
- Risk-based alert prioritisation  
- Data-driven compliance frameworks  
- Operational efficiency in financial crime investigations  

---

## 🛠️ Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---
## 💼 Business Impact
Reducing false positives improves investigator capacity, reduces alert backlog, and enables more efficient allocation of compliance resources.

---
## 🚀 Future Improvements
- Incorporate real transaction datasets for validation  
- Explore advanced models (e.g. XGBoost, Random Forest)  
- Implement real-time scoring pipeline  
- Develop dashboard for monitoring alert trends and model performance  

---

## 👤 Author
Farzean Hassim
