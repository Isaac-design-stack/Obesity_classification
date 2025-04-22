# Obesity_classification

# Obesity Classification using Decision Tree and Logistic Regression 🧠🍔

This project predicts obesity categories (e.g., Underweight, Normal, Overweight, Obese) based on biometric and demographic data such as age, height, weight, BMI, and gender. It includes data preprocessing, outlier and imbalance treatment, model training, evaluation, and pruning techniques.

## 📁 Project Structure
Obesity_Classification/ 
├── Obesity_classification.ipynb 
# Jupyter notebook with full ML workflow 
├── obesity_data.csv 
# Dataset  
├── requirements.txt 
# Project dependencies 
└── README.md 
# Project description and usage


## 📊 Problem Statement

The goal is to classify individuals into different obesity categories based on various health indicators using supervised machine learning models.

## 🚀 Key Features

- ✅ Data preprocessing and cleaning
- ✅ Outlier detection and treatment (IQR method)
- ✅ Handling class imbalance with oversampling
- ✅ Feature encoding and transformation
- ✅ Decision Tree (Gini & Entropy) and Logistic Regression models
- ✅ Model evaluation (confusion matrix, accuracy, F1-score)
- ✅ Cross-validation (K-Fold)
- ✅ Post-pruning of decision trees

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn & Matplotlib
- imbalanced-learn

## 📦 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/Obesity_Classification.git
cd Obesity_Classification

📈 Results Summary

Model	Train Accuracy	Test Accuracy	Cross-Validation Accuracy
Decision Tree (Gini)	100%	100%	~98.6%
Decision Tree (Entropy)	100%	100%	~98.6%
Pruned Tree	~100%	~98%	N/A
Logistic Regression	~79%	~91%	N/A
📉 Dataset Info
Total rows: 108

Features: Age, Gender, Height, Weight, BMI

Target: Obesity classification (Underweight, Normal, Overweight, Obese)

📌 Labels Mapping

Label	Encoded
Normal Weight	0
Obese	1
Overweight	2
Underweight	3
📊 Visualizations
Pairplots, heatmaps, boxplots

Feature importance charts

Decision tree diagrams
