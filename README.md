# ⚡ Electricity Price Forecasting using Deep Learning

This project focuses on forecasting electricity prices using advanced deep learning techniques. The primary objective is to build models that accurately predict electricity prices based on historical data patterns, using a variety of time series architectures.

---

## 📊 Problem Statement

Electricity price forecasting is critical for energy producers, consumers, and regulatory bodies to make informed decisions in power generation and distribution. Due to the highly volatile nature of electricity prices, deep learning models can be leveraged to capture nonlinear dependencies in the data and improve prediction accuracy.

---

## 🚀 Models Implemented

This project compares the performance of several deep learning models:

1. 🧠 **LSTM (Long Short-Term Memory)**
   - Captures long-range temporal dependencies in time series data.

2. 🌐 **CNN (Convolutional Neural Network)**
   - Extracts local temporal patterns and features from the data.

3. 🔗 **CNN-LSTM Hybrid**
   - Combines spatial pattern detection with sequence modeling for enhanced accuracy.

---

## 🧪 Dataset

- Source: Kaggle
- Features include:
  - Timestamp
  - Electricity price
  - Demand
  - Weather conditions (if applicable)

---

## 🛠️ Setup & Installation

```bash
# Clone the repo
git clone https://github.com/savadarakeshreddy/electricity-price-forecasting-using-deep-learning-techniques.git
cd electricity-price-forecasting-using-deep-learning-techniques

# Install dependencies
pip install -r requirements.txt
