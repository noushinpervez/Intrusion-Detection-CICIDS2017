# Intrusion Detection (CIC-IDS2017)

## Overview
This repository contains an in-depth analysis of the Intrusion Detection Evaluation Dataset (CIC-IDS2017) for Intrusion Detection. Canadian Institute for Cybersecurity (CIC) designed this dataset for the development and evaluation of intrusion detection systems (IDS). The primary focus of this repository is to showcase the implementation and comparison of different machine learning models for binary and multi-class classification tasks. The dataset can be obtained from [here](https://www.unb.ca/cic/datasets/ids-2017.html).

## Dataset Characteristics
### Size and Composition
- Over 2.8 million instances were captured over 5 days (July 3 to July 7, 2017).
- Includes normal traffic and various attacks: Brute Force, Heartbleed, Botnet, DoS, DDoS, Web Attack and Infiltration.
- A highly imbalanced dataset with a majority of records labeled as 'Benign.' (normal traffic) 

### Data Features
- 79 columns with 78 numerical features and a categorical 'Label' column.
- Features include network flow characteristics such as flow duration, packet lengths, ports, flags and more.

## Contents
### Dataset Characteristics and Exploratory Data Analysis (EDA)
- Detailed insights into the dataset's structure, characteristics and an EDA highlighting patterns and anomalies using visualizations.

### Data Preprocessing
- Steps taken to clean the data, handling duplicates and missing values, memory optimization techniques, data standardization and applying PCA to make the dataset suitable for analysis.

### Machine Learning Models
- Implementing and training various machine learning models, including Logistic Regression, Support Vector Machine, Random Forest Classifier, Decision Tree and K-Nearest Neighbours. Both binary and multi-class classifications are explored.

### Performance Evaluation and Discussion
- Evaluation metrics such as accuracy, recall, F1-score and confusion matrix are presented for each model. The impact of class imbalance on model performance is discussed.

## Key Features
- Use of data preprocessing techniques, including standardization to bring uniformity, Principal Component Analysis (PCA) for dimensionality reduction and Synthetic Minority Over-sampling Technique (SMOTE) to balance the class distribution.
- Implements both binary and multi-class classification models.
- Utilizes machine learning algorithms including Logistic Regression, Support Vector Machine (SVM), Random Forest, Decision Trees and K-Nearest Neighbors (KNN).
- Uses a real-world dataset for training and testing.
- Use of cross-validation to ensure that models are not overfitted.
- Provides extensive analysis and comparisons of the different classification algorithms.
- Includes performance evaluation metrics, including precision, recall, accuracy, F1-score, confusion matrix and more.
- Offers insights into improving network security by selecting the most suitable model.
