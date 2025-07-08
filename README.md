# stock-analysis-dashboard
An end-to-end stock data analysis dashboard with Python, MySQL, REST API, and interactive frontends in React and Google Apps Script.

## Overview
stock-analysis-dashboard is a modular system for collecting, analyzing, and visualizing stock data across multiple platforms. It allows you to automate stock data retrieval, run technical analysis, expose RESTful APIs, and build interactive dashboards using modern frontend tools.

## Tech Stack
| Layer           | Technology                        | Description                               |
| --------------- | --------------------------------- | ----------------------------------------- |
| Data Fetching   | Python (requests, yfinance, etc.) | Collect stock prices and financial data   |
| Data Storage    | MySQL                             | Store raw and processed stock data        |
| Analysis        | Python (pandas, ta, sklearn)      | Run technical indicators, ML, and signals |
| API             | Flask or FastAPI                  | Serve data to frontend apps               |
| Frontend (Main) | React + Plotly.js                 | Interactive charts and dashboards         |
| Frontend (Alt)  | Google Apps Script                | Spreadsheet-based visualization (GAS)     |

## Project Structure (Example)
stock-analysis-dashboard/
├── backend/
│   ├── fetcher/          # Data fetching scripts
│   ├── analyzer/         # Analysis & indicator logic
│   ├── api/              # FastAPI or Flask API code
│   └── db/               # MySQL setup and queries
├── frontend/
│   └── react-dashboard/  # React-based frontend
├── gas/
│   └── spreadsheet.gs    # Google Apps Script frontend
└── README.md
