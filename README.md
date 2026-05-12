# Electrical-Fault-Classification-PyTorch
ANN-based electrical fault detection and classification system using PyTorch for analyzing power system faults from voltage and current measurements.
Electrical Fault Detection and Classification using ANN
Repository Name

Electrical-Fault-Detection-ANN

Repository Description

ANN-based electrical fault detection and classification using PyTorch and power system voltage/current measurement data.

README.md
Electrical Fault Detection and Classification using ANN
Overview

This project implements an Artificial Neural Network (ANN) using PyTorch for electrical fault detection and classification in power systems.

The model learns patterns from voltage and current measurements to classify different types of electrical faults using a multi-label classification approach.

Dataset

Dataset Source:

https://www.kaggle.com/datasets/esathyaprakash/electrical-fault-detection-and-classification

Input Features
Ia
Ib
Ic
Va
Vb
Vc
Output Labels
G
C
B
A
Technologies Used
Python
PyTorch
Pandas
NumPy
Scikit-learn
Model Architecture

The ANN model consists of:

Input Layer
Hidden Layer (128 neurons, ReLU activation)
Hidden Layer (64 neurons, ReLU activation)
Output Layer (4 outputs for multi-label classification)
Loss Function
BCEWithLogitsLoss
Optimizer
Adam Optimizer
Features
Custom PyTorch Dataset Class
DataLoader Implementation
Multi-label Classification
ANN-based Fault Detection
Voltage and Current Based Fault Analysis
Training

The model is trained for 100 epochs using mini-batch gradient descent.


Project Structure

Electrical-Fault-Detection-ANN/
│
├── fault_detection.ipynb
├── requirements.txt
├── README.md
├── results/
│ ├── loss.png
│ ├── accuracy.png
│ └── predictions.png
│
└── dataset_link.txt
