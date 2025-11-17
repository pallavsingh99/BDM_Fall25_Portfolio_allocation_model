# 📈 Portfolio Optimization using Pyomo and IPOPT

This repository contains a **fully functional portfolio optimization tool** that:
- Fetches historical stock price data from **Yahoo Finance**
- Calculates **monthly returns** using only **closing prices**
- Solves the **mean-variance optimization** problem using **Pyomo** and **IPOPT**
- Plots both the **Efficient Frontier** and **Asset Allocation vs Risk**

---

## 🧠 How It Works

This project combines financial data from `yfinance` with optimization modeling from `Pyomo` to generate an **Efficient Frontier** — the set of portfolios that maximize return for a given level of risk (variance).

The script:
1. Downloads stock data (Close prices) for the selected tickers
2. Computes monthly returns
3. Builds a quadratic optimization model in Pyomo
4. Solves it across a range of risk levels using IPOPT
5. Plots the Efficient Frontier and corresponding asset allocations

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

