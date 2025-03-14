# 📈 IBKR Portfolio Analysis with AI 🤖

🚀 **AI-powered analytics for Interactive Brokers portfolios**  
A cutting-edge tool leveraging **Large Language Models (LLMs)** to analyze **IBKR trading activity**, providing **smart insights, risk assessments, and automated reports**.

## 🌟 Features

- ✅ **Portfolio Performance Analysis** (P&L, ROI, Benchmarking)
- ✅ **Risk Assessment** (Volatility, Sharpe Ratio, Max Drawdown)
- ✅ **AI-Driven Trade Insights** (LLM-powered summaries & suggestions)
- ✅ **Automated Reports** (Real-time & historical data)
- ✅ **IBKR API Integration** for live portfolio tracking

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/ibkr-portfolio-analysis.git
cd ibkr-portfolio-analysis
```

2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

3️⃣ Set up IBKR API credentials

- Obtain IBKR API Key from the IBKR Client Portal.
- Configure .env file with your API credentials.

⸻

🚀 Usage

Run the analysis script

```bash
python main.py
```

Analyze portfolio data

```bash
python analyze.py --report performance
```

⸻

📊 Example Output

📌 Portfolio Performance:

- Total Return: +12.3%
- Sharpe Ratio: 1.45
- Max Drawdown: -5.2%
  📊 AI Insights:
- "Your portfolio has a strong tech bias (TSLA, AAPL). Consider diversifying."
- "High exposure to volatility—hedging strategies recommended."

⸻

🛠️ Configuration

Edit config.yaml to customize:

- Portfolio tracking frequency
- Benchmark comparison (S&P 500, Nasdaq)
- AI model parameters

⸻

📡 API Integration

Supports IBKR TWS API & Client Portal API for real-time updates.

```python
from ibkr_api import IBKRClient

ibkr = IBKRClient(api_key="your_api_key")
portfolio = ibkr.get_portfolio()
print(portfolio)
```

---

🔥 Roadmap

🚀 Upcoming Features

- AI-Powered Trade Recommendations
- Sentiment Analysis on Holdings
- Backtesting Engine for Strategy Validation

---

🤝 Contributing

Pull requests & feature suggestions welcome!

---

📜 License

MIT License - Free to use and modify.
