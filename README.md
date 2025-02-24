# Credit Card Fraud Detection

## Overview

This project focuses on detecting fraudulent transactions in credit card data using machine learning techniques. The dataset consists of anonymized transaction features along with a class label indicating whether a transaction is fraudulent or not.

## Dataset

- **Source:** Kaggle Credit Card Fraud Detection dataset
- **Features:**
  - `Time`: Time elapsed since the first transaction
  - `V1` to `V28`: Anonymized numerical features obtained from PCA
  - `Amount`: Transaction amount (standardized)
  - `Class`: Target variable (0 = Normal, 1 = Fraudulent)

## Preprocessing Steps

1. Load the dataset and explore basic statistics.
2. Standardize `Amount` and `Time` columns.
3. Handle class imbalance using techniques like SMOTE.
4. Split data into training and test sets.

### Prerequisites

Ensure you have Python installed along with the required libraries:

```
pip install numpy pandas scikit-learn imbalanced-learn matplotlib seaborn xgboost
```

### Running the Script

1. Clone this repository:

```
git clone https://github.com/your-repo/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

2. Run the Jupyter Notebook or Python script:

```
python fraud_detection.py
```

## Future Work

- Implement deep learning models for improved accuracy.
- Explore feature engineering techniques.
- Deploy the model using Flask or FastAPI.

