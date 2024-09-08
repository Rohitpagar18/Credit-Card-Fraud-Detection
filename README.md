# Credit Card Fraud Detection

## Introduction

Analysis of credit card transactions made by European cardholders in September 2013. The dataset includes 284,807 transactions, of which 492 (0.172%) are frauds. All features are numeric, most of which are principal components from PCA.

- **Features**:
  - `V1` to `V28`: PCA components.
  - `Time`: Seconds since the first transaction.
  - `Amount`: Transaction amount.
  - `Class`: 1 for fraud, 0 otherwise.

## Data Source

Collected by Worldline and the Machine Learning Group of ULB. [Learn more](https://www.researchgate.net/project/Fraud-detection-5).

## Model Performance

- **RandomForest**: AUC = **0.88**
- **AdaBoost**: AUC = **0.85**
- **CatBoost**: AUC = **0.89**
- **XGBoost**: Validation AUC = **0.977**, Test AUC = **0.973**

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook Fraud_Detection_EDA.ipynb
   ```
