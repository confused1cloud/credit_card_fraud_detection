# Credit Card Fraud Detection System

## Overview
Real-time fraud detection system for credit card transactions using machine learning.

## Results
- **Recall**: 87%
- **Precision**: 53%
- **Best model**: XGBoost with class weights

## Models Tested
- XGBoost (class weights) → 87% recall
- Isolation Forest → 60% recall
- Autoencoder → 60% recall

## Tech Stack
- Python (XGBoost, Scikit-learn, TensorFlow)
- FastAPI for deployment
- Pandas, NumPy

## Key Challenges
- Extreme class imbalance (0.17% fraud)
- Real-time prediction requirements

## Files
- `fraud_detection.ipynb` - Complete code
- `app.py` - FastAPI deployment

## How to Run
1. Open notebook in Google Colab
2. Run all cells
3. Model trains and evaluates
