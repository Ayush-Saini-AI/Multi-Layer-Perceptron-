# Multi-Layer-Perceptron-
Network Intrusion Detection using MLP (CICIDS 2018)


A from-scratch implementation of a Multi-Layer Perceptron (MLP) for Network Intrusion Detection Systems (NIDS) using the CICIDS 2018 dataset.
The project focuses on understanding neural network internals rather than relying on high-level deep learning frameworks.

Table of Contents

Overview

Why This Project

Features

Project Structure

Getting Started

Usage

Dataset

Help & Support

Contributing

Maintainer

License

Overview

This repository contains a Jupyter Notebook that implements an MLP classifier using NumPy to detect malicious network traffic.
The workflow covers the entire ML pipeline:

Data loading and preprocessing

Feature scaling and label encoding

Neural network construction

Forward and backward propagation

Model training and evaluation

The notebook is Google Colab–ready and suitable for academic labs, research reproduction, and learning purposes.

Why This Project

📚 Educational focus – Understand neural networks at a mathematical and implementation level

🛡️ Security domain – Uses a real-world NIDS dataset

🔍 Transparent ML – No TensorFlow / PyTorch abstractions

☁️ Colab compatible – No local GPU required

🎓 Academic ready – Suitable for DL labs, viva, and presentations

Features

Multi-Layer Perceptron implemented from scratch

ReLU and Softmax activations

Cross-entropy loss

Gradient descent optimization

Data normalization and label encoding

Train–test evaluation

Modular and readable notebook structure

Project Structure
.
├── MLP_CICIDS (1).ipynb     # Main implementation notebook
├── README.md               # Project documentation
├── LICENSE                 # License information
└── docs/
    └── CONTRIBUTING.md     # Contribution guidelines

Getting Started
Prerequisites

Python 3.8+

Google Colab (recommended)

Basic knowledge of:

Machine Learning

Neural Networks

Python & NumPy

Installation

No local installation is required if using Google Colab.

If running locally:

pip install numpy pandas scikit-learn

Usage

Open MLP_CICIDS (1).ipynb in Google Colab

Mount Google Drive:

from google.colab import drive
drive.mount('/content/drive')


Place the CICIDS dataset in your Drive

Update the dataset path in the notebook:

"/content/drive/MyDrive/LAB_CICIDS 2018_1.csv"


Run all cells sequentially

Dataset

This project uses the CICIDS 2018 dataset by the Canadian Institute for Cybersecurity.

Realistic benign and attack traffic

Multiple attack categories

Widely used in NIDS research

📌 Note:
The dataset is not included in this repository due to size limitations.
You must download it separately and upload it to Google Drive.

Help & Support

Check inline comments inside the notebook

Open a GitHub Issue for bugs or questions

Use Discussions for conceptual or research-related queries

Contributing

Contributions are welcome and appreciated.

Please read:

docs/CONTRIBUTING.md

Possible contributions:

Performance optimization

Additional evaluation metrics

Deeper MLP architectures

Adversarial attack experiments

Visualization improvements

Maintainer

Ayush Saini
AI / ML Enthusiast



This project is licensed under the MIT License.
See the LICENSE
 file for details.
