# Trader-Behavior-Insights

This repository contains analysis of trader performance vs market sentiment.
1. Overview
This project analyzes the relationship between market sentiment (Fear & Greed Index) and trader performance (PnL, leverage, and trade behavior) using real historical trading data from Hyperliquid. The objective   is to uncover whether trader outcomes and decisions are influenced by market psychology — specifically periods of Fear and Greed — and to identify actionable trading insights and behavioral patterns.

2. Datasets
Fear & Greed Index Dataset
Columns include:
date
classification (Fear / Greed)
This dataset provides daily sentiment classification for the crypto market

3. Data Preparation
Key preprocessing steps:
Converted timestamp fields to consistent date format
Normalized side labels (e.g., LONG / SHORT)
Merged trading data with sentiment data on the date field
Cleaned missing values and incorrect entries
Engineered useful fields such as:
win (boolean for positive PnL)
Aggregated performance metrics

4. Methodology
The analysis includes:
Descriptive statistics
Comparative analysis of Fear vs Greed periods
Leverage behavior assessment
PnL distribution analysis
Long vs Short position outcome comparisons
Visualization of performance trends
Behavioral analysis of trader decisions
Python libraries used:
Pandas
NumPy
Matplotlib / Seaborn
Jupyter Notebook

5. Key Insights
1. Profitability increases during Greed periods
Traders earn higher average PnL when market sentiment is optimistic.
2. More losses occur during Fear
Choppy price action and uncertainty reduce trade success during Fear.
3. Win rate is significantly higher in Greed
Clear market direction boosts trading performance.
4. Traders use higher leverage during Greed
Risk-taking behavior increases during market optimism.
5. Long vs Short behavior
Long positions perform best in Greed.
Short positions perform best in Fear.
6. Behavioral biases observed
Trend-chasing behavior in Greed.
Defensive, risk-averse trading in Fear.
Overconfidence drives high leverage in Greed.
