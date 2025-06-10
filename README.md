# Panic Price Project

This project explores whether global outbreaks like COVID-19, SARS, and Ebola had any effect on financial markets, especially the S&P 500. The idea was to see if public interest (measured through Google search trends) had any connection with market behavior like average returns or volatility.

## Data Sources

- **Google Trends**: Monthly search interest for outbreak-related terms
- **Yahoo Finance**: Daily and monthly S&P 500 returns (via `yfinance`)
- **Outbreak Timelines**: Manually created datasets with start/end dates and key events (WHO alerts, etc.)

## What I Did

- Cleaned and merged trends and financial data
- Created flags for outbreak periods and events
- Made multiple visualizations (timelines, trends vs. returns, correlation heatmaps)
- Ran t-tests and regression to check if trends predict returns

## Key Findings

- No statistically significant impact of outbreaks on returns or volatility
- Search trends (like for COVID) didn’t reliably predict future market performance

## Files

- `data/`: Cleaned trend and financial data
- `analysis/`: Plots, test results, and visual summaries
- `data_prep_final_commented.ipynb`: Main notebook with full code and comments

## In Progress

I’m working on building a Power BI dashboard to make the analysis interactive.
