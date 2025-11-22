# News Sentiment & Stock Movement Analysis

## 📊 Project Overview
A comprehensive quantitative analysis platform for stock market data using technical indicators and financial metrics. This project combines exploratory data analysis with advanced technical analysis to provide actionable trading insights.

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation
`bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

## Requirements

### Key dependencies include:

· pandas, numpy - Data manipulation
· matplotlib, seaborn - Visualization
· TA-Lib - Technical indicators
· jupyter - Notebook environment

## 📁 Project Structure

project/
├── notebooks/           # Jupyter notebooks
│   ├── eda.ipynb       # Exploratory Data Analysis
│   └── task2_analysis.ipynb  # Technical Analysis
├── src/                # Source code modules
├── data/               # Stock data files
├── tests/              # Unit tests
├── requirements.txt    # Dependencies
└── README.md          # Project documentation

## 📓 Notebooks

### 1. Exploratory Data Analysis (eda.ipynb)

Purpose: Initial data exploration and insights

· Data loading and validation
· Statistical summaries
· Price and volume trends
· Correlation analysis
· Data quality checks

### 2. Technical Analysis (task2_analysis.ipynb)

Purpose: Advanced quantitative analysis

· TA-Lib indicators (SMA, RSI, MACD, Bollinger Bands)
· Trading signal generation
· Risk assessment metrics
· Comprehensive visualizations
· Performance reporting

## 📈 Key Features

### Technical Indicators

· Trend Analysis: Moving averages, MACD
· Momentum: RSI, Stochastic Oscillator
· Volatility: Bollinger Bands, ATR
· Volume Analysis: Volume trends and patterns

### Analytics Capabilities

· Automated trading signals
· Multi-timeframe analysis
· Risk and volatility assessment
· Performance tracking and reporting

### Visualization

· Interactive charts and dashboards
· Professional technical analysis plots
· Correlation heatmaps
· Returns distribution analysis

### 🎯 Usage

1. Start with EDA: Run eda.ipynb to understand your data
2. Proceed to Analysis: Use task2_analysis.ipynb for technical insights
3. Generate Reports: Export analysis results and trading signals

### 📊 Data Format

Required CSV columns:

· Date (datetime)
· Open, High, Low, Close (prices)
· Volume (trading volume)
