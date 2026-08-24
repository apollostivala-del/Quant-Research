Quant Research
Quantitative trading research tools — Monte Carlo simulations, walk-forward analysis, and risk modeling for algo traders. Built in Python using real futures trade history.

Tools
Topstep $50K Challenge — Monte Carlo Probability Simulator
topstepmc.ipynb
Simulates thousands of Topstep Trading Combine attempts by bootstrapping real daily P&L from your own trade history. Answers the question: what are your actual odds of passing, getting funded, and generating payouts?
What it produces:

Pass / blown / gave up rate across N simulations
Days to pass distribution
200 sample equity path chart vs profit target and max loss
Funded account payout distribution
Full expected value breakdown — cost if pass vs fail, EV per attempt
Fee option comparison (Standard vs Express)

How to use:

Export your trade history as a CSV with Entry Time, Exit Time, P&L columns
Set TRADES_CSV to your file path in the config cell
Adjust the Topstep rules in the config if needed (profit target, max loss, fees)
Run all cells

Requirements:
pip install pandas numpy matplotlib scipy

Coming Soon

Walk-Forward Sharpe vs Starting Capital analyzer
3D Monte Carlo equity surface and risk landscape
Strategy robustness tester (10k random OOS splits)


Notes

All simulations use bootstrapped historical daily P&L — results depend entirely on the quality of your trade history
Past performance does not guarantee future results
This is research tooling, not financial advice
