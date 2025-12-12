# Telco Customer Churn Prediction

A binary classification project comparing Neural Network and Decision Tree models for predicting customer churn in telecommunications.

## 📋 Project Overview

This project implements and compares two machine learning approaches to predict whether a customer will churn (cancel their subscription) based on various customer attributes from the Telco Customer Churn dataset.

**Models Implemented:**
- Neural Network (Multi-layer Perceptron)
- Decision Tree Classifier

## 📁 Project Structure

```
telco-churn-prediction/
├── data/                   # Dataset files
│   ├── raw/               # Original dataset
│   └── processed/         # Preprocessed data
├── notebooks/             # Jupyter notebooks
│   ├── 01_eda.ipynb      # Exploratory Data Analysis
│   ├── 02_preprocessing.ipynb
│   ├── 03_decision_tree.ipynb
│   └── 04_neural_network.ipynb
├── src/                   # Source code
│   ├── preprocessing.py   # Data preprocessing functions
│   ├── models.py         # Model implementations
│   └── evaluation.py     # Evaluation metrics
├── models/               # Saved model files
├── figures/              # Generated visualizations
├── reports/              # Final report
└── requirements.txt      # Dependencies
```

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/telco-churn-prediction.git
cd telco-churn-prediction

# Install dependencies
pip install -r requirements.txt
```

## 📊 Dataset

The [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) dataset contains information about:
- Customer demographics (gender, senior citizen, partner, dependents)
- Account information (tenure, contract type, payment method)
- Services subscribed (phone, internet, streaming, etc.)
- Charges (monthly and total)
- Target variable: Churn (Yes/No)

## 🔬 Methodology

### Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test split

### Model Training
- Hyperparameter tuning using GridSearchCV
- Cross-validation for robust evaluation

### Evaluation Metrics
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix



## 👤 Author

Thisumi Ranasinghe
BSc (Hons) Artificial Intelligence and Data Science  
Informatics Institute of Technology, Sri Lanka  
Robert Gordon University

## 📄 License

This project is for academic purposes - CM2604 Machine Learning Coursework.
