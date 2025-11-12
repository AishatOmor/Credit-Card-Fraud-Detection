# Credit-Card-Fraud-Detection
Credit Card Fraud Detection  This repository contains a Python project for detecting fraudulent credit card transactions using Logistic Regression and SMOTE to handle class imbalance. The project includes data exploration, preprocessing, model training, and evaluation.

# Dataset

The dataset contains anonymized credit card transactions.

Target variable: Class → 0 = legitimate transaction, 1 = fraud

# Features:
Time – seconds elapsed between this transaction and the first transaction in the dataset
V1 to V28 – anonymized features from PCA
Amount – transaction amount
Class – target variable

Download the dataset https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data
# Libraries used: 
<img width="977" height="261" alt="image" src="https://github.com/user-attachments/assets/5149f868-5755-4c0d-875f-08cb14c7dac4" />

# Load and Explore Data
<img width="530" height="63" alt="image" src="https://github.com/user-attachments/assets/09db4c5a-0581-4d59-8782-25f82608910e" />
<img width="763" height="58" alt="image" src="https://github.com/user-attachments/assets/06f63740-b59d-482a-a6f2-95147e0abb38" />
<img width="579" height="77" alt="image" src="https://github.com/user-attachments/assets/86529f6f-4783-4ad2-94e5-1083509f4af1" />

# Exploratory Data Analysis
<img width="464" height="73" alt="image" src="https://github.com/user-attachments/assets/b655cc12-7937-49df-9910-08a249febe5b" />
<img width="687" height="121" alt="image" src="https://github.com/user-attachments/assets/e4ae9210-aaa8-4ac2-9e69-bfa50569d77a" />

# Preprocessing and Model Training
<img width="829" height="738" alt="image" src="https://github.com/user-attachments/assets/8f050352-b740-4305-9bf0-5474df1347f8" />

# Model Evaluation and Interpretation
<img width="568" height="91" alt="image" src="https://github.com/user-attachments/assets/e3d573dd-6c26-41a7-b00e-ddd9a99ed29d" />
<img width="468" height="116" alt="image" src="https://github.com/user-attachments/assets/7a70f1c1-2ffe-4a72-8063-2720c2fb99b7" />
<img width="577" height="70" alt="image" src="https://github.com/user-attachments/assets/2f86ff76-b4de-4bb8-b220-bf9d534b36a1" />

Example Result:

<img width="527" height="200" alt="image" src="https://github.com/user-attachments/assets/fe00e3b6-b8c0-4203-96f0-42134d74c62b" />
<img width="783" height="559" alt="image" src="https://github.com/user-attachments/assets/a2f7d375-76b8-4439-833b-ccc540ef559e" />
<img width="598" height="220" alt="image" src="https://github.com/user-attachments/assets/aa741e22-b7b6-4f40-9bbc-db1ef5d77385" />



# Interpretation:

-- The model performs well on non-fraud transactions.

-- Fraud detection cannot be assessed because the test set contains no fraud cases.

-- High accuracy is misleading → it does not reflect the model’s ability to detect fraud.

# Key Insights & Recommendations

-- Class imbalance matters: SMOTE helps the model learn from rare fraud cases.

-- Test set should contain fraud transactions to properly evaluate model performance.

# Metrics to focus on for fraud detection:

Precision, Recall, F1-score for fraud

ROC-AUC or Precision-Recall AUC

Logistic Regression is a good baseline. For better detection, try:

Random Forest

XGBoost

Neural Networks

# Takeaways

-- High accuracy can be misleading in imbalanced datasets.

-- Proper evaluation of fraud detection requires fraud examples in the test set.

-- Oversampling techniques (like SMOTE) improve model learning for rare classes.









