# Geopolitical Crisis & Stock Market Analysis
### Iran vs USA-Israel War —> Impact on Indian Energy Stocks (2025-2026)

---

## Background

In late 2025 and early 2026, escalating tensions between Iran and 
the USA-Israel alliance created one of the most significant 
geopolitical shocks to global oil markets in recent years. 
As a major oil exporting nation, Iran's involvement directly 
threatened crude oil supply through the Strait of Hormuz 
the world's most critical oil shipping route.

This project analyses how that crisis played out in Indian 
stock markets specifically in energy, oil, and infrastructure 
stocks that are directly linked to global crude oil prices.

---

## Objective

As a beginner in quantitative finance and algorithmic trading, 
I built this project to understand how real world geopolitical 
events translate into stock market movements and how we can 
measure, analyse and potentially trade these movements using 
data and code.

---

## 📊 Programs Built

### 1. ONGC vs Crude Oil Price Analysis
- Downloaded real ONGC stock data and WTI Crude Oil futures
- Plotted both on a dual axis chart to visually see the relationship
- Identified key periods where ONGC tracked crude and where it didn't

### 2. SMA Crossover Strategy
- Calculated 20 day and 50 day Simple Moving Averages on ONGC
- Identified Golden Cross (buy signal) and Death Cross (sell signal)
- Visualised the crossover points on a price chart

### 3. Rolling Correlation Analysis
- Calculated 30 day rolling correlation between ONGC and Crude Oil
- Discovered that correlation broke down completely in Sep-Nov 2025
- Found that geopolitical events force the correlation back to 0.85+

### 4. Beta Analysis — 6 Energy Stocks
- Calculated Beta for ONGC, Reliance, IOC, BPCL, GAIL, Adani Ports
- Used Nifty 50 as market benchmark
- Found that shipping stocks (Adani Ports β=1.62) were MORE volatile
  than actual oil producers (ONGC β=0.17) during the crisis

### 5. Sharpe Ratio Analysis
- Calculated Sharpe Ratio for Reliance and IOC
- Found both stocks gave negative Sharpe during the crisis period
- Concluded that a fixed deposit would have outperformed both stocks
  during this specific geopolitical period

---

## 🔍 Key Findings

1. **ONGC barely followed the market (β=0.17)** — Government PSU 
   status shields it from pure market volatility

2. **Adani Ports was the most volatile (β=1.62)** — Strait of Hormuz 
   shipping threat affected logistics stocks more than oil producers

3. **Correlation between ONGC and Crude crashed to -0.75** in 
   Sep-Nov 2025 due to weak earnings, Axis Capital sell rating, 
   and OPEC oversupply fears

4. **Geopolitical crisis forces re-correlation** — when Iran-USA 
   tensions peaked, ONGC and Crude snapped back to 0.85+ correlation

5. **Negative Sharpe Ratios across the board** — the crisis period 
   was simply a bad time to hold Indian energy stocks from a 
   risk-adjusted returns perspective

---

## 🛠️ Tools & Libraries Used

```python
import yfinance as yf       # stock data
import pandas as pd         # data manipulation  
import numpy as np          # numerical calculations
import matplotlib.pyplot as plt  # visualisations
```
---

## 🚀 What I Learnt

- How to fetch and analyse real stock market data using Python
- How geopolitical events create tradeable patterns in markets
- How to measure risk using Beta and Sharpe Ratio
- How correlation between assets changes during crisis periods
- Why event driven analysis is a core strategy in algo trading

---

## 📌 Next Steps

- [ ] Backtest the SMA crossover strategy
- [ ] Add RSI and MACD indicators
- [ ] Build a simple portfolio optimiser
- [ ] Use ML to predict ONGC price movements

---

## ⚠️ Disclaimer

This project is purely for educational purposes as part of my 
journey learning quantitative finance and algorithmic trading. 
Nothing here is financial advice.

---

*Built with curiosity and a lot of debugging 😄*
