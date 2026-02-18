# 📊 Telecom Churn Model Monitoring & Drift Detection

## 🚀 Project Overview

This project builds a Telecom Churn prediction model and extends it into a production-style monitoring system to detect data drift and performance degradation.

Most machine learning projects stop after model training. This project demonstrates full model lifecycle thinking.

---

## ⚙️ Tech Stack

- Python
- Pandas
- Scikit-learn
- SciPy
- Matplotlib

---

## 📈 Phase 1: Model Development

- Data cleaning and preprocessing  
- Categorical encoding  
- Train-test split  
- Random Forest model training  
- Baseline performance evaluation  

**Baseline Performance:**
- Accuracy: 78.6%
- F1 Score: 0.57

---

## 🔄 Phase 2: Drift Simulation

To simulate real-world production scenarios, distribution shifts were introduced in:

- Tenure Months  
- Monthly Charges  

This mimics pricing changes and evolving customer behavior.

---

## 📉 Phase 3: Performance Monitoring

After drift simulation:

- Accuracy changed  
- Misclassification rate increased to 22%

This demonstrates silent model degradation under distribution shift.

---

## 📊 Phase 4: Statistical Drift Detection

Applied Kolmogorov–Smirnov (KS) Test:

- P-value: 0.0  
- Significant Data Drift Detected  

This confirms statistically significant distribution change.

---

## 🎯 Key Learnings

- ML models are sensitive to data drift  
- Monitoring is as critical as training  
- Statistical validation improves reliability  
- Production ML requires lifecycle thinking  

---

## 🧠 Conclusion

Production machine learning is not just about building models —  
it requires continuous monitoring, validation, and maintenance.
