# Finn Mester

**Business student at KEDGE Business School (International BBA), heading for investment banking and markets.**
I test financial models against real market data, measure where they break, and publish what did not work.

Looking for a 2027 internship in investment banking, sales & trading or market risk.
[LinkedIn](https://www.linkedin.com/in/finn-mester) · German (native), French, English

---

## At a glance

- Top 10% of my year: ranked 42nd out of 490
- Bloomberg Market Concepts (BMC) certified
- TOSA Excel certified
- Three research projects in Python, each result checked against a closed form or a statistical test

---

## Projects

### [Black-Scholes vs. the market](https://github.com/finn-mester/black-scholes-vs-market)
*Does a single volatility price every S&P 500 option, as Black-Scholes assumes? No, and the project measures by how much.*

- Pricing, Greeks, Monte Carlo, implied volatility and a binomial tree, written without any pricing library
- 1-month skew of 11.9 vol points against a median bid-ask of 0.11: the smile is real, not noise
- 17 daily moves beyond 4 standard deviations in 10 years, where a normal distribution predicts 0.16
- Cleaned live quotes with put-call parity, which flagged 88 stale strikes on a day the index fell 2.4%

### [Monte Carlo for pricing and market risk](https://github.com/finn-mester/monte-carlo-finance)
*From pricing exotics to backtesting VaR, with an error bar on every number.*

- Asian and barrier options; a control variate cuts variance 1,010x on the Asian
- Antithetic and control variates combined: 32x less variance on a European call
- VaR and Expected Shortfall on a EUR 1M portfolio of five CAC 40 stocks, backtested over 3,285 days: the normal model understates the tail, and every model breaks at 99% in the 2015 and 2020 stress periods

### [Volatility regimes with hidden Markov models](https://github.com/finn-mester/hmm-volatility-regimes)
*Can detecting calm and turbulent regimes beat buy-and-hold on gold, the S&P 500 and Treasuries?*

- Found a look-ahead bug that created about +18%/year of fake alpha; once fixed, the strategy trailed buy-and-hold by about 11%/year
- Pass/fail criteria set before testing, 10 bp transaction costs, out-of-sample test on 2026 data
- Negative result published as is, with a 3-page research note in English

---

## Toolkit

Python (NumPy, SciPy, pytest) · Excel · Bloomberg Terminal · Git and GitHub Actions · LaTeX

<!--
**finn-mester/finn-mester** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
