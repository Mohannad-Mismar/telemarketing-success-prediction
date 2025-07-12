# Telemarketing Success Prediction
Predicting bank term deposit subscriptions using Random Forest + SMOTE ensemble model

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 📌 Overview
Implementation of an ensemble machine learning model from the research:
> [**Enhancing Telemarketing Success Using Ensemble-Based Online Machine Learning**](docs/Enhancing_Telemarketing_Success.pdf)  
> *Shahriar Kaisar et al., Big Data Mining and Analytics 2024*

## 🔍 Dataset
Portuguese Bank Marketing Dataset ([UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)):
- 45,211 telemarketing campaign records
- 16 customer/contact features
- Highly imbalanced (11.7% success rate)
- Target: Subscription to term deposit (`y`)

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/telemarketing-success-prediction.git
cd telemarketing-success-prediction
pip install -r requirements.txt
