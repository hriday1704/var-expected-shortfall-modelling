# Value-at-Risk (VaR) & Expected Shortfall Modelling

This project implements quantitative market risk modelling techniques on a multi-asset Indian equity portfolio using Python and real market data from Yahoo Finance.

The project compares Historical Simulation and Monte Carlo Simulation approaches for estimating portfolio downside risk and tail-risk exposure.

---

## Features

- Multi-asset Indian equity portfolio construction
- Historical Value-at-Risk (VaR) at 95% and 99% confidence levels
- Expected Shortfall (Conditional VaR) estimation
- Monte Carlo Simulation using Geometric Brownian Motion (GBM)
- 10,000+ simulated market scenarios
- Tail-risk visualization and risk comparison analysis
- Historical vs Monte Carlo risk modelling comparison

---

## Technologies Used

- Python
- pandas
- NumPy
- SciPy
- Matplotlib
- yfinance

---

## Portfolio Constituents

- Reliance Industries
- TCS
- Infosys
- HDFC Bank
- ICICI Bank

---

## Risk Models Implemented

### Historical Value-at-Risk (VaR)

Estimated downside portfolio risk using historical portfolio returns at:

- 95% confidence level
- 99% confidence level

### Expected Shortfall (Conditional VaR)

Measured average tail-loss beyond the VaR threshold to capture extreme downside risk.

### Monte Carlo Simulation

Generated 10,000+ simulated portfolio return scenarios using:

- Geometric Brownian Motion (GBM)
- Random normal shock generation
- Volatility-based risk modelling

### Historical vs Monte Carlo Comparison

Compared:

- Historical VaR
- Monte Carlo VaR
- Historical Expected Shortfall
- Monte Carlo Expected Shortfall

to evaluate different market risk estimation approaches.

---
## Project Visualizations

### Historical VaR and Expected Shortfall

![VaR ES](<img width="994" height="544" alt="image" src="https://github.com/user-attachments/assets/59b352e6-d3d2-467c-8357-469c488c2a82" />)

### Monte Carlo Simulation Distribution

![Monte Carlo](<img width="1004" height="546" alt="image" src="https://github.com/user-attachments/assets/89c32360-a345-4fce-9bb1-c44198401a98" />)

### Risk Metrics Comparison

![Risk Comparison](<img width="1248" height="529" alt="image" src="https://github.com/user-attachments/assets/3cb76932-ffde-4821-8636-9d3814981574" />)

---

## Key Learnings

- Tail-risk measurement in financial markets
- VaR and Expected Shortfall interpretation
- Monte Carlo simulation techniques
- Geometric Brownian Motion modelling
- Portfolio risk analytics using Python
- Historical vs probabilistic risk estimation

---

## Future Improvements

- Correlated Monte Carlo simulations
- GARCH-based volatility modelling
- Stress testing framework
- Portfolio optimization integration
- Interactive risk dashboard using Streamlit

---

## Author

Hriday  
B.Tech Computer Engineering — NMIMS Navi Mumbai
