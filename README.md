<div align="center">

# [ PHISHGUARD ML ]

### AI-Powered Phishing Threat Intelligence Platform

```text
> Initializing Threat Detection Engine...
> Loading Machine Learning Models...
> Real-Time URL Analysis Module Active...
```

![Python](https://img.shields.io/badge/Python-111111?style=flat-square&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-111111?style=flat-square&logo=fastapi)
![React](https://img.shields.io/badge/React-111111?style=flat-square&logo=react)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-111111?style=flat-square)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Threat%20Detection-111111?style=flat-square)

</div>

---

```text
═══════════════════════════════════════════════════════
[ STATUS ] THREAT ANALYSIS CORE : ACTIVE
[ STATUS ] ENSEMBLE ML ENGINE   : ONLINE
[ STATUS ] URL CLASSIFIER       : RUNNING
═══════════════════════════════════════════════════════
```

# System Overview

PhishGuard ML is a machine learning-based cybersecurity platform developed to identify phishing websites through intelligent URL analysis and behavioral threat classification.

The system evaluates suspicious websites using multiple security-oriented indicators including:

- SSL certificate integrity
- URL structure anomalies
- Domain manipulation patterns
- Anchor behavior analysis
- Website traffic metrics
- Redirection characteristics

Unlike traditional blacklist-based systems, PhishGuard ML focuses on predictive threat intelligence, enabling the detection of previously unseen phishing attacks through machine learning-driven analysis.

---

# Threat Intelligence Pipeline

```text
[ Suspicious URL ]
         ↓
[ Feature Extraction Engine ]
         ↓
[ Behavioral Threat Analysis ]
         ↓
[ Machine Learning Classification ]
         ↓
[ SAFE / SUSPICIOUS / PHISHING ]
```

---

# Detection Infrastructure

## Real-Time Threat Analysis

The platform performs real-time phishing detection by extracting and analyzing multiple security-related website features from user-submitted URLs.

---

## Multi-Model Security Architecture

Several machine learning models were trained and evaluated throughout the project development lifecycle:

- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Artificial Neural Networks (ANN)
- Extra Trees Classifier
- Stacking Ensemble

Ensemble learning methods were integrated to improve classification consistency and threat detection accuracy.

---

## Threat Logging & Intelligence Expansion

Prediction results and analyzed URLs are continuously stored to support:

- phishing pattern analysis,
- dataset expansion,
- retraining operations,
- model optimization,
- and long-term cybersecurity research.

This enables the platform to evolve against emerging phishing techniques and adaptive attack behaviors.

---

# Model Evaluation

| Model | Accuracy | F1 Score | ROC-AUC |
|---|---|---|---|
| Stacking Ensemble | 97.60% | 97.86% | 99.80% |
| Extra Trees | 97.60% | 97.86% | 99.46% |
| Random Forest | 97.38% | 97.66% | 99.78% |

---

# Security-Critical Features

| Feature | Security Function |
|---|---|
| SSLfinal_State | SSL / HTTPS certificate verification |
| URL_of_Anchor | Suspicious anchor behavior detection |
| Web Traffic | Website trust and popularity analysis |

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

# Threat Analysis Workflow

1. User submits a suspicious URL
2. Security-related features are extracted
3. Machine learning models perform threat evaluation
4. The system classifies the target as:

```text
[ SAFE ]
[ SUSPICIOUS ]
[ PHISHING ]
```

---

# Project Objectives

PhishGuard ML was developed to:

- improve cybersecurity awareness,
- strengthen phishing detection systems,
- research AI-driven threat analysis,
- and explore scalable machine learning-based security solutions.

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
═══════════════════════════════════════════════════════
[ DISCLAIMER ]

This project was developed for academic and educational
purposes. Additional security layers, continuous monitoring,
and periodic model retraining are recommended for production
environments.

═══════════════════════════════════════════════════════
```

# License

This repository is shared for educational and academic use.
