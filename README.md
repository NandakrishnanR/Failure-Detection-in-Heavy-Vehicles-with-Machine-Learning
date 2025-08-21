# 🚚 Failure Detection in Heavy Vehicles with Machine Learning

_A project by Nandakrishnan Rajeev, Portia Hungwe and Dr. Sunil Survaiiya (Deggendorf University of Technology, Germany)_
## 💡 Overview

This project is your **gateway to understanding how Artificial Intelligence can prevent costly vehicle breakdowns** — and make roads safer for everyone. We used real Scania truck sensor data to identify **failures in the Air Pressure System (APS)**, using state-of-the-art machine learning, including **Logistic Regression, XGBoost, and Bayesian modeling**. Our results? Stunning accuracy, huge savings in maintenance costs, and an intuitive web demo anyone can try!

---

## 🏆 Project Highlights

- **99.52% Accuracy** with XGBoost for failure detection — almost every critical failure is caught before disaster strikes!
- **User-friendly web interface** (even non-techies can predict truck failures).
- **Transparent, open source Python code** for all steps: cleaning, training, prediction, and model evaluation.
- Business impact: Prevents unnecessary repairs and catastrophic breakdowns, saving €€€ in maintenance and downtime.

---

## 🔍 The Problem

Modern heavy trucks are data-rich machines. One of the most critical systems — the Air Pressure System (APS) — is responsible for reliable brakes and gear shifting. If it fails unpredictably, it can cause:

- Dangerous road situations
- Expensive repairs and downtime
- Unhappy customers

**Goal:** Detect APS failures early with machine learning and help Scania Trucks focus maintenance where it matters most.

---

## 📊 Data and Features

- **Source:** Operational sensor data from Scania heavy trucks, focused on APS.
- **Samples:** ~40,000 for training, ~16,000 for testing.
- **Features:** 171 anonymized sensor parameters per vehicle.
- **Class balance:** Imbalanced (majority "no failure", minority "APS failure") — handled in preprocessing and modeling.

---

## 🛠️ Techniques Used

- **Data Cleaning & Normalization:** _Pandas, sklearn_ (handling missing values, encoding categories, scaling).
- **Logistic Regression:** For interpretable, explainable predictions.
- **XGBoost Classifier:** For complex patterns and boosting accuracy.
- **Bayesian Modeling:** For better risk quantification and uncertainty measurement.
- **Visualization:** ROC curves, confusion matrices, and classification reports.
- **Business Cost Matrix:** Explicit, practical mapping of prediction errors to real-world money.

---

## 🚦 Results At-A-Glance

| Model                | Accuracy | Class 0 Precision | Class 1 Precision | F1 Score (Macro) | ROC AUC |
|----------------------|----------|-------------------|-------------------|------------------|---------|
| **Logistic Regression** | 97.46%   | High              | Good              | ~0.96            | ~0.97   |
| **XGBoost**             | 99.52%   | 1.00              | 0.96              | 0.98             | >0.99   |

**Confusion matrix highlights:**

- **Logistic Regression:** Missed a few failures. Good overall, best for transparency.
- **XGBoost:** Caught (almost) all failures, minimal false alarms — the best performer!

---

## 👀 What Does This Mean for Real People?

- **Fleet Operators:** Focus mechanics’ time only where there’s real risk
- **Drivers:** Safer journeys with fewer breakdowns
- **Customers & Logistics Providers:** Higher on-time delivery, lower costs

