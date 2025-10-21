# Breast Cancer Classification using K-Nearest Neighbors (KNN)

A machine learning project that uses K-Nearest Neighbors algorithm to classify breast cancer tumors as **benign** or **malignant** with **96.5% accuracy**.

## 📋 Project Overview

This project demonstrates how simple, interpretable machine learning models can provide meaningful insights in healthcare. Built to highlight the importance of early detection and AI's potential role in medical diagnostics, this classifier achieves excellent performance using the KNN algorithm.

## 🎯 Results

- **Accuracy**: 96.5%
- **Misclassifications**: Only 4 out of 114 test cases
- **Precision**: 97% (Benign), 96% (Malignant)
- **Recall**: 92% (Benign), 99% (Malignant)
- **F1-Score**: 95% (Benign), 97% (Malignant)

## 📊 Dataset

- **Source**: [Breast Cancer Classification Dataset on Kaggle](https://www.kaggle.com/datasets/sahilnbajaj/cancer-classification/code)
- **Samples**: 569 instances
- **Features**: 30 medical features (mean radius, texture, perimeter, area, etc.)
- **Target**: Binary classification (0 = Benign, 1 = Malignant)

## 🛠️ Technical Implementation

### Algorithms & Tools
- **Algorithm**: K-Nearest Neighbors (KNN)
- **Libraries**: scikit-learn, pandas, numpy, matplotlib, seaborn
- **Preprocessing**: StandardScaler for feature normalization
- **Evaluation**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

### Model Configuration
- **n_neighbors**: 5
- **Train/Test Split**: 80/20 with random_state=44
- **Feature Scaling**: StandardScaler applied to all features


