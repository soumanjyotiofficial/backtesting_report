# backtesting_report
## Please note that on the last page pdf of the backtesting report; the tester (me) claims to have 3 years of experience. The statement is false. Even though I have done backtesting for the 3 years as # # student project not as a profession as a hobby of learning programming language algo. (It was a part of my affirmation I used to practice and the template I used for the client was the same template I built during my learning stage)
Certainly! Below is a README file formatted for a GitHub repository, based on the provided context.

---

# Trading Strategy Analysis

## Table of Contents
1. [Client Information](#client-information)
2. [Strategy Requirement](#strategy-requirement)
3. [Trading Strategy Report](#trading-strategy-report)
4. [Executive Summary](#executive-summary)
5. [Objective](#objective)
6. [Key Performance Metrics Used](#key-performance-metrics-used)
7. [Methodology](#methodology)
8. [Key Performance Metrics Table](#key-performance-metrics-table)
9. [Yearly Equity Curve](#yearly-equity-curve)
10. [System Equity Curve](#system-equity-curve)
11. [Distribution of Profit and Loss Trades](#distribution-of-profit-and-loss-trades)
12. [Tester’s Opinion](#testers-opinion)
13. [Conclusion](#conclusion)

---

## Client Information
Page No: 2

---

## Strategy Requirement
Page No: 3

**Purpose:** Evaluate the trading system on NIFTY INDEX and BANKNIFTY based on the provided trading rules.

**Duration:** Past 7 years

**Total Number of Indicators Used:** 2 (EMA and ADX+)

**Trading Strategy Report**

---

## Executive Summary
Page No: 4

This strategy is a positional trading strategy, tested on a Daily Time frame candle.

**Strategy Overview:**
- **Strategy Name:** 10EMA-ADXPosition
- **Strategy Type:** Long only strategy
- **Asset Type:** Index

**Description:** The strategy underwent back testing using historical data spanning a 20-year period. It encompasses all stocks within the NIFTY50 index as the sample universe. The analysis is conducted on a daily timeframe using candlestick charts.

---

## Objective
Page No: 4

1. Provide performance metrics for the developer to decide on deployment in front test or live market.
2. Provide key parameters for the developer to assess the strategy's profitability and consistency.

---

## Key Performance Metrics Used
Page No: 5

- **Total Return (in %):** \[\(\frac{\text{Final value of capital}}{\text{Initial capital}} - 1\) * 100\]
- **Total Return (in amount):** \[\(\text{Final value of capital} - \text{Initial Capital}\)\]
- **Sharpe Ratio:** \[\frac{R_s - R_f}{\sigma_s}\]
  - Rs = Return of strategy
  - Rf = Risk free rate
  - σs = Standard deviation of return (risk)
- **Average Profit:** \[\frac{\text{Total Profit} - \text{Total Loss}}{\text{Total number of trades}}\]
- **Average Bars Held:** \[\frac{\text{Sum of Bars Held for All Trades}}{\text{Total number of trades}}\]
- **Max. System Drawdown (MXDD):** From equity Curve
- **MXDD%:** \[\frac{\text{Max. System Drawdown}}{\text{Peak Equity}} * 100\]
- **Gross Recovery Factor:** \[\frac{\text{Net Profit}}{\text{Max. System Drawdown}}\]
- **CAR/MXDD%:** \[\frac{\text{Compounded annual % return}}{\text{MS% Drawdown}}\]
- **RAR/MXDD:** \[\frac{\text{Sharpe Ratio - Rf}}{\text{MXDD}}\]
- **Profit Factor (PF):** \[\frac{\text{Total Profit}}{\text{Total Loss}}\]
- **Payoff Ratio (PR):** \[\frac{\text{Avg. Profit per Winning Trade}}{\text{Avg. Loss per Losing Trade}}\]
- **Standard Error (Std.E):** \[\frac{\text{Standard Deviation of equity curve}}{\sqrt{\text{Number of trades}}}\]
- **Annualized Return:** \[\sqrt{n}\left(\frac{\text{Ending Value}}{\text{Initial Capital}}\right)\]

---

## Methodology
Page No: 6

- **Samples:** The data sample contains the top 50 stocks based on free-float market capitalization across various industries such as FMCG, Telecom, Banking, IT, etc.
- **Data Collection:** Data is collected from Yahoo Finance public database.
  - **Data Period:** Starting: 1/11/2016 Ending: 22/12/2023.
- **Tools:**
  1. Line Charts
  2. Table
  3. Bar Chart

---

## Key Performance Metrics Table
Page No: 7

- **Total Profit/Loss:** Rs.15,78,108.34
- **Avg. Profit/Loss:** 1397.8
- **Total Return:** 157.81%
- **Annualized Return:** 5.03% CAGR
- **Sharpe Ratio:** -41.17
- **Avg. Bars Held:** 60
- **Gross Recovery Factor:** 35.95
- **Yearly Max Drawdown (%):** 3.39%
- **CAR/MaxDD:** 1.15
- **RAR/MaxDD:** -9.38
- **Profit Factor:** 2.96
- **Payoff Ratio:** 3.89
- **Standard Error:** 29683
- **Standard Deviation:** 441447.3
- **System Max Drawdown:** 4.39%

---

## Yearly Equity Curve
Page No: 8

- The yearly equity curve is steadily upward with a compounded annual growth rate of 5.03%.
- The volatility seems to be low, and the Year Max Drawdown is 3.39%.

---

## System Equity Curve
Page No: 9

- The system equity curve is upward sloping, with some flat portions indicating periods when the trading strategy did not contribute much to the equity curve.
- Notable periods of inactivity are between 2008-2012 (Global Financial Crisis) and 2019-early 2023 (COVID Pandemic).

---

## Distribution of Profit and Loss Trades
Page No: 10

- Out of total trades (1129), 454 trades were profitable.
- Average profit per winning trade is greater than the average loss per losing trade.

---

## Tester’s Opinion
Page No: 10

- The equity curve and max drawdown indicate stability.
- The Sharpe Ratio is negative, suggesting high risk.
- Profit Factor (2.96) and Payoff Ratio (3.89) indicate favorable reward-to-risk ratios.
- The strategy generates a compounded annual growth rate of 5.03%, which is low compared to some risk-free investment options.

---

## Conclusion
Page No: 11

- Strategy optimization is required for the strategy to earn returns exceeding the risk-free rate and the average return generated by Nifty50.

---

**Back-tester Name:** Souman Jyoti (3 years of experience in back-testing)

**Contact:** 9834485979 (WhatsApp Only)

---

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

---
