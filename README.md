# anomaly-detection-v1
Statistical Anomaly Detection System

This is a Statistical Anomaly Detection System that implements two classic statistical methods:

1. Core Components:
A. StatisticalDetector Class:

Z-Score Detection: Measures how many standard deviations a data point is from the mean

IQR (Interquartile Range) Detection: Uses quartiles to identify outliers

B. DataLoader Class:

Loads/saves CSV files

Generates synthetic normal and anomalous data

Data preprocessing (normalization, standardization)

Train-test splitting

C. Metrics Class:


Calculates performance metrics (accuracy, precision, recall, F1-score)

Displays confusion matrix
