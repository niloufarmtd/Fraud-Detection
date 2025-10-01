# Fraud-Detection
A comprehensive machine learning pipeline for detecting fraudulent transactions using various classification algorithms.

This Jupyter notebook demonstrates a comprehensive fraud detection analysis using machine learning. It includes data exploration, preprocessing, and model comparison with LazyPredict. The LightGBM and XGBoost models show high accuracy, providing insights into identifying fraudulent transactions effectively.

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![License](https://img.shields.io/badge/License-MIT-green)

##  Overview

This project implements a fraud detection system using machine learning techniques. The notebook includes complete data analysis, preprocessing, feature engineering, and model comparison using LazyPredict to identify the best-performing algorithm for fraud detection.

##  Features

- **Data Exploration**: Comprehensive EDA with statistical analysis and missing value detection
- **Preprocessing**: Data cleaning and preparation for machine learning
- **Model Comparison**: Automated model evaluation using LazyPredict
- **Multiple Algorithms**: Tests 26+ different classifiers including:
  - LightGBM
  - XGBoost
  - Random Forest
  - Logistic Regression
  - Neural Networks
- **Performance Metrics**: Accuracy, Balanced Accuracy, ROC AUC, F1 Score

##  Results

The model comparison revealed top performers:

| Model | Accuracy | Balanced Accuracy | ROC AUC | F1 Score |
|-------|----------|------------------|---------|----------|
| XGBClassifier | 95% | 0.65 | 0.65 | 0.94 |
| LGBMClassifier | 95% | 0.58 | 0.58 | 0.93 |
| QuadraticDiscriminantAnalysis | 85% | 0.65 | 0.65 | 0.87 |

##  Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/fraud-detection.git

# Navigate to directory
cd fraud-detection

# Install requirements
pip install -r requirements.txt
 Project Structure
text
fraud-detection/
├── fraud_detection.ipynb  # Main Jupyter notebook
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
└── data/                 # Dataset directory
## Usage
Open the Jupyter notebook:

bash
jupyter notebook fraud_detection.ipynb
Run cells sequentially to:

Load and explore the dataset

Preprocess the data

Train and compare multiple models

Evaluate performance metrics

## Dataset
The dataset contains 15,420 entries with 33 features including:

Transaction details (Month, WeekOfMonth, DayOfWeek)

Customer information (Age, Sex, MaritalStatus)

Policy details (PolicyType, VehicleCategory, Deductible)

Fraud indicator (FraudFound_P)

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

 License
This project is licensed under the MIT License - see the LICENSE file for details.

 Authors
Your Name - Your GitHub

 Acknowledgments
LazyPredict library for automated model comparison

LightGBM and XGBoost communities for excellent ML libraries
