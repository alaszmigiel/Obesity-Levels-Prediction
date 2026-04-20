# Obesity-Levels-Prediction

This project focuses on **predicting obesity levels** based on lifestyle, eating habits, and physical condition using machine learning.

## Overview
The goal of this project is to analyze factors influencing obesity and build a predictive model for multi-class classification.

The workflow includes:
- Data preprocessing and encoding
- Exploratory Data Analysis (EDA)
- Model training and evaluation

## Project Highlights
- Compared multiple machine learning models for multi-class classification
- Implemented both classical ML models and neural networks
- Applied feature engineering and encoding techniques
- Identified the best performing model (XGBoost)
  
## Dataset
The dataset includes demographic data, eating habits, and lifestyle features used to predict obesity levels.

## Models Used
- XGBoost
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- Neural Networks (RSNNS, nnet)

## Results

### Best Model
**XGBoost** achieved the best overall performance:
- Accuracy (test): **96.9%**
- Cross-validation accuracy: **97.0%**
- AUC: ~0.998  

### Model Comparison
- **Random Forest:** 95.95% accuracy, AUC: 0.999  
- **Decision Tree:** 92.38% accuracy  
- **SVM:** 81.67% accuracy

### Neural Networks
- **nnet:** 95% accuracy, Kappa: 0.9416  
- **RSNNS:** 94.29% accuracy, Kappa: 0.9333  

### Key Insight
Models struggled most with adjacent classes (Overweight Level I vs II), while obesity classes were classified with high accuracy.

## Installation & Usage

### 1. Clone the repository
```sh
git clone https://github.com/alaszmigiel/Obesity-Levels-Prediction.git
cd Obesity-Levels-Prediction
```
### 2. Open Jupyter Notebook
```sh
jupyter notebook
```
### 3. Open the file
```sh
Obesity_Levels_Prediction.ipynb
```
### 4. Run all cells
The notebook includes all required steps and installations if needed.

## Technologies Used
- **Language:** R  
- **Data Processing:** dplyr, tidyr  
- **Visualization:** ggplot2, corrplot  
- **ML:** caret, xgboost, kernlab  
- **Neural Networks:** RSNNS, nnet  
- **Evaluation:** pROC, MLmetrics  
