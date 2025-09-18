# Financial Report Analysis — Industry Comparison of Profitability & Leverage

An analysis of financial statement data (income statement + balance sheet) for companies across different industries, to compare profitability and leverage ratios and explore how industry type correlates with financial health.

---

## What’s Inside

- Python scripts for computing key financial ratios across companies  
- Industry group comparisons (e.g., FMCG, Real Estate, etc.)  
- Visualizations (plots & pivot comparisons) of profitability vs. leverage  
- Excel / raw statement data for balance sheets & income statements  

---

## Tools & Techniques Used

- Python (pandas for data manipulation, seaborn & matplotlib for visualization)  
- Financial ratio calculation: gross margin, debt-to-equity, etc.  
- Pivot tables & grouping to compare across industries  
- Data cleaning: handling missing values, standardizing fields, removing outliers  

---

## Problem & Business Impact

Companies, investors, and analysts often look only at basic revenue or net income numbers, which don’t capture underlying risk or capital structure. Without comparing profitability alongside leverage, it’s hard to assess financial stability or identify over-leveraged businesses. This project helps:

- Reveal which industries are more profitable on average  
- Identify industries with high leverage (potential risk)  
- Provide comparative insights to drive investment or strategic decisions  

---

## Approach / Workflow

1. **Data Collection & Preparation**  
   - Gathered financial statements (Income Statement, Balance Sheet) for companies in multiple industries.  
   - Cleaned data: standardizing column names, handling missing or anomalous values.  

2. **Ratio Calculation**  
   - Calculated *Gross Margin* = (Revenue − COGS) / Revenue  
   - Calculated *Debt-to-Equity* = Total Liabilities / Shareholders’ Equity  

3. **Industry Grouping & Comparison**  
   - Grouped companies by industry type (e.g. FMCG, Real Estate, etc.)  
   - Used pivot / aggregate functions to compute average, median, and variation in ratios across industries.  

4. **Visualization & Insights**  
   - Created plots (scatter / bar / boxplots) to show distribution of profitability and leverage.  
   - Identified correlations and outliers.

---

## Key Findings

- FMCG (Fast Moving Consumer Goods) companies exhibited **lowest average profitability**, though with moderate leverage.  
- Real Estate companies had among the **highest leverage ratios**, coupled with highly variable profitability.  
- There’s a **positive correlation** in some industries between high leverage and high profitability; in others, high leverage corresponds with volatility.  
- Outliers exist: certain firms significantly underperform / over-leverage versus their industry peers.

---

## Recommendations & Takeaways

- Investors should carefully evaluate **leverage alongside profitability**, especially in high-leverage sectors like real estate.  
- Companies in low profitability industries should prioritize debt management and cost control.  
- Further work could incorporate **trend / time series** analysis to see how these ratios evolve over years.  
- Additional metrics (e.g. liquidity ratios, return on equity, interest coverage) would add nuance.  


