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

## ▶️ Running the Notebook

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd ECM402-Lab3
```

### 2. Create and activate a virtual environment

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open:

```text
ECM402_Lab3_Solutions.ipynb
```

Run the cells from top to bottom.

## 🧠 Implementation Notes

The notebook is intentionally organized so that each problem contains only the code needed for that problem and its direct dependencies.

- Original execution counts and stored outputs have been removed.
- Code is preserved from the supplied reference solution.
- Part A uses NumPy for the neural-network implementation.
- Part B uses PyTorch for the AMC classifier.
- The datasets are generated locally; no external dataset download is required.
- CPU execution is supported.

## 📊 Problem Map

| Problem | Topic | Main Tools |
|---|---|---|
| 1 | Spiral dataset preparation | NumPy, Matplotlib |
| 2 | NN implementation from scratch | NumPy |
| 3 | Training & optimizer comparison | NumPy, Matplotlib, Pandas |
| 4 | Network capacity | NumPy, Matplotlib, Pandas |
| 5 | AMC features & visualization | NumPy, Matplotlib, Pandas |
| 6 | PyTorch MLP | PyTorch |
| 7 | Optimizer & LR comparison | PyTorch, Matplotlib |
| 8 | SNR & error analysis | PyTorch, scikit-learn, Matplotlib |

## 🔬 Reproducibility

Random seeds are explicitly set in the notebook where required. Because training performance can depend on the installed Python/PyTorch version and CPU environment, small numerical differences may occur between runs.

## 👤 Course

**Course:** ECM-402 — AI for Signal Processing  
**Lab:** Lab 3  
**Topic:** Feedforward Neural Networks and Automatic Modulation Classification

## 📄 License

This repository is intended for academic/educational use. Add the license required by your institution or course before publishing the repository publicly.
