# 📈 Trading Performance & Market Sentiment Analysis

This project explores the relationship between trader performance and market sentiment using the Fear & Greed Index, uncovering hidden patterns for data driven trading strategies.

---

## 📋 Overview

The analysis examines how market sentiment (as measured by the Fear & Greed Index) affects trading behavior, performance, and profitability. It aims to identify optimal trading strategies across different market sentiment conditions and time periods.

---

## 📁 Data Sources

- `fear_greed_index.csv`: Historical Fear & Greed Index data with sentiment classifications
- `historical_data.csv`: Trading performance data with transaction details

---

## ✅ Key Analyses Performed

### 1. Sentiment Shift Analysis
- Analyzes how changes in market sentiment (e.g., Fear ➝ Neutral) affect P&L distribution and trading behavior.
- **Insight**: Traders perform better during improving sentiment regimes, especially when transitioning out of fear.

### 2. Volatility Analysis
- Assesses how volatility and risk-adjusted returns vary with sentiment phases.
- Includes time-series overlays of volatility with sentiment categories.
- **Insight**: Neutral sentiment periods often balance volatility and profitability effectively.

### 3. Performance Consistency Analysis
- Evaluates trader consistency using Win Rate, Mean vs Median P&L, and a custom Consistency Score.
- **Insight**: Positive sentiment leads to higher consistency and lower variance in performance.

### 4. Sentiment Duration Analysis
- Studies how the **length of sentiment phases** impacts trader performance.
- **Insight**: Longer stable sentiment periods—especially bullish—enable better returns and fewer losses.

### 5. Long vs Short Strategy Analysis
- Compares how long and short strategies perform under different sentiments.
- **Insight**: Long trades outperform in Greed/Positive conditions; short strategies are effective during Negative phases.

### 6. Risk-Reward Analysis
- Focuses on profit quality: Risk-Reward Ratio, Expectancy, Profit Factor, etc.
- **Insight**: Positive sentiment provides the highest reward per risk unit; consistency is highest in Neutral/Positive phases.

### 7. Asset-Specific Sentiment Analysis
- Measures sentiment-performance correlation for individual coins.
- Identifies best and worst sentiment conditions per asset.
- **Insight**: Some assets thrive under specific sentiment regimes, enabling strategy customization.

---

## 📊 Visualizations Table

| Module                        | Visualization Title                                         | Chart Type              | Insight Type             |
|------------------------------|-------------------------------------------------------------|-------------------------|--------------------------|
| **Sentiment Shift**          | P&L by Sentiment Shift Type                                | Boxplot                 | Distributional           |
|                              | Fear & Greed Index Over Time                               | Time Series             | Contextual/Trend         |
|                              | Metrics by Sentiment Shift Type                            | Bar Chart               | Comparative              |
| **Volatility**               | P&L Volatility by Sentiment                                | Bar Chart               | Risk Profile             |
|                              | Risk-Adjusted Return                                       | Bar Chart               | Return Quality           |
|                              | P&L Distribution by Sentiment                              | Boxplot                 | Variance Analysis        |
|                              | Rolling Volatility Over Time                               | Scatter                 | Time Series Volatility   |
| **Performance Consistency**  | Win Rate Across Sentiments                                 | Bar Chart               | Reliability              |
|                              | Consistency Score                                           | Bar Chart               | Stability Index          |
|                              | Mean vs Median PnL                                          | Bar Chart               | Skewness                 |
|                              | Sentiment Consistency Distribution                         | Pie Chart               | Segment Distribution     |
| **Sentiment Duration**       | Avg PnL by Duration Category                               | Bar Chart               | Holding Period Benefit   |
|                              | Duration Frequency Histogram                               | Histogram               | Behavioral Insight       |
|                              | Total PnL by Duration                                      | Bar Chart               | Profit Accumulation      |
|                              | Avg PnL Heatmap (Sentiment × Duration)                     | Heatmap                 | Interaction Effect       |
| **Long/Short Strategy**      | Avg PnL by Strategy                                        | Bar Chart               | Comparative              |
|                              | Win Rate by Strategy                                       | Bar Chart               | Effectiveness            |
|                              | Total PnL by Strategy                                      | Bar Chart               | Aggregate Performance    |
|                              | Risk vs Return by Strategy                                 | Scatter                 | Trade-Off Analysis       |
| **Risk-Reward**              | Risk-Reward Ratio                                          | Bar Chart               | Efficiency Metric        |
|                              | Profit Factor                                              | Bar Chart               | Risk Quality             |
|                              | Win Rate vs Risk-Reward                                    | Scatter                 | Strategy Segmentation    |
|                              | Expectancy                                                 | Bar Chart               | Predictive Value         |
|                              | Avg Win vs Avg Loss                                        | Bar Chart               | Reward vs Pain           |
|                              | Total P&L                                                  | Bar Chart               | Strategy Worth           |
| **Asset-Specific Analysis**  | Sentiment-PnL Correlation per Asset                        | Bar Chart               | Sensitivity              |
|                              | Best/Worst Sentiment Period per Asset                      | Table / Summary         | Optimization             |
|                              | Avg PnL by Asset & Sentiment                               | Grouped Bar Chart       | Strategic Alignment      |
|                              | Performance Heatmap                                        | Heatmap                 | Sentiment Effectiveness  |
|                              | Win Rate by Asset & Sentiment
