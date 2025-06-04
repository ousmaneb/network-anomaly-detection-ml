# Network Anomaly Detection Using Machine Learning

This repository contains all source code, datasets, and evaluation scripts used in the dissertation titled:

> **"Enhanced Network Anomaly Detection Using Machine Learning Models"**

## Overview
The goal of this project is to evaluate various machine learning models for network anomaly detection using the NSL-KDD dataset. The experiments include:

- Binary classification (Normal vs. Attack)
- Multiclass classification (Identifying specific types of attacks)
- Evaluation with and without SMOTE-ENN resampling for handling class imbalance
- Neural network implementation for comparison
- Execution time analysis for model performance

## Files Included
- `enhanced-nids-ml.ipynb`: Core implementation notebook with model training, evaluation, and metrics output
- `execution-time-graph.ipynb`: Script to visualize and compare model execution times
- `KDDTrain+.csv` & `KDDTest+.csv`: NSL-KDD dataset files

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- LightGBM
- CatBoost
- Custom Neural Network (Keras/TensorFlow)

## Features
- Detailed classification reports with precision, recall, F1-score (4 decimal places)
- Compact confusion matrix tables
- Execution time comparison across all models

## Environment
All experiments were run in **Google Colab** with the following key dependencies:
- `scikit-learn`
- `imbalanced-learn`
- `catboost`, `lightgbm`, `xgboost`
- `tensorflow`

## Citation
If you use this code in your research, please cite the following:

> Ousmane, B. (2025). *Network anomaly detection using machine learning models* [Source code]. GitHub. https://github.com/ousmaneb/network-anomaly-detection-ml

## License
This codebase is released for academic and research purposes only. Commercial use, redistribution, or modification of the code outside the scope of scholarly work is prohibited without explicit written permission from the author.
If you are interested in reusing or extending this work for non-academic purposes, please contact the author directly.

---
Feel free to open an issue or pull request if you have suggestions or improvements.

