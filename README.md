# Financial News Sentiment Analysis for Nova Financial Solutions

## 📊 Project Overview
This project conducts comprehensive analysis of correlations between financial news sentiment and stock market movements. The analysis enhances predictive analytics capabilities for financial forecasting accuracy and operational efficiency.

## 🎯 Business Objective
Nova Financial Solutions aims to leverage advanced data analysis to:
- Perform sentiment analysis on financial news headlines
- Establish statistical correlations between news sentiment and stock price movements
- Develop investment strategies using news sentiment as predictive tools

## 📁 Project Structure
nova-financial-analysis/
├── .github/workflows/ # CI/CD pipelines
├── data/ # Financial datasets
├── notebooks/ # Jupyter notebooks for analysis
│ ├── 01_task1_analysis.ipynb # EDA & Statistical Analysis
│ ├── 02_technical_analysis.ipynb # Technical Indicators
│ └── 03_correlation_analysis.ipynb # Sentiment Correlation
├── src/ # Source code modules
├── tests/ # Unit tests
├── scripts/ # Utility scripts
└── requirements.txt # Project dependencies

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8+
- Git

### Environment Setup
```bash
# Clone repository
git clone https://github.com/beza1619/nova-financial-analysis.git
cd nova-financial-analysis

# Create virtual environment
python -m venv venv

# Activate environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
