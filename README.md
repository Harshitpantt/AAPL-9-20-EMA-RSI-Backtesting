Overview
This Google Colab notebook contains a comprehensive backtesting implementation for a trading strategy based on the 9-day and 20-day Exponential Moving Averages (EMA) combined with the Relative Strength Index (RSI) for Apple Inc. (AAPL) stock.

Strategy Description
The trading strategy uses the following technical indicators and rules:

Indicators Calculated:
EMA 9: 9-day Exponential Moving Average

EMA 20: 20-day Exponential Moving Average

RSI: 14-day Relative Strength Index

Trading Signals:
Buy Signal: When EMA 9 crosses above EMA 20 AND RSI > 50

Sell Signal: When EMA 9 crosses below EMA 20 AND RSI < 50

Colab Setup
This notebook is designed to run in Google Colab and includes:

Automatic Installation:
python
!pip install yfinance ta-lib pandas numpy matplotlib
Features:
✅ Runs directly in Google Colab environment

✅ Automatic package installation

✅ Cloud-based execution

✅ Interactive plotting with matplotlib

✅ Direct data fetching from Yahoo Finance

Data Source
Ticker: AAPL (Apple Inc.)

Period: January 1, 2018 to January 1, 2025

Source: Yahoo Finance via yfinance

How to Use in Colab
Method 1: Upload to Colab
Download the .ipynb file

Go to Google Colab

Upload the file: File → Upload notebook

Run all cells: Runtime → Run all

Method 2: Direct GitHub Integration
Upload to your GitHub repository

Open Colab and use: File → Open notebook → GitHub

Paste your repository URL

Method 3: Copy-Paste Code
Create new Colab notebook

Copy and paste code cells from the original file

Run sequentially

Key Outputs
Technical indicators (EMA 9, EMA 20, RSI) calculation

Trading signals and positions

Market returns vs Strategy returns comparison

Cumulative performance visualization

Performance metrics analysis

Colab-Specific Features
Automatic dependency resolution

Cloud storage integration

Interactive matplotlib plots

No local installation required

Free GPU/TPU access (if needed)

Requirements
The notebook automatically installs:

python
yfinance      # Financial data
ta-lib        # Technical analysis
pandas        # Data manipulation
numpy         # Numerical computing
matplotlib    # Visualization
Important Notes
Colab sessions are temporary - Download results before ending session

Runtime may disconnect - Save progress frequently

Free tier limitations - Consider runtime constraints

Data persistence - Re-run data fetching cells if session restarts

Performance Tips for Colab
Use GPU runtime for large computations: Runtime → Change runtime type → GPU

Mount Google Drive for saving results

Download important plots and data before session ends

Use %matplotlib inline for inline plotting

File Structure in Colab
Package installation cell

Import libraries

Data downloading and preprocessing

Technical indicator calculations

Signal generation logic

Backtesting implementation

Performance visualization

Results analysis

Disclaimer
This is an educational backtesting implementation for demonstration purposes. Past performance does not guarantee future results, and proper risk management should always be applied in live trading.

Ready to run in Google Colab! 🚀
