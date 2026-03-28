# Credit Card Fraud Detection Project

This is a Machine Learning project focused on detecting fraudulent credit card transactions using real-world data. The project covers the complete pipeline from data preprocessing to model training and evaluation.

## Kaggle Notebook
The full notebook with code, visualizations, and results can be viewed here:  
https://www.kaggle.com/code/alishbayousaf1100/credit-card-fraud-detection

## Files in this Repository
- Credit_Card_Fraud_Detection.ipynb → Data preprocessing and EDA  
- Credit_Card_Fraud_Detection_Feature_Engineering.ipynb → Feature engineering  
- Credit_Card_Fraud_Detection_Complete_Notebook.ipynb → Model training, evaluation, and results  

## Project Steps

### Data Visualization and Statistical Analysis
Understanding distributions, missing values, and feature relationships  

### Data Preprocessing
Handling missing values, feature scaling, and cleaning  

### Feature Engineering
Creating new features such as Hour, Log_Amount, and High_Amount  

### Model Training and Evaluation
Training LightGBM model and evaluating using accuracy, precision, recall, and F1-score  

### Handling Class Imbalance
Applied SMOTE to balance the dataset and improve fraud detection  

### Risk Scoring
Generated probability-based risk scores to prioritize suspicious transactions  

## Key Results
- High overall accuracy achieved  
- Fraud detection recall significantly improved after applying SMOTE  
- Model effectively identifies fraudulent transactions  

## How to Run
- Open the notebook in Jupyter Notebook or Kaggle  
- Run all cells step by step to reproduce results  

## Requirements
Python libraries required:  
pandas, numpy, matplotlib, seaborn, scikit-learn, lightgbm, imbalanced-learn  

## Conclusion
This project demonstrates a complete machine learning pipeline for fraud detection. Handling class imbalance using SMOTE significantly improved the model’s ability to detect fraudulent transactions. The final model can also generate risk scores to assist in real-world decision-making.
