# meachine-learning-and-neural-networks
Credit Card Fraud Detection using Autoencoders

 Overview
This project demonstrates how autoencoders can be used for anomaly detection in highly imbalanced datasets.
Clustering is an unsupervised machine learning technique used to group similar data points without prior labels. It helps uncover hidden patterns in data.
This project applies K-Means clustering to a credit card dataset to identify distinct customer segments based on their financial behaviour. The goal is to support business decision-making such as targeted marketing and risk management.
In this tutorial K-Means clustering is applied to a credit card dataset containing information about customer transactions, balances, and payment behaviour. The aim is to uncover underlying patterns in customer activity and group individuals into meaningful segments. These segments can then be used to support data-driven decision-making, such as identifying high-value customers, detecting low-engagement users, and improving risk assessment strategies.

Contents
•	notebook.ipynb – full implementation
•	report.pdf – tutorial write-up
•	requirements.txt – dependencies
 How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Run the notebook:
   jupyter notebook
Dataset
Credit Card Fraud Detection Dataset (Kaggle)
Method
- Train autoencoder on normal transactions
- Compute reconstruction error
- Detect anomalies using threshold
Results
Autoencoders successfully separate normal and fraudulent transactions using reconstruction error.

