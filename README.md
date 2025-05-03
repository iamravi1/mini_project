# DDoS Detection with Deep Learning Models for Network Security

This project focuses on classifying and predicting intrusion attempts in computer networks using Artificial Neural Networks (ANN). Using the KDD CUP'99 dataset, we trained a neural network to accurately detect five major types of network attacks, improving early detection and response in cybersecurity systems.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Paper Implemented](#Paper-Implemented)
- [Key Features](#key-features)
- [Dataset Details](#dataset-details)
- [Software and Hardware Requirements](#software-and-hardware-requirements)
- [Installation](#installation)

---

## 📄 Paper Implemented
- [Research Paper Link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4256380)

## 🚀 Project Overview

With the increasing rate of network intrusions, intrusion detection systems (IDS) have become essential. This project implements an Artificial Neural Network (ANN) to detect five major classes of attacks based on the KDD CUP'99 dataset:
- Buffer Overflow
- Denial of Service (DoS)
- User to Root (U2R)
- Remote to Local (R2L)
- PROBE

The goal is to build a model that can predict whether a given network connection record represents a normal or malicious activity.

---

## ✨ Key Features

- Preprocessing and normalization of KDD CUP'99 data
- ANN model implementation using TensorFlow/Keras
- Multiclass classification of five major attack types
- High detection accuracy (99.1%)
- Model evaluation and visualization

---

## 📊 Dataset Details

- **Dataset Name:** KDD CUP’99
- **Source:** [UCI Machine Learning Repository](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)
- **Format:** CSV
- **Size:** ~5 million instances (used subset for training/testing)
- **Classes:**
  - Normal
  - DoS (e.g., smurf, neptune)
  - Probe (e.g., port scan)
  - R2L (e.g., guessing password)
  - U2R (e.g., rootkit)
  - Buffer Overflow

---

## 💻 Software and Hardware Requirements

### Software
- **Language:** Python 3.9+
- **Libraries:** Listed in `requirements.txt`
- **IDE:** Jupyter Notebook / VS Code / PyCharm

### Hardware
- **CPU:** Intel i5 or better
- **RAM:** Minimum 8 GB (Recommended: 16 GB)
- **GPU:** Optional (CUDA-compatible for TensorFlow)
- **Disk Space:** 2+ GB free

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/iamravi1/mini_project.git
   cd mini_project
