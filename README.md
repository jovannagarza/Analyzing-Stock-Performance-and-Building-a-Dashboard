## Analyzing-Stock-Performance-and-Building-a-Dashboard-
## Stock Performance Dashboard

This project analyzes the historical performance and revenue trends of four major stocks: **Tesla**, **Amazon**, **AMD**, and **GameStop**. It simulates the role of a data scientist at an investment startup, using financial data to support smarter investment decisions.

## Highlights

- Extracted stock price data using the `yfinance` API
- Scraped revenue data using `BeautifulSoup`
- Visualized price and revenue trends using Plotly
- Built an interactive dashboard for stock performance analysis

## Tools Used

Python, Pandas, yfinance, BeautifulSoup, Plotly, JupyterLab

## Project Files

| Notebook | Purpose |
|----------|---------|
| `1) Extracting Stock Data Using a Python Library.ipynb` | Pull historical stock data |
| `2) Extracting Stock Data Using Web Scraping.ipynb` | Scrape quarterly revenue |
| `3) Extracting and Visualizing Stock Data.ipynb` | Merge and visualize trends |

## Run Locally

1. Clone the repo:
```bash
git clone https://github.com/your-username/stock-performance-dashboard.git
cd stock-performance-dashboard
pip install yfinance beautifulsoup4 plotly pandas
jupyter lab
