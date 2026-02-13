# Trader Behavior vs Market Sentiment – Analysis Summary

## Methodology
- Cleaned and processed Bitcoin Fear/Greed Index and Hyperliquid historical trade data.
- Converted timestamps and aligned datasets at daily level.
- Engineered daily trader metrics: PnL, trade frequency, average trade size, and long-short bias.
- Compared trader behavior and performance across Fear and Greed sentiment regimes.
- Segmented traders based on activity and profitability.
- Built a machine learning model to predict daily trader profitability.

## Key Insights
1. Traders generate significantly higher profits during Greed sentiment days, but risk and volatility are also higher.
2. During Fear periods, traders reduce trade frequency and average trade sizes, indicating risk-off behavior.
3. High-activity traders outperform during Greed markets but suffer deeper losses during Fear regimes.
4. Trade frequency and average trade size are strong predictors of trader profitability.

## Strategy Recommendations
1. **Fear Regime Strategy**
   - Reduce trade frequency
   - Lower position sizes
   - Focus on high-probability setups

2. **Greed Regime Strategy**
   - Increase trade frequency moderately
   - Maintain disciplined risk management
   - Prefer trend-following strategies

## Bonus – Predictive Modeling
A Random Forest classifier was trained to predict daily profitability using behavioral features. Results indicate that trade frequency and position sizing carry strong predictive power.
