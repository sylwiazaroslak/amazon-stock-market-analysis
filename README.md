# Amazon Stock Market Data Visualization Project

## Project Overview
In the financial and stock markets, the ability to transform raw data into clear, actionable visual insights is a vital skill for driving strategic, data-driven decisions. This project is an exploratory data analysis (EDA) and visualization exercise using **Microsoft Excel**, focused entirely on the historical performance of **Amazon.com, Inc. (AMZN)**. By analyzing daily financial metrics, this project explores past performance, uncovers market trends, and communicates data-driven insights effectively.

The primary objective is to evaluate market liquidity, price stability, and corporate catalyst-driven volatility over a 12-month period.

---

## 📊 Executive Summary & Key Insights
* **The Volume-Volatility Link:** Large expansions in the daily price range do not happen randomly; they are actively fueled by surges in institutional trading volume. The most dramatic example occurred in late July / early August 2021, where a historic price spread expansion exceeding **$155** perfectly aligned with the yearly trading volume peak of **10.0 million units**.
* **High Intraday Predictability:** A scatter plot analysis reveals a near-perfect linear relationship between the daily High and Low prices, yielding a Coefficient of Determination (**$R^2 = 0.9725$**). This indicates that **97.25%** of the daily price variance is highly structured, orderly, and systematic.
* **Balanced Market Symmetry:** On a day-to-day baseline, Amazon's trading sessions were almost perfectly split, resulting in a **51% decrease** and **49% increase** across the year. This tight split indicates a balanced, non-trending daily environment, even though the macro trend line across the full year maintained a net positive upward slope.

---

## Dataset Profile: Amazon (AMZN)
The dataset used spans from **December 2020 to November 2021** and represents cleaned daily historical tracking metrics optimized for processing within Excel.

It contains the following structural columns (all monetary values expressed in **USD ($)**):
- **`Date`**: The calendar date the financial activity was recorded.
- **`Open`**: The opening price from the first transaction of the trading day.
- **`High`**: The peak/maximum price achieved during the trading day.
- **`Low`**: The lowest/minimum price recorded during the trading day.
- **`Close`**: The final closing price from the last transaction of the trading day.
- **`Volume`**: The total number of shares traded throughout the day.

---

## Analytical Workflow & Dashboard Structure
The workbook is broken down into distinct visual phases to isolate specific financial trends:

### 1. Daily and Monthly Price Directional Trends
- Utilized basic formulas (`AVERAGE`, `MIN`, `MAX`) to calculate Amazon's baseline performance and net price swings.
- Built **Pie Charts** to map the 51/49% directional split and **Column Charts** to track the distribution of daily gains and losses.

### 2. Trading Volume Distribution & Liquidity
- Constructed a **Histogram Chart** showing that the vast majority of trading days cluster tightly between **2.0M and 3.5M units**, proving a highly stable retail trading baseline.
- Isolated institutional catalyst events (earnings reports) where volumes spiked up to **10.0M units** using chronological trendlines.

### 3. Intraday Price Correlation
- Modeled the daily floor vs. ceiling on an **Excel Scatter Plot** to check for chaotic price expansions.
- Derived the **Pearson correlation coefficient ($R = 0.986$)** and linear trendline formula to statistically prove intraday structural stability.

### 4. Volatility vs. Liquidity
- Created a **Dual-Axis Timeline** overlaying the Price Spread (`High - Low`) directly against trading volume to visually connect market participation with market movement.

---

## Technical Skills Applied
- **Advanced Excel Charting:** Dual-axis combination timelines, scatter plots with linear trendlines, and right-skewed frequency histograms.
- **Financial Statistical Modeling:** Regression concepts, calculating Coefficients of Determination ($R^2$), and tracking volatility metrics.
- **Exploratory Data Analysis (EDA):** Transforming raw financial telemetry into clear, boardroom-ready asset profiles.

---

## How to Use This Repository
1. **Open the Workbook**: Open `amazon_stock_market_analysis.xlsx` to view the interactive data sheets and charts.
2. **Review the Data Sheets**: Navigate through the sheets (`Daily_change`, `Volume_analysis`, `High_vs_low`) to inspect the formulas and statistical distributions.
3. **Analyze the Reports**: Review the `Final_report` sheet to see how data insights match the visual trends.
