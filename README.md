# Credit Card Default Prediction 💳

A comprehensive machine learning project that predicts credit card payment defaults to help financial institutions identify high-risk customers and minimize potential losses.

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Machine Learning](https://img.shields.io/badge/ML-Classification-green.svg)](https://scikit-learn.org/)

## 📋 Overview

This project implements and compares multiple machine learning algorithms to predict whether a credit card customer will default on their next payment. By analyzing historical payment data, demographic information, and credit history, the models help financial institutions make informed decisions about credit risk management.

## 🔗 Resources

- **Research Paper**: [credit card default.pdf](https://github.com/sajinamatya/Credit-card-default-prediction-/blob/main/credit%20card%20default.pdf)

## 🎯 Project Objectives

- Predict credit card payment defaults with high accuracy
- Compare performance across multiple ML algorithms
- Identify key features that contribute to default risk
- Provide actionable insights for credit risk management

## 🤖 Machine Learning Algorithms

This project implements and evaluates four different classification algorithms:

1. **Logistic Regression** - Baseline linear model for binary classification
2. **Support Vector Machine (SVM)** - Kernel-based classifier for complex decision boundaries
3. **Random Forest** - Ensemble of decision trees for robust predictions
4. **Ensemble Learning** - Combined model leveraging strengths of multiple algorithms

## 📊 Model Performance Comparison

The following chart shows a comprehensive performance comparison across all implemented models:

<img width="767" height="269" alt="Model Performance Comparison" src="https://github.com/user-attachments/assets/266719d6-5aa9-46bc-9655-2b65fa0a00aa" />

## 🔄 System Architecture

The complete workflow of the prediction system from data ingestion to model deployment:

<img width="499" height="652" alt="System Flow Chart" src="https://github.com/user-attachments/assets/ffc9c961-b02c-4025-8245-73331dd215ed" />

## 📁 Project Structure

```
Credit-card-default-prediction-/
├── notebooks/              # Jupyter notebooks with analysis
├── data/                   # Dataset files
├── models/                 # Trained model files
├── src/                    # Source code
├── credit card default.pdf # Research paper
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.x
Jupyter Notebook
Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sajinamatya/Credit-card-default-prediction-.git
cd Credit-card-default-prediction-
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## 📈 Features Used

The model analyzes various customer attributes including:

- **Demographic Information**: Age, gender, education level, marital status
- **Credit Data**: Credit limit, bill amounts, payment history
- **Payment Behavior**: Past payment records, payment delays
- **Financial Indicators**: Balance amounts, payment amounts over time

## 🔍 Model Evaluation Metrics

Models are evaluated using:

- **Accuracy**: Overall prediction correctness
- **Precision**: Reliability of positive predictions
- **Recall**: Ability to identify actual defaults
- **F1-Score**: Harmonic mean of precision and recall
- **ROC-AUC**: Model's discrimination capability

## 💡 Key Insights

- Historical payment behavior is the strongest predictor of default
- Ensemble methods generally provide better generalization
- Feature engineering significantly impacts model performance
- Class imbalance handling improves model reliability


## 📧 Contact

**Sajin Amatya** - [@sajinamatya](https://github.com/sajinamatya)

Project Link: [https://github.com/sajinamatya/Credit-card-default-prediction-](https://github.com/sajinamatya/Credit-card-default-prediction-)

## 📝 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Dataset providers and research community
- Open-source ML libraries and tools
- Contributors and collaborators

---

⭐ If you find this project helpful, please consider giving it a star!
