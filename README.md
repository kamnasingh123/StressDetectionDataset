# StressDetectionDataset
A novel Dataset for stress detection 

Stress Detection Dataset with Patterned Anomalies
This repository contains a structured dataset designed for research in stress detection using physiological signals collected from wearable sensors. The dataset has been used to build an interpretable stress prediction system based on deep learning and mathematical modeling.

Dataset Description
Filename: stress_dataset_with_patterned_anomalies.csv

Each row in the dataset represents a time-synchronized reading of physiological signals captured from individuals in real or simulated stress conditions. Some rows are marked with synthetic anomalies to reflect patterned stress responses or unusual physiological variations.

Columns included:

timestamp: Time at which the reading was taken (in seconds or ISO format)

HRV: Normalized Heart Rate Variability signal

EDA: Normalized Electrodermal Activity signal

TEMP: Normalized Skin Temperature (in degrees Celsius)

stress_label: Binary label indicating stress (1 = stressed, 0 = not stressed)

anomaly_flag: Indicates presence of a synthetic anomaly (1 = anomaly present, 0 = normal)

Purpose
This dataset is intended for:

Training deep learning models (e.g., CNN-LSTM) for real-time stress classification

Developing interpretable stress prediction equations using nonlinear signal transformations

Testing the robustness of stress models under patterned anomalies

Use Cases
Stress detection in occupational healthcare (e.g., hospital staff)

Real-time mental health monitoring using wearable devices

Development of interpretable AI models for physiological signal processing

Model Reference
This dataset was used in a research study to develop:

A CNN-LSTM hybrid model achieving 94% accuracy, 96% precision, 95% recall, and 94% F1-score

A mathematical stress model with low prediction error (MAE = 0.0306, RMSE = 0.0348) aligned with deep learning outputs
