# 📘 Lab Assignment-5: LSTM-based Deep Learning Tasks

## 🧠 Objective

This assignment aims to apply Long Short-Term Memory (LSTM) models to solve three key sequence-based problems:

1. **Time Series Forecasting**
2. **Sequence Text Prediction**
3. **Text Sequence Classification**

---

## 📁 Experiments Overview

---

### 🧪 Experiment 5.1: Time Series Forecasting using LSTM

#### ✅ Objective
To forecast future values of a univariate time series using LSTM.

#### 📊 Dataset Used:
- **Airline Passengers Dataset** (Monthly number of airline passengers from 1949 to 1960)

#### ⚙️ Model Summary:
- Input: Previous time steps
- LSTM Layer: Captures temporal patterns
- Dense Layer: Predicts the next value

#### 🧾 Output:
- Plot: Actual vs Predicted
- Evaluation: RMSE, MAE

---

### 🧪 Experiment 5.2: Sequence Text Prediction using LSTM

#### ✅ Objective
To generate next characters based on an input sequence using LSTM.

#### 📚 Dataset Used:
- **Tiny Shakespeare Dataset** (`tensorflow_datasets`)

#### ⚙️ Model Summary:
- Character-level tokenization
- Embedding + LSTM + Dense layers
- Trained for 20 epochs for coherent text generation

#### 🧾 Output:
- Auto-generated text samples
- Loss curves plotted

---

### 🧪 Experiment 5.3: Text Classification using LSTM

#### ✅ Objective
To classify text sequences (e.g., sentiment analysis) using LSTM.

#### 📚 Dataset Used:
- **IMDb Movie Reviews Dataset** (`tf.keras.datasets.imdb`)

#### ⚙️ Model Summary:
- Embedding Layer
- LSTM Layer (64 units)
- Dense Sigmoid output for binary classification

#### 🧾 Output:
- Evaluation: Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- Plot: Accuracy over epochs
- Tested on custom review samples

---

## 📌 Evaluation Metrics Explained

- **MAE (Mean Absolute Error)**: Avg. absolute difference between actual and predicted values
- **RMSE (Root Mean Squared Error)**: Penalizes large errors more than MAE
- **Accuracy**: Ratio of correct predictions
- **F1-Score**: Harmonic mean of precision and recall
- **Confusion Matrix**: Visual classification performance

---
