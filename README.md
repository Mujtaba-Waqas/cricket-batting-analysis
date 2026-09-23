# cricket-batting-analysis
# ODI Batting Performance Analysis

**Question:** What batting traits are most strongly associated with elite
ODI performance, and how do India and Pakistan compare on scoring speed?

## Method
- Sample restricted to qualified batters (1,000+ career ODI runs)
- Constructed boundary rate and century rate from raw counts
- Summary statistics, histogram, groupby team collapse, and crosstab
- Welch's t-test comparing India vs Pakistan mean strike rate
- Two OLS regressions: strike rate on boundary rate;
  batting average on century rate

## Key findings
- India's mean strike rate is significantly higher than Pakistan's
  in the qualified sample (5% significance level)
- India has the highest mean career runs among the nine major teams

## Stack
Python · pandas · NumPy · SciPy · statsmodels · Matplotlib

## Files
- `cricket_batting_analysis.ipynb` — full analysis
- `batting_stats.csv` — dataset
