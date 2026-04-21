# 🔍 Transaction Monitoring Optimization & False Positive Reduction (ML)

## 📌 Overview

This project simulates a machine learning-enhanced transaction monitoring optimisation system designed to reduce false positives and improve alert quality.

It compares a traditional rules-based alert generation approach with a logistic regression model to demonstrate how machine learning can refine risk detection and enhance decisioning in AML workflows.

The system highlights how data-driven models can be integrated into transaction monitoring pipelines to improve precision, reduce unnecessary alerts, and optimise investigator workload.

This builds on the rules-based decisioning system introduced in Project 1 (aml-risk-triage-system) by enhancing alert quality using machine learning.

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

## ⚙️ Model Framework

The system evaluates two approaches:

Baseline (Rules-Based):
- Alerts generated using predefined thresholds (transaction amount, frequency)

Machine Learning Model:
- Logistic regression trained on labelled risk outcomes
- Features include transaction behaviour, customer risk, and historical alerts

The ML model predicts true risk and helps distinguish between genuine alerts and false positives.

---

## 🧠 System Architecture

This project extends a traditional AML monitoring pipeline by incorporating machine learning:

1. Transaction data ingestion  
2. Rules-based alert generation (baseline)  
3. True risk labelling  
4. Machine learning model training  
5. ML-based risk prediction  
6. Alert refinement and prioritisation  

This demonstrates how ML can enhance existing transaction monitoring systems rather than replace them entirely.

---

## 📊 Key Result

The machine learning model demonstrates improved precision in identifying true high-risk cases, reducing false positives compared to the rules-based approach.

However, results are based on a small simulated dataset and may not generalise to real-world environments.

This highlights the importance of data quality, feature engineering, and model governance in production AML systems.

---

## 💼 Business Impact

This project demonstrates how financial institutions can:

- Reduce false positives in transaction monitoring systems  
- Improve investigator efficiency by prioritising high-quality alerts  
- Enhance detection precision through data-driven models  
- Support scalable AML operations through model-based optimisation  
- Bridge the gap between detection systems and operational workflows  

This reflects how modern AML platforms integrate machine learning into surveillance systems to improve both detection quality and operational efficiency.

In high-volume environments, even small improvements in false positive rates can significantly reduce operational workload, making rule tuning and alert optimisation critical components of scalable AML systems.

---

## ⚙️ Decisioning Enhancement

The ML model refines alert outcomes by filtering low-quality alerts:

- High ML-predicted risk → Prioritised for investigation  
- Low ML-predicted risk → De-prioritised or filtered  

This enhances the decisioning layer by improving signal quality and reducing unnecessary investigation effort.

---

## 🧠 Key Insight

Traditional rules-based systems are effective for broad detection but often generate high volumes of false positives.

Machine learning enhances these systems by:

- Improving precision and reducing false positives  
- Enhancing signal-to-noise ratio  
- Supporting more efficient allocation of investigation resources  

This demonstrates the value of hybrid approaches combining rules-based detection with ML-driven optimisation.

This mirrors real-world transaction monitoring environments where rule tuning and model outputs must be continuously calibrated to balance detection sensitivity and false positive rates.

---

## 🔄 Evolution Towards AI-Enabled Alert Optimisation

While this project focuses on machine learning-based optimisation, it represents an intermediate layer within a broader AI-enabled AML operating model.

Potential enhancements include:

- LLM-based alert explanation and summarisation  
- AI-assisted triage and prioritisation workflows  
- Integration with case review copilots for downstream decision support  
- Agentic workflows to dynamically adjust alert thresholds and prioritisation  

This reflects the shift from static rules-based systems toward hybrid and AI-assisted transaction monitoring architectures.

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
  
## ⚠️ Model Considerations

In real-world deployment, models require ongoing monitoring, validation, and governance to ensure performance stability and regulatory compliance.

---

## 🚀 Future Improvements

- Incorporate real transaction datasets for validation  
- Explore advanced models (e.g. XGBoost, Random Forest)  
- Implement real-time scoring pipeline  
- Develop dashboard for monitoring alert trends and model performance  

---
🔗 Extension to Cryptocurrency Monitoring

While this project is built using simulated fintech transaction data, the detection and optimisation logic is directly applicable to cryptocurrency transaction monitoring environments.

In traditional systems, monitoring focuses on customer accounts and transaction activity. In crypto environments, this shifts toward wallet-level behaviour, transaction flows across addresses, and network-based movement of funds.

The same core financial crime patterns apply — including transaction velocity, structuring, and behavioural anomalies — but are expressed through rapid fund movement, multi-hop transfers across wallets, and interconnected transaction paths.

This project demonstrates how rule-based detection can be enhanced with machine learning to refine alert quality, reduce false positives, and improve prioritisation — capabilities that are critical in high-volume crypto environments where transaction speed and scale significantly increase noise within monitoring systems.

From a rule tuning perspective, this approach supports more precise threshold calibration and dynamic alert optimisation, enabling detection systems to maintain sensitivity to suspicious behaviour while reducing unnecessary investigation workload.

---

🎯 Key Takeaway

This project demonstrates how transaction monitoring systems can evolve from static rules-based detection into hybrid rule + machine learning frameworks that improve precision, reduce false positives, and enhance operational efficiency.

The core focus is on improving signal quality — ensuring that alerts generated are both meaningful and actionable — which is essential in scaling transaction monitoring systems across both traditional financial and cryptocurrency environments.

---

## 👤 Author
Farzean Hassim
