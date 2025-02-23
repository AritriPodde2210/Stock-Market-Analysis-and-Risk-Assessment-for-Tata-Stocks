
# 📈 Tata Stock Market Analysis & Risk Assessment

## 📝 Overview
This project focuses on analyzing Tata Group stocks using various financial indicators, risk assessment methods, and correlation with NIFTY 50. The goal is to provide a **comprehensive risk analysis** and **automated trading insights** based on real time stock data.

## 📊 Features
- **Real-time Data Collection & Cleaning** from Yahoo Finance
- **Stock Trend Analysis** (Closing Price, Moving Averages, RSI)
- **Candlestick Charting** for Visual Insights
- **Correlation with NIFTY 50**
- **Daily Return & Volatility Analysis**
- **Risk Assessment:** Value at Risk (VaR), Bootstrap method
- **Trading Signal Generation** based on RSI
- **Automated Comparison Table** for Portfolio Insights

## 📂 Datasets Used
- real time Stock Data for **Tata Group Companies** (TCS, Tata Motors, Tata Steel, Titan, Tata Power, Tata Consumer)
- **NIFTY 50** historical data for correlation analysis
- Time range: *Specify the timeframe of data used*

## 🔧 Tools & Libraries
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Yahoo Finance API** (yfinance)
- **Scikit-learn** (for data preprocessing)
- **Jupyter Notebook** for analysis

## 📈 Analysis Process
### 1️⃣ Data Collection & Preprocessing
- Fetched historical stock data from Yahoo Finance
- Cleaned missing values and formatted timestamps

### 2️⃣ Stock Market Analysis
- **Closing Price Trends**
- **Moving Averages** (10-day & 50-day)
- **Candlestick Charts** for visualization

### 3️⃣ Risk & Return Analysis
- **Daily Returns** computation
- **Stock Volatility Analysis**
- **Correlation Matrix** (Stock vs NIFTY 50)
- **Risk Analysis using Value at Risk (VaR)**

### 4️⃣ Trading Signal Generation
- **RSI Calculation (Relative Strength Index)**
- **Buy/Sell/Hold Recommendations** based on RSI thresholds:
  - RSI < 30 → **BUY** (Oversold)
  - RSI > 70 → **SELL** (Overbought)
  - 30 ≤ RSI ≤ 70 → **HOLD**

### 5️⃣ Portfolio Risk Management
- **Bootstrap method** for stock price forecasting
- **Portfolio Comparison Table** (Mean Returns, Volatility, RSI, NIFTY Correlation)

## 📊 Results & Insights
- TCS and Titan had the **lowest RSI values**, indicating potential buying opportunities.
- Tata Steel and Tata Consumer showed **higher volatility**, posing greater risk.
- **High correlation** of Tata Motors & Tata Steel with NIFTY 50.
- **Automated trading signals** based on RSI provided actionable insights.

## 🚀 How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/tata-stock-analysis.git
   ```
2. Install dependencies:
   ```sh
   pip install pandas numpy matplotlib seaborn yfinance
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook analysis.ipynb
   ```

## 📌 Future Enhancements
- 📌 Add **Machine Learning Models** for stock price prediction.
- 📌 Implement **Automated Portfolio Optimization**.
- 📌 Deploy a **Web Dashboard** for real-time stock monitoring.

## 🤝 Contributing
Feel free to contribute by improving the analysis, adding new features, or optimizing the code! 

## 📜 License
This project is open-source and available under the **MIT License**.

---
💡 **Author:** Aritri Podder | 📧 Contact: [reach.aritripodder@gmail.com] | 🌐 LinkedIn: [https://www.linkedin.com/in/aritri-podder-749887226/]


