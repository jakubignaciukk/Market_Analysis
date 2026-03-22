# Market_Analysis
Python data analysis of macroeconomic correlations between US Banks, EU Auto, and Semiconductor sectors using yfinance.

**What I analyzed:**
- Normalized price comparison across sectors
- 30-day rolling volatility
- Correlation matrix within and between sectors

**Key findings:**
- COVID crash caused simultaneous volatility spike across all sectors
- Highest correlation within sectors, lower cross-sector
- **Stellantis anomaly:**
  Stellantis shows an unusually high correlation with US Banks - possibly because 
it sells lower-segment cars (Fiat, Opel) more dependent on consumer credit, 
unlike BMW and Mercedes which target wealthier buyers. Its customers may be 
more sensitive to the same macroeconomic factors that drive bank stocks.

**Tools:** Python, Pandas, Matplotlib, Seaborn, yfinance

**Data source:** Yahoo Finance via yfinance library
