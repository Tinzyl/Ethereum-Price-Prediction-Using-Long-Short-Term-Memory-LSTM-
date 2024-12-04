# 💹 Ethereum Price Prediction Using Long Short-Term Memory (LSTM)

This project predicts the future price of Ethereum (ETH) using a Long Short-Term Memory (LSTM) neural network. The model is trained on historical price data to predict the price for the next hour.

---

## 🌟 Project Highlights

- **Data Preprocessing**: Extracted and scaled historical price data. 🧹
- **Feature Engineering**: Created time-based features like hour, day, month, and year. 🕒
- **Custom LSTM Model**: Built and trained an LSTM model for sequential data prediction. 🤖
- **High Accuracy**: Achieved a high R² score of **0.969** for predictions. 📈
- **Future Forecasting**: Predicted Ethereum prices for up to 30 days into the future. 🔮

---

📊 **Data Overview**

Dataset: Contains hourly price data for Ethereum.

Columns: Open, High, Low, Close, Volume

Period: Historical data from 2016 to 2020.

Target Variable: Close price.

🤖 **Model Details**

Architecture:

Input: 240-hour rolling window of the Close price.

Layers:

LSTM: 100 units for sequential learning.

Dropout: 20% to prevent overfitting.

Dense: Linear activation for continuous output.

Output: Single predicted price for the next hour.

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam

🧪 **Model Performance**

Training Loss: Converged to a low MSE in 5 epochs.

R² Score: 0.969 (indicating strong predictive capability).
