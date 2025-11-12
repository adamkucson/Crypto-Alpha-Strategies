# Cryptocurrency Alpha Strategies: Technical vs. Sentiment Analysis

A comprehensive quantitative research project comparing systematic trading strategies in cryptocurrency markets. This study evaluates channel breakout (technical) and Google Trends-based sentiment strategies across multiple cryptocurrencies from 2020-2025.

## 📊 Project Overview

This project develops and backtests two independent alpha-generation strategies for cryptocurrency trading:

1. **Channel Breakout Strategy** - Price momentum-based technical strategy using rolling highs/lows
2. **Sentiment Analysis Strategy** - Behavioral strategy exploiting Google Trends search volume changes

Both strategies are rigorously tested across different universes (Top 10, Top 20, Top 80 cryptocurrencies) with proper train/test splits and transaction cost considerations.

## 🎯 Key Findings

### Performance Summary

| Strategy | Sharpe Ratio | Annual Return | Max Drawdown | Alpha (Annual) | Beta | Alpha t-stat |
|----------|--------------|---------------|--------------|----------------|------|--------------|
| **Channel Breakout** (Top 10, Fixed) | **2.04** | 56.9% | -17.2% | 43.5% | 0.20 | 1.76 |
| **Sentiment Analysis** (Top 5, Fixed) | **2.43** | 132.9% | -17.9% | 134.1% | 0.63 | 2.62 |
| Bitcoin Benchmark | ~1.2 | ~45% | -35% | 0% | 1.00 | - |

### Critical Insights

✅ **Both strategies generate statistically significant alpha** beyond Bitcoin market exposure  
✅ **Fixed-weight allocation is essential** - Fully-invested approaches produced catastrophic -70% drawdowns  
✅ **Sentiment strategy dominates on risk-adjusted returns** with a 2.43 Sharpe ratio  
✅ **Universe expansion degrades performance** - Quality beats quantity in crypto  
✅ **Strategy combination offers limited benefits** - 0.58 correlation limits diversification gains

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and time series analysis
- **NumPy** - Numerical computations
- **matplotlib & seaborn** - Data visualization
- **statsmodels** - Statistical analysis and regression
- **scipy** - Optimization and statistical functions
- **Jupyter Notebooks** - Interactive development and documentation
