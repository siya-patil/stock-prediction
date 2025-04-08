# 📈 Stock Price Prediction using LSTM

This project implements a Long Short-Term Memory (LSTM) neural network to predict future stock prices based on historical data. LSTMs are a type of recurrent neural network (RNN) capable of learning long-term dependencies, making them ideal for time series forecasting tasks like stock market predictions.

---

## 📁 Dataset

- The dataset consists of historical stock price data.
- It includes columns like `Date`, `Open`, `High`, `Low`, `Close`, and `Volume`.

---

## 🧠 Model

- **Architecture**: LSTM layers followed by Dense layers.
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam
- **Normalization**: MinMaxScaler is used to scale stock prices between 0 and 1 for better training performance.

---

## ⚙️ Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- TensorFlow / Keras / LSTMs

---

## 📊 Output
- The model plots training vs validation loss.
- It visualizes actual vs predicted stock prices.
