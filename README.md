# Alpha Pulse – Portfolio Risk Analytics

## Project Overview

Alpha Pulse is a financial data analytics project that analyzes portfolio performance and risk using Python and Tableau.
The project focuses on measuring portfolio returns, volatility, and drawdown to understand the risk-return characteristics of the portfolio.

The analysis helps investors evaluate how a portfolio performs over time and identify potential risk exposure.

---

## Objectives

The main objectives of this project are:

• Analyze portfolio performance using financial metrics
• Measure risk using volatility and drawdown analysis
• Visualize portfolio growth over time
• Build an interactive dashboard using Tableau
• Provide insights into portfolio risk and returns

---

## Technologies Used

• Python
• Pandas
• NumPy
• Jupyter Notebook
• Tableau
• GitHub

---

## Dataset

The dataset contains historical portfolio values used to calculate financial performance metrics such as returns and volatility.

Dataset file location:

data/portfolio_final.csv

---

## Financial Metrics Used

### Portfolio Growth

Portfolio growth shows how the value of the portfolio changes over time.
It helps investors understand the overall performance of their investment.

---

### Total Return (KPI)

Total return measures the percentage change in the portfolio value from the beginning to the end of the investment period.

Formula:

Total Return = (Final Portfolio Value − Initial Portfolio Value) / Initial Portfolio Value × 100

---

### Rolling Volatility

Rolling volatility measures the variation in portfolio returns over a moving time window.
It helps in understanding how stable or risky the portfolio is over time.

---

### Maximum Drawdown

Drawdown measures the largest decline from a portfolio peak to its lowest point before recovering.

Formula:

Drawdown = (Current Portfolio Value − Peak Value) / Peak Value

This metric helps investors understand potential losses during market downturns.

---

## Project Workflow

1. Data Collection
2. Data Preprocessing using Python
3. Financial Metric Calculation
4. Risk Analysis
5. Data Visualization
6. Dashboard Creation using Tableau

---

## Tableau Dashboard

The Tableau dashboard provides interactive visualizations of portfolio performance and risk metrics.

Dashboard includes:

• Portfolio Growth
• Total Return KPI
• Rolling Volatility
• Maximum Drawdown

---

## Dashboard Preview

![Dashboard](images/Overall Dashboard.png)

---

## Project Structure

Alpha-Pulse-Portfolio-Risk-Analytics

│
├── data
│   └── portfolio_final.csv

├── notebook
│   └── Alpha Pulse Portfolio-Risk-Analytics.ipynb

├── tableau
│   └── Alpha Pulse.twbx

├── images
│   ├── Overall Dashboard.png
│   ├── Portfolio Growth (1).png
│   ├── Rolling Volatility.png
│   ├── Drawdown.png
│   └── KPI Total Return.png

---

## Conclusion

This project demonstrates how financial analytics techniques can be used to evaluate portfolio performance and risk.
Using Python for analysis and Tableau for visualization provides clear insights into portfolio behavior and helps in better investment decision-making.
