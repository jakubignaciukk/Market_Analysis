# Market_Analysis
Python data analysis of macroeconomic correlations between US Banks, EU Auto, and Semiconductor sectors using yfinance.

**What I analyzed:**
- Normalized price comparison across sectors
- 30-day rolling volatility
- Correlation matrix within and between sectors
- Hypotesis test: mass-market vs premium auto correlation with US Banks

**Key findings:**
- COVID crash caused simultaneous volatility spike across all sectors
- Highest correlation within sectors, lower cross-sector
- **Stellantis anomaly:**
  Stellantis shows an unusually high correlation with US Banks - possibly because 
it sells lower-segment cars (Fiat, Opel) more dependent on consumer credit, 
unlike BMW and Mercedes which target wealthier buyers. Its customers may be 
more sensitive to the same macroeconomic factors that drive bank stocks.
- **Hypothesis Testing & Geographic Exposure (Update):**
  To test the credit-sensitivity hypothesis, the analysis was expanded to include Ford, VW, Renault, and Porsche. The results showed that while US-exposed mass-market brands (Stellantis, Ford) correlate heavily with US Banks, European-focused mass brands (VW, Renault) do not. **Conclusion:** Geographic exposure to the US market (where auto purchases are highly debt-driven) dictates this correlation much more than the vehicle price segment alone.

**Tools:** Python, Pandas, Matplotlib, Seaborn, yfinance

**Data source:** Yahoo Finance via yfinance library
