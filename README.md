# ECM-402 Lab 3 — Neural Networks & Automatic Modulation Classification

A clean, Git-ready implementation of **ECM-402: AI for Signal Processing — Lab 3**.

The project covers neural networks implemented from scratch with NumPy and a PyTorch MLP for Automatic Modulation Classification (AMC).

## 📌 Overview

### Part A — Neural Network from Scratch

- Spiral dataset generation at multiple noise levels
- Explanation of nonlinear class separation
- Dense/fully connected layer
- ReLU activation
- Numerically stable softmax + cross-entropy
- SGD with momentum
- RMSProp
- Adam
- Numerical gradient checking
- Training and optimizer comparison
- Decision-boundary visualization
- Hidden-layer capacity comparison: **3 vs. 64 neurons**

### Part B — Automatic Modulation Classification

- Synthetic I/Q signal generation
- BPSK, QPSK, 8PSK, 16QAM, and 64QAM
- Constellation visualization at different SNRs
- Amplitude/phase statistics
- Higher-order cumulant features
- Stratified train/test splitting across SNR
- Feature standardization
- PyTorch MLP implementation
- SGD, RMSProp, and Adam comparison
- Adam learning-rate sweep
- Accuracy versus SNR
- Low-/high-SNR confusion matrices
- Longer observation-window experiment

## 📁 Repository Structure

```text
ECM402-Lab3/
├── ECM402_Lab3_Solutions.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 🛠️ Requirements

- Python 3.9+
- NumPy
- Matplotlib
- Pandas
- scikit-learn
- PyTorch
- Jupyter Notebook / JupyterLab

Install the dependencies with:

```bash
pip install -r requirements.txt
```  
**Lab:** Lab 3  
**Topic:** Feedforward Neural Networks and Automatic Modulation Classification

## 📄 License

This repository is intended for academic/educational use. Add the license required by your institution or course before publishing the repository publicly.
