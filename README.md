# NASDAQ-100 Stock Clustering & Investment Simulator

## Why This Project?

Investors face the challenge of navigating a large number of stocks without clear guidance on which are safe, risky, or high growth. **The NASDAQ-100** contains some of the most important technology and growth companies in the world, but their behavior varies greatly.

This project aims to:

- Analyze **NASDAQ-100 stock** data (2022–2024)
- Measure returns, risk, and volatility
- Group stocks into clusters so investors can easily compare risk/return profiles
- Provide an interactive investment simulator so anyone can test how their money might perform

This project helps transform raw financial data into **actionable insights for decision-making**.

--
## Methodology

**1. Data Collection**

- Stock prices downloaded using yfinance

- Period covered: 2022-01-01 to 2024-12-31

**2. Feature Engineering**

- Daily & Weekly Returns

- Volatility (7-day & 21-day rolling standard deviation)

- Cumulative Returns

- Annualized Returns

**3. Clustering (KMeans)**

- Stocks grouped into 4 categories based on risk & return

- PCA used to reduce dimensions and visualize clusters

**4. Investment Simulator**

- Choose stock(s)

- Enter investment amount

- Select duration (days)

- See expected returns & cluster profile
