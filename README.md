# Credit_Card_Fraud_Detection

#Overview
This project focuses on detecting credit card fraud using a Logistic Regression Classifier. It employs techniques like SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance and fine-tuning through Grid Search to optimize model performance. The resulting model achieved a ROC-AUC curve value of approximately 0.982, indicating strong predictive power.

#Project Structure
credit_card_fraud_detection.ipynb: Jupyter Notebook containing the complete code and analysis of the project.
data/: Directory to store the dataset used for training and testing the model.
README.md: This document, providing an overview and instructions for the project.

#Prerequisites

Before running the code in credit_card_fraud_detection.ipynb, make sure you have the following dependencies installed:

Python (recommended version: 3.x)
Jupyter Notebook
Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

You can install the required Python libraries using pip:

pip install scikit-learn pandas numpy matplotlib seaborn

#Usage
i).Clone this repository to your local machine:
    git clone https://github.com/yourusername/credit-card-fraud-detection.git
ii).Navigate to the project directory:
    cd credit-card-fraud-detection
iii).Open and run the Jupyter Notebook credit_card_fraud_detection.ipynb:
     jupyter notebook credit_card_fraud_detection.ipynb

Follow the instructions and code within the notebook to reproduce the analysis, build the Logistic Regression Classifier, apply the SMOTE technique, and fine-tune the model using Grid Search.

#Dataset
The dataset used for this project can be found in the data/ directory. Ensure that you have the dataset file (creditcard.csv) available before running the notebook.

#Results
The model achieved an impressive ROC-AUC curve value of approximately 0.982, indicating its effectiveness in detecting credit card fraud.
