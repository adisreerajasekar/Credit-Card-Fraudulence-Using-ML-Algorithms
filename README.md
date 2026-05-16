# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques on a highly imbalanced dataset. The workflow includes data preprocessing, exploratory data analysis (EDA), feature scaling, handling class imbalance, model training, and performance evaluation.

The objective of this project is to accurately identify fraudulent transactions while minimizing false positives.

---

## Dataset
Dataset used:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Information
- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Normal Transactions: 284,315
- Fraud Percentage: 0.172%

### Features
- `Time` – Time elapsed between transactions
- `V1` to `V28` – PCA transformed numerical features
- `Amount` – Transaction amount
- `Class` – Target variable
  - `0` → Legitimate Transaction
  - `1` → Fraudulent Transaction

---

## Project Objectives
- Perform Exploratory Data Analysis (EDA)
- Analyze transaction patterns
- Handle imbalanced data
- Train fraud detection models
- Evaluate model performance using classification metrics

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```text
credit-card-fraud-detection/
│
├── data/
│   └── creditcard.csv
│
├── Credit Card Fraudulence.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

## Data Preprocessing
The following preprocessing techniques were applied:
- Checking missing values
- Feature scaling
- Train-test splitting
- Handling imbalanced classes
- Data visualization and correlation analysis

---

## Exploratory Data Analysis
EDA techniques used in the project include:
- Fraud vs Normal transaction comparison
- Correlation heatmaps
- Distribution plots
- Transaction amount analysis
- Class imbalance visualization

---

## Machine Learning Models
The project includes implementation and evaluation of fraud detection models such as:
- Logistic Regression
- Random Forest
- Decision Tree
- Other classification techniques

---

## Evaluation Metrics
Since the dataset is highly imbalanced, multiple evaluation metrics were used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

## Results
The models were evaluated based on their ability to correctly identify fraudulent transactions. Performance comparison was carried out using classification metrics and confusion matrix analysis.

---

## License
This project is for educational and research purposes.
