Global Tech ETF Analysis

This repository contains a data analysis project focused on long-term performance trends in major global technology exchange-traded funds (ETFs). The objective is to build a clear, reproducible workflow for retrieving market data, visualizing historical movements, and gradually expanding toward basic portfolio analysis.

The initial scope includes three widely recognized technology-related ETFs:

QQQ — Nasdaq-100

VGT — Vanguard Information Technology ETF

SOXX — iShares Semiconductor ETF

These funds represent different areas within the technology sector, ranging from broad exposure to more concentrated semiconductor holdings.

1. Project Overview

The purpose of this project is to examine long-term price behavior of major technology ETFs and provide a simple but structured foundation for further financial analysis.
The project begins with essential time-series retrieval and visualization and will expand incrementally to include basic backtesting components and performance metrics.

This repository is intended to remain lightweight, cleanly organized, and easy to extend.

2. Current Features

The initial notebook implements the following:

Retrieval of historical price data using yfinance

Data alignment and preparation for analysis

Visualization of long-term price trends for QQQ, VGT, and SOXX

These steps provide a preliminary view of historical performance across different types of technology ETFs.

3. Planned Enhancements

Future updates will extend the scope of the analysis. Planned components include:

Buy-and-hold return simulations

Monthly contribution (DCA) modeling

Performance metrics:

CAGR

Volatility

Maximum drawdown

Basic risk-adjusted comparisons

Inclusion of additional ETFs for broader comparison

Optional interactive dashboard for displaying results

Each addition will be implemented gradually to maintain clarity and readability.

4. Project Structure
Global-Tech-ETF-Backtesting-Trend-Analysis/
│
├── Global_Tech_ETF_Analysis.ipynb     # Main analysis notebook
└── README.md                          # Project documentation


The structure is intentionally simple at this stage and will be updated as analysis becomes more detailed.

5. Tools and Libraries

Python

Google Colab

pandas

yfinance

matplotlib

These tools were selected to keep the workflow accessible and reproducible without complex environment setup.

6. Notebook

Main analysis notebook:
Global_Tech_ETF_Analysis.ipynb

The notebook currently focuses on data retrieval and long-term trend visualization. Future iterations will incorporate backtesting and extended metrics.

7. Notes

This project is a work in progress.
Updates will be added progressively as new features are developed and tested.

8. Author

Jacqueline Song
