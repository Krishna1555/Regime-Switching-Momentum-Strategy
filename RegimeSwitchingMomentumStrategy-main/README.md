# Regime-Switching Momentum Strategy

A Python-based quantitative trading strategy that uses a Hidden Markov Model (HMM) to identify market conditions and generate momentum-based trading signals.

## Overview

This project analyzes historical stock market data (OHLCV) to identify different market regimes, such as bullish, bearish, and sideways markets. Based on the detected regime, it generates trading signals and evaluates strategy performance through backtesting.

## Features

- **Market Regime Detection:** Uses HMM to identify changing market conditions.
- **Momentum Signals:** Generates buy, hold, and sell signals based on market trends.
- **Backtesting:** Tests strategy performance using historical stock data.
- **Performance Metrics:** Evaluates returns, Sharpe ratio, and maximum drawdown.
- **Risk Management:** Applies risk controls based on market conditions.

## Tech Stack

- Python
- Pandas & NumPy
- Hidden Markov Models (HMM)
- Technical Indicators
- Matplotlib
- Quantitative Backtesting


## Usage

Run the modules in the following order:

```bash
python src/data_ingestion.py
python src/feature_engineering.py
python src/regime_detection.py
python src/signal_generation.py
python src/backtesting.py
```

## Project Structure

```text
RegimeSwitchingMomentumStrategy/
│
├── data/                   # Project documentation
├── src/
│   ├── data_ingestion.py   # Data collection and preprocessing
│   ├── feature_engineering.py # Technical indicators
│   ├── regime_detection.py # HMM-based regime detection
│   ├── signal_generation.py # Trading signals
│   └── backtesting.py      # Strategy evaluation
│
├── requirements.txt
└── README.md
```
