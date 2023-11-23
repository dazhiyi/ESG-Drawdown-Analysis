# ESG Risk Ratings Correlation with DrawDown Beta 📈

## Project Overview 🎯
This project, led by Zhiyi Da, focuses on the correlation between ESG risk ratings and various portfolio risk measures, specifically DrawDown Beta. The study replicates and extends the methodologies of Ding and Uryasev (2022) related to DrawDown Beta and Portfolio Optimization.

## Objectives 🎯
- Implement and analyze the DrawDown Beta as per Ding and Uryasev (2022).
- Investigate the correlation of ESG risk ratings with:
  - Standard Beta ERoD0+
  - Beta CDaR0.9
  - Beta Maximum Drawdown
  - Annual Return

## Methodology 🔍
- Calculations based on the ESG ratings from Sustainalytics across different categories (Negligible, Low, Medium, High, Severe risk).
- Utilization of Python’s `yfinance` package for data extraction.
- Implementation of various risk measures (ERoD Beta, CDaR Beta, Maximum Drawdown) for analysis.
- Correlation analysis using Pearson and Spearman methods.

## Key Findings 💡
- Correlations observed between ESG ratings and the mentioned risk measures.
- Identification of performance differences among various ESG rating categories.
- Notable findings in extreme ESG rating categories (Negligible and Severe) due to small sample sizes.

## Limitations and Future Work 🚧
- Further analysis required due to limited data in extreme ESG categories.
- Potential expansion of study to include a larger dataset or international companies.

## References 📚
- Ding, R. and Uryasev, S. (2022). Drawdown beta and portfolio optimization. Quantitative Finance, pages 1–12.
- Zabarankin, M., Pavlikov, K., and Uryasev, S. (2014). Capital asset pricing model (CAPM) with drawdown measure. European Journal of Operational Research, 234(2):508–517.
