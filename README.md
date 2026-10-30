# CAC-40-Analysis

I wanted to see which large French stocks gave the best return for the risk taken over
the last five years, and whether simply holding an equal mix of them would have beaten
the CAC 40

<img width="1006" height="508" alt="image" src="https://github.com/user-attachments/assets/4e931382-6cb8-435b-b4a8-c60b82d2c29d" />

I picked 10 stocks from different sectors (TotalEnergies, LVMH, Hermès, L'Oréal, Sanofi,
Airbus, BNP Paribas, Schneider Electric, Air Liquide, Capgemini) and compared them with
the index, using sata from Yahoo Finance between January 2021 and
December 2025

# What I found

- The equal-weight portfolio almost doubled over the period, while the CAC 40 rose by about 50%.
  That's 14.6% a year against 8.7%, for almost the same volatility (17.2% vs 16.1%).
- Its Sharpe ratio is 0.73, against 0.42 for the index
- Most of the gain came from a few stocks: BNP Paribas, Hermès, Airbus, TotalEnergies
- Diversification works even with 10 stocks: most of them move around 25% a year on their own,
  but together they are almost as stable as the whole index

## Limits

- The stock prices include dividends but the CAC 40 index doesn't, which can explain about 3% a year of the gap
- The stocks come from today's CAC 40, so they're all companies that did well enough to stay in it (survivorship bias)
- The portfolio is rebalanced every day for free, which isn't possible in real life
- Five years is a short period
