# Credit Card Fraud Detection

## Submitted by: sumala Vidya Sagar   
**College:** Rajiv Gandhi University Of Knowledge And Technologies-Nuzvid  


## Problem Statement

To predict fraudulent credit card transactions using machine learning models.

This project analyzes real-world customer-level data collected during a research collaboration between Worldline and the Machine Learning Group.


##  Business Problem Overview

Banks face major financial and reputational risks due to fraud. With digital transactions rising, detecting fraud through machine learning is critical to prevent losses, reduce manual reviews, and improve customer trust.

## Dataset

- Total Transactions: 284,807
- Fraudulent: 492 (~0.17%)
- Features: V1 to V28 (PCA-transformed), Time, Amount
- Class: `1 = Fraud`, `0 = Genuine`

Source: [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## Project Pipeline

1. Data Understanding
2. EDA (Exploratory Data Analysis)
3. Train-Test Split & Sampling
4. Model Building & Hyperparameter Tuning
5. Model Evaluation with Confusion Matrix, ROC-AUC, Precision, Recall


##  Evaluation

Since the dataset is imbalanced, **recall and precision** are more important than accuracy. The best-performing model accurately identifies most fraudulent transactions.

---

##  Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (ML Models)



##  Conclusion

This project shows how machine learning can help financial institutions identify fraud and reduce risks effectively.



## Files Included

- `Sagar_Credit_Card_Fraud_Detection.ipynb` – The main project notebook
- `dataset.csv` – The anonymized transaction dataset
