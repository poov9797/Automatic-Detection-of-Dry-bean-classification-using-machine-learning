# Automatic Dry Bean Classification using Machine Learning
## Overview
This project focuses on the automatic classification of dry beans using machine learning techniques. The goal is to develop a robust model that can accurately categorize different dry bean varieties based on geometric attributes. The primary machine learning algorithms used for classification are XGBoost and Decision Tree.

## Introduction
Dry beans are a vital pulse crop globally, and their cultivation faces challenges due to climate change. This project addresses the need for automatic classification of dry beans to ensure seed quality and meet market demands. The report explores the use of machine learning models, XGBoost and Decision Tree, for accurate classification.

## Dataset
The dataset consists of 13,611 samples, each with 16 geometric attributes representing different dry bean varieties. The seven varieties considered are Dermason, Barbunya, Bombay, Seker, Cali, Horoz, and Sira. Geometric attributes include area, perimeter, aspect ratio, solidity, and more.

## Data Preprocessing
Data preprocessing involves cleaning and converting raw data into a format suitable for machine learning algorithms. Categorical targets are converted into numerical form, and the data is split into features and targets. A crucial step is splitting the data into training and testing sets for model evaluation.

## Machine Learning Techniques
## XGBoost Classifier
The XGBoost classifier is chosen for its strong performance and scalability. The model is developed and trained using a dataset with tuned hyperparameters. The model achieves accuracy ranging from 86.84% to 100.00%, showcasing its effectiveness in dry bean classification.

## Decision Tree
Decision trees are explored as an alternative classification method. The model is tuned with hyperparameters like criterion, max depth, min samples split, and min samples leaf. The Decision Tree model achieves an accuracy of 91%.

## Results and Evaluation
The models' performance is evaluated using a k-fold validation strategy, providing a comprehensive assessment of accuracy, precision, recall, and F1 score. The XGBoost classifier outperforms the Decision Tree, achieving an accuracy of 92.65%.

## Limitations
Limitations include the susceptibility of XGBoost to noise and outliers and the computational expense of GridSearchCV for hyperparameter tuning. Alternative methods and optimizations are suggested.

## Conclusion
The project concludes that the XGBoost classifier, despite being computationally expensive, offers superior accuracy for dry bean classification. The Decision Tree provides a less resource-intensive alternative with slightly lower accuracy. The report suggests further exploration of hyperparameter tuning for enhanced accuracy.

## References
Koklu, M., Ozkan, I.A. (2020). Multiclass classification of dry beans using computer vision and machine learning techniques. Computers and Electronics in Agriculture, 174.
XGBoost documentation: XGBoost classifier.
Scikit-learn Documentation: Decision Trees.
G Słowiński (2021). Dry Beans Classification Using Machine Learning. Available at: Paper.
Murat Koklu, Ilker Ali Ozkan (2020). Multiclass classification of dry beans using computer vision and machine learning techniques. Computers and Electronics in Agriculture, 174, 105507.
