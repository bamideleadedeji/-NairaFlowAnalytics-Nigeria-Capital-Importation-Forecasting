# NairaFlowAnalytics: Nigeria Capital Importation Forecasting

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](https://github.com/yourusername/NairaFlowAnalytics)

## Project Overview

NairaFlowAnalytics is a comprehensive time series analysis and forecasting system for Nigeria's capital importation data. This project provides insights into historical trends, seasonal patterns, and future projections of capital flows into Nigeria's economy.

### Key Features
- **Data Processing**: Automated cleaning and aggregation of quarterly capital importation data
- **Statistical Analysis**: Comprehensive EDA with trend, seasonality, and volatility analysis
- **Forecasting**: ARIMA modeling with 8-quarter forward projections
- **Visualization**: Professional-grade charts and diagnostic plots
- **Reporting**: Automated generation of analysis reports and executive summaries

## Quick Start

### Installation
```bash
# Clone the repository
git clone https://github.com/bamideleadedeji/NairaFlowAnalytics.git
cd NairaFlowAnalytics

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

Basic Usage
# Run the complete analysis
python run_analysis.py

# Or run in Jupyter Notebook
jupyter notebook Nigeria_Capital_Analysis.ipynb

Analysis Pipeline
Data Loading - Import from CSV/Excel sources

Data Cleaning - Handle missing values, duplicates, and formatting

Time Series Creation - Aggregate to quarterly frequency

Exploratory Analysis - Trend, seasonality, volatility assessment

Model Building - ARIMA/SARIMA model selection and training

Forecasting - 8-quarter projections with confidence intervals

Reporting - Generate comprehensive analysis reports

 Project Structure
NairaFlowAnalytics/
├── data/
│   ├── raw/                    # Raw data files
│   ├── processed/              # Cleaned and processed data
│   └── outputs/                # Analysis outputs and reports
├── notebooks/                  # Jupyter notebooks
│   └── Nigeria_Capital_Analysis.ipynb
├── src/                        # Source code
│   ├── data_processing.py
│   ├── analysis.py
│   ├── forecasting.py
│   └── visualization.py
├── docs/                       # Documentation
├── tests/                      # Test files
├── requirements.txt            # Python dependencies
├── .gitignore                  # Git ignore file
├── LICENSE                     # MIT License
└── README.md                   # This file

 Sample Output
https://docs/images/forecast_plot.png

Technical Details
Models Implemented
ARIMA (AutoRegressive Integrated Moving Average)

SARIMA (Seasonal ARIMA)

Exponential Smoothing

Model comparison with AIC/BIC criteria

Key Metrics
Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

Mean Absolute Percentage Error (MAPE)

Akaike Information Criterion (AIC)

Prerequisites
Python 3.8+

Basic understanding of time series analysis

Familiarity with pandas and matplotlib

Testing
# Run tests
pytest tests/

# Run with coverage
pytest --cov=src tests/

Data Sources
National Bureau of Statistics (NBS), Nigeria

Central Bank of Nigeria (CBN)

World Bank Open Data

IMF Economic Outlook

Use Cases
Economic Policy Planning - Informing monetary and fiscal policy decisions

Investment Analysis - Guiding foreign and domestic investment strategies

Risk Management - Assessing economic vulnerability to capital flow volatility

Academic Research - Supporting economic research on emerging markets

Business Intelligence - Informing corporate strategy and market entry decisions

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
National Bureau of Statistics, Nigeria for data access

Python open-source community for amazing libraries

Contributors and users of this project

Future Enhancements
Real-time data integration

Machine learning models (LSTM, Prophet)

Web dashboard interface

API for programmatic access

Mobile app for on-the-go insights.

https://api.star-history.com/svg?repos=bamideleadedeji/NairaFlowAnalytics&type=Date
