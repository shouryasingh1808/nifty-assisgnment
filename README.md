# NIFTY 50 Crash Recovery Quantitative Research Study

This repository contains the code, research documentation, and validation files for the quantitative evaluation of the NIFTY 50 index's recovery tendencies following significant one-day drawdowns.

## Project Overview
* **Objective:** Investigate whether NIFTY 50 reliably recovers over the following 1, 3, and 5 trading days after a daily drop of -2.0% or worse[cite: 1].
* **Dataset:** Daily OHLC data for `^NSEI` (2011–2026) sourced via Yahoo Finance[cite: 1].
* **Key Finding:** The observed post-fall bounce (e.g., 58.5% 3-day win rate) is **not statistically significant** (p > 0.05 via Welch's T-Test) when compared against market baselines and validated via chronological out-of-sample splitting.

## Repository Contents
- `Nifty_assisgnment.ipynb`: Step-by-step research notebook.
- `Research_Note.pdf`: Comprehensive 2-page final research report[cite: 1].
- `AI_Usage_Note.pdf`: Disclosure of AI collaboration tools used.
- `requirements.txt`: Python package dependencies.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `Nifty_assisgnment.ipynb` in Google Colab or Jupyter and run all cells.
