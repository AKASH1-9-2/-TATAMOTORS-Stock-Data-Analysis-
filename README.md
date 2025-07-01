# 📈 TATAMOTORS Stock Data Analysis (2011–2021)

This project analyzes the historical stock performance of TATAMOTORS from 2011 to 2021 using Power BI. It provides insights into trading behavior, volume trends, closing prices, and key financial metrics through interactive visualizations.

---

## 📊 Project Description

This Power BI dashboard project aims to explore and visualize key aspects of TATAMOTORS stock data over a 10-year period. The analysis includes:

- Volume and price trends
- Trading activity
- VWAP (Volume Weighted Average Price)
- Deliverable vs Total Volume
- Monthly average volume and close price trends

---

## 📁 Dataset Source

The dataset includes the following columns:
- Date
- Open, High, Low, Close Prices
- Volume
- Deliverable Volume
- % Deliverable
- Trades

**Data Format:** Daily trading records from 2011 to 2021.

---

## 🔧 Preprocessing Steps

- Cleaned missing values
- Formatted `Date` column as Date/Time
- Created new columns:
  - `Year`, `Month`, `Quarter`, `MonthYear`
  - Calculated `VWAP = SUM(Close * Volume) / SUM(Volume)`

All preprocessing was done within Power BI using Power Query and DAX.

---

## 📌 Dashboard Features

### 1. KPI Cards
- Max Close Price
- Min Close Price
- Total Trades
- Avg. % Deliverable

### 2. Time Series Visuals
- Line chart for Closing Price Trend
- Area chart for VWAP over time

### 3. Volume Analysis
- Clustered column chart for Monthly Average Volume
- Stacked bar chart for Year-wise Deliverable vs Total Volume

### 4. Heatmap
- Matrix visual showing Average Close by Year and Month

### 5. Interactivity
- Slicers for Year, Month, and other filters
- Tooltip-based insights across visuals

---

## 📌 Key Metrics Observed

- Significant price volatility between 2013 and 2015
- Increase in trading volume in later years
- VWAP trends closely follow high-volume months
- Deliverable volume often outpaces total trade volume in mid-range years

---

## 📬 Contact

For any questions, reach out at LinkedIn : www.linkedin.com/in/akashbalamurugan .

