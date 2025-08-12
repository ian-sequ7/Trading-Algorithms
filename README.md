# TradingView Pine Script Strategies

This repository contains two custom **Pine Script® v5** strategies designed for use in [TradingView](https://www.tradingview.com/).  
Both scripts are backtestable and include configurable parameters for optimization.

---

## 📂 Strategies

### 1. **TriCore Alpha**
A multi-strategy algorithm that blends **momentum**, **mean reversion**, and **breakout** systems, adapting dynamically to different market regimes.  

**Core Features:**
- **Momentum Strategy** (MACD + RSI + trend confirmation)  
- **Mean Reversion Strategy** (Bollinger Bands + RSI bounce)  
- **Breakout Strategy** (High-volume resistance/support breaks)  
- **Market Filters** using SPY for trend direction and VIX for volatility regime  
- **Dynamic Risk Management** with ATR-based stops, position sizing, and volatility adjustments  
- **Performance Tracking Table** for real-time backtest metrics  

**Target Metrics:**
- **Sharpe Ratio:** 1.2 – 1.8  
- **Sortino Ratio:** 1.5 – 2.0  
- **Win Rate:** 55 – 65%  
- **Max Drawdown:** 8 – 15%  

📄 **File:** [`TriCore Alpha.txt`](TriCore%20Alpha.txt)  

---

### 2. **RSI + MA Strategy**
A simpler, trend-following strategy using **Relative Strength Index (RSI)** and a **Moving Average** for entries and exits.  

**Core Features:**
- **Long Entry:** RSI oversold + above MA, or MA crossover  
- **Short Entry:** RSI overbought + below MA, or MA crossunder  
- **Exit Conditions:** RSI returning to neutral zone or opposite MA crossover  
- **Configurable Risk Management:** Adjustable stop loss and take profit percentages  

📄 **File:** [`RSI+MA StrategyV1.txt`](RSI%2BMA%20StrategyV1.txt)  

---

## 🚀 Usage
1. Open **TradingView** → Pine Editor  
2. Copy and paste the code from the `.txt` file  
3. Click **Add to chart**  
4. Adjust input parameters to fit your market and time frame  
5. Enable **Strategy Tester** to view performance metrics  

---

## 📊 Quick Comparison

| Feature                | TriCore Alpha | RSI + MA Strategy |
|------------------------|--------------|-------------------|
| Strategies Included    | Momentum + Mean Reversion + Breakout | RSI + Moving Average |
| Market Filters         | Yes (SPY + VIX) | No |
| Risk Management        | Dynamic ATR-based | Static % Stop Loss/Take Profit |
| Complexity             | High | Low |
| Performance Table      | Yes | No |

---

## ⚠️ Disclaimer
These scripts are for **educational purposes only**. They do **not** constitute financial advice.  
Past performance is not indicative of future results.  
Always test strategies on historical data before applying to live markets.
