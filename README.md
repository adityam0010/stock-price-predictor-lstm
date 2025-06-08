# 📈 Stock Price Prediction App (LSTM + Streamlit)

A web-based application that predicts future stock prices using LSTM (Long Short-Term Memory) neural networks and displays the results interactively via Streamlit. The app also includes technical indicators like RSI, MACD, SMA, and EMA for enhanced analysis.

---

## 🚀 Features

- ✅ Fetch real-time stock data using `yfinance`
- ✅ Automatically compute technical indicators with `ta`
- ✅ Prepare sequences and train an LSTM model using `TensorFlow`
- ✅ Forecast future stock prices (1–30 days ahead)
- ✅ Interactive web UI built with Streamlit
- ✅ Visualize historical vs predicted prices
- ✅ Simple interface for any stock ticker (e.g., AAPL, MSFT, INFY)

---

## 🧠 Technologies Used

| Tech | Description |
|------|-------------|
| Python | Core language for logic and modeling |
| Streamlit | For building the interactive UI |
| TensorFlow | For LSTM-based deep learning |
| yFinance | To fetch stock data from Yahoo Finance |
| scikit-learn | For data preprocessing/scaling |
| pandas & numpy | For data manipulation |
| matplotlib | To plot charts in Streamlit |
| ta | Technical Analysis indicators like RSI, MACD, etc. |

---

## 🖥️ Project Structure

```bash
├── app.py                     # Streamlit UI
├── data/
│   └── data_loader.py         # Fetch & preprocess stock data
├── model/
│   └── trainer.py             # LSTM model creation, training, and prediction
├── utils/
│   └── indicators.py          # Add RSI, MACD, SMA, EMA indicators
├── requirements.txt           # Python dependencies
└── README.md                  # You're here!


⚙️ How to Run the Project Locally

Download or Clone the repo:
git clone https://github.com/adityam0010/stock-price-predictor-lstm.git
cd stock-price-predictor-lstm

🧪 Set up virtual environment (recommended)
python -m venv venv

# Activate it:
venv\Scripts\activate         # Windows
source venv/bin/activate      # macOS/Linux

📦 Install dependencies
pip install -r requirements.txt

🚀 Run the app
streamlit run app.py
