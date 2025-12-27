# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning. The analysis and model development were done using Python in Visual Studio Code.
The goal is to explore transaction data, handle class imbalance, and train models that can correctly identify fraudulent activity.

---

## About the Project

Credit card fraud detection is a real-world classification problem where fraudulent transactions make up a very small portion of the data. This makes the task challenging, as models must detect fraud without incorrectly flagging too many legitimate transactions.
In this project, I analyze the dataset, preprocess the data, train machine learning models, and evaluate their performance using standard classification metrics.

---
## What’s Included

- Data exploration and understanding the dataset  
- Data preprocessing and feature scaling  
- Handling imbalanced data  
- Training machine learning models  
- Evaluating models using accuracy, precision, recall, and F1-score  

All of the work is implemented in a single Python workflow and executed in Visual Studio Code.

---
## Tech Used

- Python  
- Visual Studio Code  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
---
## Project Structure

```text
credit-card-fraud-detection/
├── credit_card_fraud_detection.ipynb
└── README.md
---

## Results and Observation

The trained models were evaluated using metrics such as accuracy, precision, recall, and F1-score. Because fraudulent transactions represent only a small portion of the dataset, special attention was given to recall and precision rather than accuracy alone.
The results highlight how important it is to handle class imbalance when working on fraud detection problems, as a model with high accuracy can still perform poorly at identifying fraudulent cases.
---
