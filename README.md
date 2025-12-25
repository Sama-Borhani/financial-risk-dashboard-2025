# Financial Risk Monitoring Dashboard (2025)

Financial risk monitoring project analyzing an equal-weighted equity portfolio using daily 2025 market data. Implements annualized return/volatility, Sharpe ratio, VaR (95%/99%), drawdowns, and rolling risk metrics using Python and Power BI.

## Key Findings (2025)
- Annualized return: ~17%
- Annualized volatility: ~22%
- Sharpe ratio: ~0.59
- 1-day 95% VaR: ~-14.7%
- Max drawdown: ~-33%
- Rolling 30D volatility peaked above ~60% during stress periods

## Repository Structure
- `outputs/`: exported PDF report
- `notebooks/`: data extraction notebook (yfinance)
- `data/raw/`: extracted price data (CSV) *(optional)*
- `powerbi/`: Power BI file *(optional)*

## How to Reproduce
1. Run the notebook in `notebooks/` to download 2025 daily price data.
2. Load exported data into Power BI (if using the `.pbix`) or review the PDF in `outputs/`.

