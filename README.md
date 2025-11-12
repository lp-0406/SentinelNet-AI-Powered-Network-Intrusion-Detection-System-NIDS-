
# 🛰️ SentinelNet – AI-Powered Network Intrusion Detection System (NIDS)

> 🚀 AI-driven system for real-time network intrusion detection using machine learning.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Machine Learning](https://img.shields.io/badge/ML-Supervised%20%7C%20Unsupervised-orange.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 📘 Overview
**SentinelNet** is an AI-powered **Network Intrusion Detection System (NIDS)** that automatically monitors and analyzes network traffic to detect suspicious or malicious behavior in real time.  
By leveraging **machine learning algorithms**, SentinelNet identifies potential threats, anomalies, and attacks — providing intelligent alerts and visual insights.

---

## 🎯 Objectives
- Detect and classify **network intrusions** using supervised and unsupervised learning.
- Reduce **false positives** through feature engineering and adaptive models.
- Enable **real-time traffic monitoring** with a user-friendly dashboard.
- Provide interpretable metrics and visual results for cybersecurity analysis.

---

## 🧠 Key Features
✅ Real-time intrusion detection  
✅ Multiple ML algorithms (Random Forest, SVM, K-Means, Isolation Forest)  
✅ Automatic data preprocessing & feature selection  
✅ Visualization of results with metrics and confusion matrix  
✅ Optional dashboard built using Streamlit  
✅ Scalable for IoT and enterprise network environments  

---

## 📊 Dataset
The system is trained and tested using publicly available intrusion detection datasets:

### 1. NSL-KDD Dataset
An enhanced version of KDD Cup 99 with improved class balance and reduced redundancy.  
Contains 41 features describing each network connection (e.g., duration, protocol type, bytes sent, service type, etc.)  
**Classes:** Normal | DoS | Probe | R2L | U2R  

### 2. CICIDS2017 Dataset
A modern dataset capturing real network traffic with various attack scenarios:  
**Attacks:** DDoS, Brute Force, Infiltration, Botnet, Web Attack, etc.  
Provides flow-level features such as packet counts, byte rates, and duration.

---

## ⚙️ Workflow
```mermaid
flowchart TD
    A[Dataset Collection] --> B[Data Cleaning & Encoding]
    B --> C[Feature Engineering]
    C --> D[Model Training]
    D --> E[Model Evaluation]
    E --> F[Real-Time Detection]
    F --> G[Dashboard & Alerts]
