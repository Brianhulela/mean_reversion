# Mean Reversion Strategy with EMAs

This repository implements a **Mean Reversion Trading Strategy** using **Exponential Moving Averages (EMAs)** to identify buy and sell signals. The strategy buys when the stock is considered "oversold" and sells when it is "overbought" based on the relationship between short-term and long-term EMAs.

![Cover Image](https://github.com/Brianhulela/mean_reversion/blob/master/TSLA_mean_reversion_strategy.png)

## How It Works

- **Buy Signal**: Short-term EMA is below the long-term EMA and the price is below both.
- **Sell Signal**: Short-term EMA crosses above the long-term EMA and the price is above both.

## Usage

Clone the repository and run the script to backtest the strategy with historical stock data.

Read more about the strategy in my [Medium article](https://hulela.co.za/trading-strategies-mean-reversion-566c93d49b56).
