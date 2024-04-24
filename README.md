# DetectingAnomalies
Capstone Project

#### Executive Summary
I am interested in using ML to detect suspicious activity in BLockchain environemnts. In order to do this I will be using preprocessing and feature engineering technique to properly prep the data. I will also spend ample time analyzing the data before diving to ensure full understanding of the dataset. In terms of training the model, I plan to use cross validation to split the data into training and testing data, as well as using GridSearchCV to help find the right hyper parameters for the models I train. I will assess my findings based on Precision-Recall curves and each models F1 and balanced accuracy scores , since the dataset I am using is naturally imbalanced due to anomalies been.. anomalies. I will focus on using anomaly detection classifiers such as Isolation Forest and potentially autoencoders, as well as experimenting with the other classifiers we’ve learned in class.

#### Rationale
This is an important question to answer because we are at the intersection of blockchain and AI technology and it is imperative that we finding useful ways to blend these two technologies in a way that promotes security, user satisfaction, and integrity of blockchain networks.

#### Research Question
How can we detect anomalies in blockchain transactions based on user behavior?

#### Data Sources
Data will be sourced from the Metaverse Financial Transactions Dataset available at [Kaggle](https://www.kaggle.com/datasets/faizaniftikharjanjua/metaverse-financial-transactions-dataset/data).

#### Methodology
The methodology includes preprocessing and feature engineering to properly prepare the data. Detailed analysis will precede model training to ensure a full understanding of the dataset. Techniques such as cross-validation will be used to split the data into training and testing sets, and GridSearchCV will be employed to optimize model hyperparameters. Anomaly detection classifiers like Isolation Forest and potentially autoencoders will be used, focusing on precision-recall curves and F1 and balanced accuracy scores due to the natural imbalance of the dataset.

#### Results
The expected results were that anomalies are highly dependent on three main features: Age Group, purchase pattern, and transaction type. What I found in reality so far is that the anomalies were only based on the transaction type, which is problematic because transaction type is always labels when sources these datasets. 

#### Next Steps
The IsolationFOrest model only detected transactions as anamolies when they were labaled as "scam" or 'phising". This means I need ot go back to the drawing board and do some feature engineering to discover better connections within my dataset to enable more features to hold more significance when my model makes predicts. I also need to explore using autoecncoders to see if this model type is more suitable for discovering these features.

#### Outline of Project

- [Link to notebook 1](Capstone.ipynb)

