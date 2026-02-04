# Hyperliquid-Trader-Sentiment-Analysis


## Trader Performance vs Market Sentiment

<!-- R1: This project analyzes the relationship between trader performance and market sentiment (Fear/Greed) using Hyperliquid trading data as part of a Data Science Intern Round-0 assignment. -->

### Objective
To analyze how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid platform, and to derive actionable trading insights.

---

### Datasets
1. **Bitcoin Market Sentiment (Fear & Greed Index)**
   - Columns: Date, Classification (Fear / Greed)
   - link=  https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing


2. **Historical Trader Data (Hyperliquid)**
   - Includes: account, symbol, execution price, size, side, timestamp, leverage, closed PnL, etc.
   - link= https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

---

### Methodology
- Loaded and inspected both datasets for missing values and data types
- Converted timestamps and aligned data at a daily level
- Merged trader data with sentiment data based on date
- Created key metrics such as:
  - Daily PnL per trader
  - Trade frequency
  - Win rate proxy
  - Leverage distribution
  - Long/short ratio
- Compared trader behavior and performance across Fear vs Greed days
- Segmented traders based on behavioral characteristics

---

### Key Insights
- Trader performance differs significantly between Fear and Greed periods
- Higher leverage usage during Greed days leads to increased PnL volatility
- Conservative (low-leverage) traders tend to perform more consistently during Fear periods

---

### Strategy Recommendations
- **Rule 1:** During Fear days, reduce leverage exposure, especially for high-frequency traders
- **Rule 2:** During Greed days, favor consistent low-leverage traders over aggressive high-leverage strategies

---

### Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

### How to Run
1. Clone the repository
2. Install required Python libraries
3. Open and run the Jupyter notebook step by step

---

### Author
Afnan
