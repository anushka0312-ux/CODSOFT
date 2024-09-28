# Credit Card Fraud Detection

This repository contains a machine learning project focused on detecting fraudulent credit card transactions. The objective is to classify transactions as legitimate or fraudulent based on patterns learned from historical data.

## Project Overview

Credit card fraud is a serious issue in the financial industry. This project aims to create a model that accurately identifies fraudulent transactions using various machine learning techniques. The dataset used for this project is highly imbalanced, with many more legitimate transactions than fraudulent ones.

## Features

- **Data Preprocessing**: Handle missing values, scale features, and balance the dataset.
- **Exploratory Data Analysis**: Visualize and understand data distribution, correlations, and patterns.
- **Model Training**: Train multiple machine learning models like Logistic Regression, Decision Trees, Random Forest, and XGBoost.
- **Model Evaluation**: Evaluate models using metrics such as Accuracy, Precision, Recall, F1-Score, and AUC-ROC curve.
- **Hyperparameter Tuning**: Optimize model performance using techniques like Grid Search or Random Search.

## Dataset

The dataset used is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains 284,807 transactions, with 492 fraud cases. The data is highly imbalanced, making evaluation metrics like Precision and Recall critical for this problem.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Preprocess the data by running:
   ```bash
   python preprocess.py
   ```
2. Train the model by running:
   ```bash
   python train.py
   ```
3. Evaluate the model by running:
   ```bash
   python evaluate.py
   ```

## Results

- **Accuracy**: 99.8%
- **Precision**: 91.5%
- **Recall**: 93.4%
- **F1-Score**: 92.4%
- **AUC-ROC Score**: 0.98


