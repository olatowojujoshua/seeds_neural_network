# Wheat Seeds Classification – Artificial Neural Network (ANN)

This project builds and evaluates a feed-forward Artificial Neural Network (ANN) to classify wheat seeds into three varieties using the UCI Seeds Dataset.

## 📘 Project Overview
- 210 samples  
- 7 numeric features  
- 3-class classification  
- Neural network with two hidden layers  
- Hyperparameter comparison (16 vs 64 units)

## 🔧 Methods
- Data preprocessing:
  - Train/test split (80/20)
  - Standardization (StandardScaler)
- ANN architecture:
  - ReLU activation
  - Dropout regularization (0.3)
  - Softmax output
  - Adam optimizer (lr = 0.001)
- Training:
  - 50 epochs
  - Batch size 16
  - Validation split 0.2

## 📊 Results
- Model A: 16 units (Small Network)
- Model B: 64 units (Large Network)
- Evaluated using accuracy / precision / recall / F1-score
- Confusion matrix plotted for best-performing model

## 📁 Repository Structure

