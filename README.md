# AI-Powered Phishing URL Detection using ResMLP

## Overview
This project implements a deep learning-based phishing URL detection system using a custom Residual Multi-Layer Perceptron (ResMLP) architecture. The model classifies URLs as phishing or benign using handcrafted URL, domain, HTML, and JavaScript-based features.

The project reproduces and evaluates the IEEE research paper:
"An Effective Detection Approach for Phishing URL Using ResMLP"

---

## Features
- Deep Learning-based phishing URL detection
- Custom ResMLP architecture using TensorFlow/Keras
- Large-scale dataset with 522K+ URLs
- Advanced preprocessing and feature engineering
- Benchmarking against 7 ML/DL models
- ROC, PR Curves, Confusion Matrix, and Feature Importance visualizations
- Model comparison and performance analysis

---

## Tech Stack
- Python
- TensorFlow / Keras
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset
The dataset contains:
- Benign URLs
- Phishing URLs

Features include:
- URL length
- Special character counts
- HTTPS flags
- Domain age
- DNS records
- HTML & JavaScript behavior indicators

Total dataset size:
- 522,214 URLs

---

## Model Architecture
The ResMLP architecture includes:
- Conv1D layers
- Inverted Residual Blocks
- Batch Normalization
- ReLU activation
- Dropout regularization
- Dense MLP layers

---

## Results

| Metric | Score |
|---|---|
| Accuracy | 90.07% |
| Precision | 95.83% |
| Recall | 46.93% |
| F1 Score | 63.01% |
| ROC-AUC | 91.06% |

---

## Model Comparison
Models evaluated:
- Logistic Regression
- Naive Bayes
- Random Forest
- XGBoost
- Gradient Boosting
- DNN
- LSTM
- ResMLP (Proposed)

---

## Folder Structure

```bash
.
├── models/
├── plots/
├── results/
├── ML.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

```bash
git clone https://github.com/yourusername/ai-phishing-url-detector.git
cd ai-phishing-url-detector
pip install -r requirements.txt
```

---

## Run the Project

```bash
jupyter notebook
```

Open:
```bash
ML.ipynb
```

---

## Future Improvements
- Real-time phishing detection API
- Streamlit frontend deployment
- Transformer-based phishing detection
- Explainable AI integration
- LLM-powered phishing explanation system

---

## Author
Sushmitha Bungatavula
