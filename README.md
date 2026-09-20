# USD FX Quant Signal Engine V2

## What this version contains
- EUR/USD
- GBP/USD
- USD/JPY
- USD/CHF
- AUD/USD
- NZD/USD
- USD/CAD
- EMA 20/50/200
- RSI
- MACD
- ADX
- ATR
- 20-period breakout detection
- 4-hour trend confirmation
- Entry / Stop Loss / Take Profit
- Risk/reward
- Multi-pair scanner
- Historical backtest
- Real market-data download through yfinance

## Important
This is a research/signal application, not a guaranteed-profit system.
The confidence score is a rule-based score, NOT a probability of winning.

## Run locally

1. Install Python 3.10 or newer.
2. Open a terminal in this folder.
3. Install dependencies:

   pip install -r requirements.txt

4. Start the app:

   streamlit run app.py

5. Open the local Streamlit address shown in the terminal.

## Recommended next upgrades
1. Replace yfinance with a broker/live FX API.
2. Add spread/slippage.
3. Add economic-calendar data for NFP, CPI and FOMC.
4. Add walk-forward/out-of-sample testing.
5. Add risk-per-trade position sizing.
6. Add alerts.
