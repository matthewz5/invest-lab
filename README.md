# Investment Project - Operations & Performance

![operations_plot](plot_operations.jpg)

This project is a tool for analyzing investment operations and comparing the performance of a selected ETF with major stock indices (S&P 500 and IBOVESPA). It uses Python, `pandas`, `matplotlib`, and `yfinance` to process, visualize, and compare investment data.

## Features

- **Import and process your investment operations** from an Excel file.
- **Fetch historical price data** for any ticker (ETF, stock, or index) using Yahoo Finance.
- **Calculate cumulative investment statistics** such as mean price, balance, and cumulative returns.
- **Visualize your operations** on price charts, including buy/sell markers and mean price lines.
- **Compare your investment performance** with S&P 500 (`^GSPC`, in USD) and IBOVESPA (`^BVSP`, in BRL).

![performance_plot](plot_performance.jpg)

## Requirements

- Python 3.8+
- Jupyter Notebook or VS Code with Jupyter extension
- Packages:
  - `pandas`
  - `matplotlib`
  - `yfinance`
  - `openpyxl` (for Excel file reading)

Install requirements with:
```bash
pip install pandas matplotlib yfinance openpyxl
