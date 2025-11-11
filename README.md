

<p align="center">
  <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0bb0a498-9d0a-420d-bd21-c905e4313240" />
</p>


# AutoTrade Engine

A modular algorithmic trading engine supporting **Long/Short**, **Stop‑Loss / Take‑Profit**, **ATR‑based dynamic risk**, **cooldown logic**, and **multi‑indicator strategy fusion**. Designed for both **backtesting** and **paper trading** with CCXT.

---

## 📌 Features

* Unified engine for **Backtest** and **Live Paper Mode**
* Full **Long + Short** capability
* ATR‑based stop generation with adaptive SL/TP
* Time‑based position exit and dynamic trailing logic
* Cooldown system to avoid over‑trading
* Modular components: Strategy, Risk Manager, Engine, Broker
* Full logging: trades + equity curve

---

## 📁 Project Structure (Tree)

```
AutoTrade/
│── core/
│   ├── engine.py        # Trading engine
│   ├── strategy.py      # Indicators + signal generator
│   ├── risk.py          # ATR risk model + SL/TP
│   ├── broker.py        # PaperBroker / backtest broker
│
│── tools/
│   ├── indicators.py    # RSI, MACD, ATR, slopes
│
│── reports/
│   ├── paper_trades.csv
│   ├── paper_equity.csv
│
│── main.py              # Entry point
│── config.yaml          # Exchange + engine configs
│── README.md
```

---

## 🚀 Roadmap (Next 11 Steps)

1. **Portfolio Engine**: multi‑asset parallel trading
2. **Regime Detection**: trend / chop classifier
3. **Volatility Adapter**: adjust SL/TP, cooldown, and position size
4. **Adaptive Learning**: reward‑based auto‑tuning of risk parameters
5. **LLM‑Agent Integration** (optional): natural‑language‑driven supervision
6. **Orderbook‑aware execution**
7. **Dynamic strategy weights** (RSI/MACD/ATR fusion)
8. **Walk‑Forward optimization module**
9. **Pandas → Polars migration** for speed
10. **Live trading mode** with real keys
11. **Dashboard**: real‑time charts + equity monitoring

---

## 🔧 Requirements

* Python 3.10+
* ccxt
* pandas
* numpy
* pyyaml

Install everything:

```bash
pip install -r requirements.txt
```

---

## 🔑 License

**Proprietary License – Personal Use Only**

This project is **not** open‑source. Only the owner may use, modify, or distribute it.

---

## 📬 Contact

For questions, collaboration, or private enhancements:

Developer: Majid Askary

Email: m.askary84@yahoo.com

LinkedIn: https://www.linkedin.com/in/majidaskary

---


