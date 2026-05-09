<div align="center">

# PHISHGUARD ML

### Intelligent Phishing Threat Detection Platform

AI-powered cybersecurity system for phishing website analysis, malicious URL detection, and real-time threat classification.

<br>

![Python](https://img.shields.io/badge/Python-3.x-111111?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-111111?style=for-the-badge&logo=fastapi)
![React](https://img.shields.io/badge/React-Frontend-111111?style=for-the-badge&logo=react)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-111111?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Threat%20Detection-111111?style=for-the-badge)

</div>

---

```text
[ STATUS ] Threat Detection Engine Active
[ STATUS ] Machine Learning Models Loaded
[ STATUS ] Real-Time URL Analysis Enabled
```

---

# Overview

PhishGuard ML is a machine learning-based cybersecurity platform designed to detect phishing websites through intelligent URL analysis and behavioral threat classification.

The system evaluates suspicious websites using multiple security-oriented indicators including:

- SSL certificate validity
- URL structural anomalies
- Domain manipulation patterns
- Anchor behavior analysis
- Website traffic signals
- Redirection characteristics

Unlike traditional blacklist-based protection systems, PhishGuard ML focuses on predictive threat analysis, enabling the detection of previously unseen phishing attempts using machine learning-driven security intelligence.

---

# Threat Detection Pipeline

```text
[ User URL Input ]
          ↓
[ Feature Extraction ]
          ↓
[ Threat Intelligence Analysis ]
          ↓
[ Machine Learning Classification ]
          ↓
[ Safe / Suspicious / Phishing ]
```

---

# Core Capabilities

## Real-Time Threat Analysis

The platform performs instant phishing risk evaluation by extracting and analyzing security-related features from user-submitted URLs.

---

## Multi-Model Machine Learning Infrastructure

The system integrates multiple machine learning algorithms to maximize phishing detection performance:

- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Artificial Neural Networks (ANN)
- Extra Trees Classifier
- Stacking Ensemble

Ensemble learning techniques were utilized to improve classification consistency and overall threat detection reliability.

---

## Intelligent Threat Logging

Prediction results and analyzed URLs are continuously stored within a structured logging system to support:

- dataset expansion,
- retraining operations,
- phishing pattern analysis,
- long-term model optimization,
- and cybersecurity research workflows.

---

# Performance Evaluation

| Model | Accuracy | F1 Score | ROC-AUC |
|---|---|---|---|
| Stacking Ensemble | 97.60% | 97.86% | 99.80% |
| Extra Trees | 97.60% | 97.86% | 99.46% |
| Random Forest | 97.38% | 97.66% | 99.78% |

---

# Security-Critical Features

| Feature | Security Purpose |
|---|---|
| SSLfinal_State | SSL / HTTPS certificate validation |
| URL_of_Anchor | Detection of suspicious anchor behavior |
| Web Traffic | Website trust and popularity evaluation |

---

# System Architecture

## Backend Infrastructure
- FastAPI
- Python
- Uvicorn

## Frontend Infrastructure
- React
- Vite
- Tailwind CSS

## Machine Learning & Data Processing
- Scikit-learn
- Pandas
- NumPy
- XGBoost

---

# Project Structure

```plaintext
phishing_websitesi/
│
├── backend/                   # FastAPI backend services
├── frontend/                  # React frontend interface
├── Training Dataset.arff      # Main phishing dataset
├── train_models.py            # Model training pipeline
├── generate_report_figures.py # Security analysis visualizations
├── best_model.pkl             # Best trained ML model
├── metrics.json               # Model performance metrics
├── prediction_logs.csv        # Threat prediction logs
└── bilgi.md                   # Project documentation
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/ilydozttrk/PhishGuard-ML-Public.git
cd phishing_websitesi
```

---

## Backend Setup

```bash
cd backend

pip install -r requirements.txt

uvicorn main:app --reload
```

Backend service runs on:

```text
http://127.0.0.1:8000
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend service runs on:

```text
http://localhost:5173
```

---

# Threat Classification Workflow

1. User submits a suspicious URL
2. Security-related features are extracted
3. Machine learning models perform threat analysis
4. The system classifies the website as:

- SAFE
- SUSPICIOUS
- PHISHING

---

# Project Objectives

PhishGuard ML was developed to:

- strengthen cybersecurity awareness,
- improve phishing attack detection,
- explore AI-driven security systems,
- and research scalable machine learning-based threat analysis solutions.

---

# Academic Context

Developed within the scope of the  
Data Mining Course at  
Bitlis Eren University — Department of Computer Engineering.

---

# Development Team

| Name | GitHub |
|---|---|
| İlayda ÖZTÜRK | https://github.com/ilydozttrk |
| Semanur YILDIRIM | https://github.com/semanuryldrm |
| Şilan PEHLİVAN | https://github.com/silanpehlivan |

---

```text
[ DISCLAIMER ]
This project was developed for academic and educational purposes.
Additional security layers, continuous monitoring, and periodic
model retraining are recommended for production environments.
```

---

# License

This repository is shared for educational and academic use.
