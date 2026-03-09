# HbA1c Prediction from Retinal Fundus Images

This repository contains a multimodal deep learning framework for predicting HbA1c levels from retinal fundus images.

🏆 Best Paper Award – BIOCOM 2026

## Problem

HbA1c is a key biomarker for long-term glycemic control. However, traditional measurement requires invasive blood sampling.

This project explores a non-invasive method using retinal imaging and machine learning.

## Methodology

Pipeline:

1. Image preprocessing
2. Deep feature extraction using ResNet-18
3. Metadata fusion (age + gender)
4. Ridge Regression
5. Leave-One-Out Cross Validation

## Model Performance

MAE  : 0.92%  
RMSE : 1.28%  
R²   : 0.59  

## Technologies

- Python
- PyTorch
- OpenCV
- NumPy
- Scikit-learn

## Dataset

The dataset contains 26 retinal fundus images with corresponding demographic metadata and HbA1c values.

Due to patient privacy, the dataset cannot be shared publicly.

## Conference

BIOCOM 2026  
National Conference on Biomedical & Computing Technologies
