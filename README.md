# Machine Learning Based Network Intrusion Detection System

This project implements a machine learning based intrusion detection system that classifies network traffic as **normal** or **malicious** using the NSL-KDD dataset.

## Objective

The objective of this project is to analyze network traffic and detect potential intrusions using machine learning models.

## Algorithms Used

- Logistic Regression
- Random Forest
- XGBoost

## Dataset

The project uses the **NSL-KDD dataset**, a widely used benchmark dataset for network intrusion detection research.

Dataset Source:  
https://github.com/defcom17/NSL_KDD

## Methodology

1. Load and preprocess the NSL-KDD dataset
2. Convert attack labels into binary classes (Normal / Attack)
3. Encode categorical features
4. Split dataset into training and testing sets
5. Train multiple machine learning models
6. Evaluate model performance using various metrics
7. Visualize results using graphs and ROC curves

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve

## Results

The experimental results show that ensemble models such as **Random Forest** and **XGBoost** achieve higher accuracy and better intrusion detection performance compared to Logistic Regression.

## Features of the Project

- Machine learning based intrusion detection
- Model performance comparison
- Confusion matrix visualization
- ROC curve analysis
- Feature importance analysis

## Technologies Used

- Python
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Conclusion

This project demonstrates how machine learning techniques can be applied to detect malicious network activity and improve cybersecurity systems.

