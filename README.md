# Stock Price Prediction LSTM vs XGBoost
This project builds an LSTM neural network to predict stock prices using historical data fetched via Yahoo Finance. It is trained on daily closing prices and visualizes future trends.

---

# Tech Stack

- Python  
- TensorFlow / Keras (LSTM)  
- XGBoost (Gradient Boosted Trees)  
- yFinance (Yahoo Finance API)  
- NumPy, Pandas, Matplotlib  
- Google Colab

---
# Dataset

Historical stock price data is fetched using `yfinance`. Example:

```python
data = yf.download("RELIANCE.NS", start="2015-01-01", end="2024-12-31")
```

Replace `"RELIANCE.NS"` with any valid NSE or US ticker.

---

# Features

- Download and preprocess real stock data
- Normalize and create sequences for LSTM
- Build and train a 2-layer LSTM model
- Build and train an XGBoost regressor for comparison
- Visualize predictions and compare RMSE scores

---

# Output Sample

> 📷 Screenshot of actual vs predicted prices

![Stock Price Prediction Graph](images/output_plot.png)  
*Actual vs Predicted Stock Prices using LSTM and XGBoost*

---

# How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/stock-price-prediction-lstm.git
cd stock-price-prediction-lstm
```

2. **Open the notebook in Google Colab or Jupyter Notebook**

3. **Install the requirements:**

```python
!pip install yfinance pandas numpy matplotlib scikit-learn keras tensorflow xgboost
```

4. **Run all cells to generate predictions and plots**

---
# Author
**Vidhi Mistry**  
vidhimistry292@gmail.com
