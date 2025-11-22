# Financial Technical Analysis Dashboard

## 📊 Project Overview
A comprehensive quantitative analysis toolkit for stock market data using technical indicators and financial metrics. This project provides both exploratory data analysis and advanced technical analysis capabilities.

## 📁 Notebook Structure

### 1. eda.ipynb - Exploratory Data Analysis
Purpose: Initial data exploration and basic analysis

Contents:
- Data loading and cleaning
- Basic statistical analysis
- Price trend visualization
- Volume analysis
- Correlation studies
- Data quality checks

Key Features:
- Missing value analysis
- Distribution plots
- Time series decomposition
- Outlier detection
- Basic performance metrics

### 2. task2_analysis.ipynb - Advanced Technical Analysis
Purpose: Comprehensive quantitative analysis using TA-Lib and financial metrics

Contents:

#### 🔧 Technical Indicators (TA-Lib)
- Trend Analysis:
  - Simple Moving Averages (SMA 20, SMA 50)
  - Exponential Moving Averages (EMA 12, EMA 26)
  - MACD (Moving Average Convergence Divergence)

- Momentum Indicators:
  - RSI (Relative Strength Index) - 14 period
  - Stochastic Oscillator (%K, %D)

- Volatility Measures:
  - Bollinger Bands (20 period, 2 std)
  - Average True Range (ATR) - 14 period

- Volume Analysis:
  - Volume Moving Average

#### 📈 Financial Metrics (PyNance-style)
- Daily returns calculation
- Cumulative returns tracking
- Rolling volatility (20-day)
- Price change analysis
- Gap analysis (Open vs Previous Close)
- Support and resistance levels

#### 🎯 Trading Signals
- RSI-based signals (Oversold/Bought)
- Moving Average crossover signals
- MACD signal line crossovers
- Combined multi-indicator signals

#### 📊 Visualizations
- Price with Moving Averages & Bollinger Bands
- RSI with overbought/oversold levels
- MACD with histogram
- Volume analysis with moving average
- Stochastic oscillator
- Cumulative returns tracking
- Correlation heatmaps of indicators
- Returns distribution analysis

## 🚀 Quick Start

### Prerequisites
`bash
pip install pandas numpy matplotlib seaborn jupyter TA-Lib

## Installation & Setup

### 1. Clone the repository
  
   git clone <repository-url>
   
   cd <project-directory>
   
### 2. Launch Jupyter Notebook
  
   jupyter notebook
   
### 3. Run Notebooks in Order:
   · Start with eda.ipynb for data understanding
   
   · Proceed to task2_analysis.ipynb for advanced analysis

## 📋 Execution Order

### Step 1: EDA Notebook (eda.ipynb)

1. Load and inspect your stock data
2. Perform data quality checks
3. Generate basic visualizations
4. Understand data distributions and patterns

### Step 2: Technical Analysis (task2_analysis.ipynb)

1. Calculate technical indicators
2. Generate trading signals
3. Create comprehensive visualizations
4. Generate analysis reports

## 📈 Data Requirements

### Your CSV files should contain:

· Date (datetime format)
· Open (opening price)
· High (daily high)
· Low (daily low)
· Close (closing price)
· Volume (trading volume)

### 🎯 Key Features

Analysis Capabilities

· Multi-timeframe analysis support
· Automated signal generation
· Risk assessment through volatility measures
· Performance tracking with cumulative returns
· Correlation analysis between indicators

Visualization Features

· Professional charts with institutional standards
· Interactive plots for exploration
· Multi-panel dashboards for comprehensive view
· Export capabilities for reports

## 📊 Outputs Generated

From EDA Notebook:

· Data quality report
· Basic statistical summaries
· Initial trend analysis
· Correlation matrices

## From Technical Analysis Notebook:

· Technical indicator values
· Trading signals with timestamps
· Comprehensive visualization dashboard
· Analysis report with recommendations
· Processed data CSV export

## 🔧 Customization

Modify Parameters:

· Adjust moving average periods
· Change RSI overbought/oversold thresholds
· Modify Bollinger Band standard deviations
· Customize signal generation logic

Add New Indicators:

The modular structure allows easy integration of additional TA-Lib indicators or custom metrics.
