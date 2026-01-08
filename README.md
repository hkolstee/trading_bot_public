# Deep Learning Trading Bot

This repository serves as a public showcase for a private high-frequency algorithmic trading project. The system utilizes deep reinforcement learning (RL) to make autonomous trading decisions in cryptocurrency markets.

## Project Overview

The goal of this project is to create a robust trading agent that adapts to changing market conditions without relying on hard-coded strategies. The agent learns to maximize risk-adjusted returns through extensive simulation and training.

### Core Technology

*   **Deep Learning Architecture**: The system leverages state-of-the-art sequence modeling techniques to identify complex temporal patterns and relationships within the data.
*   **Multi-Modal Data Pipeline**: The bot ingests a high-dimensional feature set to form its view of the market, combining:
    *   **Market Data**: High-frequency price and volume information.
    *   **Network Activity**: Metrics reflecting on-chain behavior and adoption.
    *   **Sentiment Analysis**: Signals derived from social media and news trends.
    *   **Macro Indicators**: Broader economic signals to detect long-term market regimes.
*   **Fidelity-First Backtesting**: To avoid the common pitfall of look-ahead bias, the backtesting engine strictly enforces real-world constraints, accounting for data latency, trading fees, and slippage.

## Performance & Visualizations

The following plots are generated from backtests on unseen data. Each window represents a specific period where the model's decisions were simulated against historical data.

### Backtest Results

These charts show the equity curve, drawdown, and key performance metrics for various testing windows.

![Backtest Result 1](plots/backtest_results_100200_101200.png)
![Backtest Result 2](plots/backtest_results_115000_116000.png)
![Backtest Result 3](plots/backtest_results_125500_126250.png)
![Backtest Result 4](plots/backtest_results_144000_144750.png)
![Backtest Result 5](plots/backtest_results_166000_166750.png)
![Backtest Result 6](plots/backtest_results_185000_185750.png)
![Backtest Result 7](plots/backtest_results_195000_195750.png)
![Backtest Result 8](plots/backtest_results_19500_20250.png)
![Backtest Result 9](plots/backtest_results_211500_212250.png)
![Backtest Result 10](plots/backtest_results_222000_222750.png)
![Backtest Result 11](plots/backtest_results_36000_36750.png)
![Backtest Result 12](plots/backtest_results_63700_64700.png)

### Trade Visualizations

Visualizing specific trade entries and exits helps verify that the model is reacting to valid signals rather than noise.

#### Long Positions
![Long Chart 1](plots/chart_long_100200_101200.png)
![Long Chart 2](plots/chart_long_115000_116000.png)
![Long Chart 3](plots/chart_long_125500_126250.png)
![Long Chart 4](plots/chart_long_144000_144750.png)
![Long Chart 5](plots/chart_long_166000_166750.png)
![Long Chart 6](plots/chart_long_185000_185750.png)
![Long Chart 7](plots/chart_long_195000_195750.png)
![Long Chart 8](plots/chart_long_19500_20250.png)
![Long Chart 9](plots/chart_long_211500_212250.png)
![Long Chart 10](plots/chart_long_222000_222750.png)
![Long Chart 11](plots/chart_long_36000_36750.png)
![Long Chart 12](plots/chart_long_63700_64700.png)

#### Short Positions
![Short Chart 1](plots/chart_short_100200_101200.png)
![Short Chart 2](plots/chart_short_115000_116000.png)
![Short Chart 3](plots/chart_short_125500_126250.png)
![Short Chart 4](plots/chart_short_144000_144750.png)
![Short Chart 5](plots/chart_short_166000_166750.png)
![Short Chart 6](plots/chart_short_185000_185750.png)
![Short Chart 7](plots/chart_short_195000_195750.png)
![Short Chart 8](plots/chart_short_19500_20250.png)
![Short Chart 9](plots/chart_short_211500_212250.png)
![Short Chart 10](plots/chart_short_222000_222750.png)
![Short Chart 11](plots/chart_short_36000_36750.png)
![Short Chart 12](plots/chart_short_63700_64700.png)

### Dataset Overview

![Price Array](plots/price_array.png)
