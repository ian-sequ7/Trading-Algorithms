#TradingView Pine Script Strategies
This repository contains two custom Pine Script® v5 strategies designed for use in TradingView. Both scripts are backtestable and include configurable parameters for optimization.
📂 Strategies
1. TriCore Alpha
A multi-strategy algorithm that blends momentum, mean reversion, and breakout systems, adapting dynamically to different market regimes.
It incorporates:
Momentum Strategy (MACD + RSI + trend confirmation)
Mean Reversion Strategy (Bollinger Bands + RSI bounce)
Breakout Strategy (High-volume resistance/support breaks)
Market Filters using SPY for trend direction and VIX for volatility regime
Dynamic Risk Management with ATR-based stops, position sizing, and volatility adjustments
Performance Tracking Table for real-time backtest metrics
Target Metrics:
Sharpe Ratio: 1.2 – 1.8
Sortino Ratio: 1.5 – 2.0
Win Rate: 55 – 65%
Max Drawdown: 8 – 15%
📄 File: TriCore Alpha.txt
2. RSI + MA Strategy
A simpler, trend-following strategy using Relative Strength Index (RSI) and a Moving Average for entries/exits.
It features:
Long entry: RSI oversold + above MA, or MA crossover
Short entry: RSI overbought + below MA, or MA crossunder
Exit on RSI returning to neutral or opposite MA crossover
Configurable stop loss and take profit levels
📄 File: RSI+MA StrategyV1.txt
🚀 Usage
Open TradingView → Pine Editor
Copy and paste the code from the .txt file
Click Add to chart
Adjust input parameters to fit your market and time frame
Enable strategy tester to view performance metrics
⚠️ Disclaimer
These scripts are for educational purposes only. They do not constitute financial advice.
Past performance is not indicative of future results.
Always test strategies on historical data before applying to live markets.
