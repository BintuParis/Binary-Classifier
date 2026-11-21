# Network Traffic Anomaly Detection

A deep learning binary classification pipeline built in PyTorch to identify suspicious network activity and potential cyber attacks from tabular network traffic logs.

## Overview
Modern network intrusion detection systems require fast, automated classification of high-volume traffic records. This project implements an end-to-end machine learning workflow—from leakage-free feature scaling to neural network training and evaluation—to distinguish benign traffic (`0`) from suspicious activity (`1`) across 7 network traffic features.

## Tech Stack
* **Deep Learning:** PyTorch (`torch.nn`, `torch.optim`)
* **Preprocessing:** scikit-learn (`StandardScaler`), Pandas, NumPy
* **Evaluation:** TorchMetrics (`Accuracy`)
