# Fraud Detection System

## Overview
Machine learning system for detecting fraudulent financial transactions in real-time. Processes 6M+ records with 93% recall and <0.1% false positive rate.

## Key Features
- Real-time scoring (<100ms/transaction)
- XGBoost/LightGBM/Random Forest ensemble
- Behavioral feature engineering:
  - Account emptying patterns
  - Transaction velocity
  - Unusual time windows
- Production-ready Flask API

## Installation
```bash
git clone https://github.com/yourusername/fraud-detection.git
cd fraud-detection
pip install -r requirements.txt
