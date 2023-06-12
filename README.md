# Credit Risk Prediction Project

This project focuses on utilizing machine learning techniques to tackle the challenge of credit risk prediction. By employing data preparation, statistical reasoning, and machine learning algorithms, we aim to build models that can effectively identify risky credit card loans.

## Project Overview

- The goal of this project is to develop and evaluate machine learning models for credit risk prediction.
- The credit card credit dataset from LendingClub, a peer-to-peer lending services company, will be used as the primary data source.
- We will address the inherent class imbalance in credit risk classification by employing resampling techniques provided by the `imbalanced-learn` and `scikit-learn` libraries.
- The following techniques will be applied to the dataset:
  - Oversampling using the RandomOverSampler and SMOTE algorithms.
  - Undersampling using the ClusterCentroids algorithm.
  - Combinatorial resampling using the SMOTEENN algorithm, which combines over- and undersampling approaches.
- Two machine learning models that reduce bias, namely BalancedRandomForestClassifier and EasyEnsembleClassifier, will be compared and evaluated for their ability to predict credit risk.
- The performance of these models will be assessed using various metrics, such as accuracy scores, confusion matrices, and classification reports.
- Based on the evaluation results, a written recommendation will be provided regarding the suitability of the models for credit risk prediction.

## Project Structure

The project consists of the following key deliverables:

1. **Data Preparation**: Perform data preprocessing and prepare the credit card credit dataset for model training and evaluation.

2. **Resampling Techniques**:
   - Apply oversampling techniques using RandomOverSampler and SMOTE algorithms.
   - Apply undersampling using the ClusterCentroids algorithm.
   - Implement the SMOTEENN algorithm for a combinatorial approach to resampling.

3. **Model Training and Evaluation**:
   - Train and evaluate the BalancedRandomForestClassifier and EasyEnsembleClassifier models.
   - Calculate accuracy scores, generate confusion matrices, and create classification reports for each model.

