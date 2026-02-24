# Sequence & Image Models (CNN / RNN / LSTM / GRU)

This repository contains hands-on deep learning notebooks covering:

- **CNN** for image classification tasks
- **RNN** for sequence modeling (sentiment analysis, text prediction)
- **LSTM / GRU** for improved sequence learning and long-term dependencies

The goal is to understand how these architectures work and compare their behavior on different types of data.

---

## Tech Stack

- Python 3
- Jupyter Notebook
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib

---

## Repository Structure

```
Sequence-Image-Models/
├── notebooks/
│   ├── 01_cnn_session.ipynb   — CNN notebook (CIFAR-10 & MNIST)
│   ├── 02_rnn_session.ipynb   — RNN notebook (IMDB sentiment + text prediction + translator)
│   └── 03_lstm_gru.ipynb      — LSTM & GRU notebook (time-series forecasting)
└── requirements.txt
```

---

## Notebooks Overview

### 01 — CNN (Convolutional Neural Network)
- Dataset: **CIFAR-10** (60,000 color images, 10 classes) and **MNIST** (handwritten digits)
- Compares a fully-connected **DNN** vs a **CNN** on image classification
- Key concepts: Conv2D, MaxPooling, Flatten, Dropout

### 02 — RNN (Recurrent Neural Network)
- Dataset: **IMDB** movie reviews (binary sentiment analysis)
- Projects: next-word prediction and a mini English → Spanish translator (Seq2Seq with LSTM)
- Key concepts: Embedding, SimpleRNN, sequence padding, tokenization

### 03 — LSTM & GRU
- Dataset: **Daily Minimum Temperatures** (time-series regression)
- Trains an LSTM and a GRU to forecast temperature values
- Key concepts: sequence windows, LSTM vs GRU comparison, validation loss curves

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Ahmed3li99/Sequence-Image-Models.git
cd Sequence-Image-Models
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start Jupyter:

```bash
jupyter notebook
```

4. Open any notebook inside `notebooks/` and run all cells.

---

## Author

Ahmed Ali
