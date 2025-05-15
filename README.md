# 🧠 Trade Smarter: Analyzing Trader Performance & Market Sentiment

> 📊 A data science project exploring how market **sentiment** influences **trading behavior** and **profitability**  
> 🧑‍💻 By a aspiring Junior Data Scientist passionate about turning raw data into meaningful insights

---

## 🚀 Project Goal

The aim of this project was to uncover patterns between **trader performance** and **market sentiment** (Fear vs Greed).  
I set out to answer:  
- _Do traders perform better on certain sentiment days?_  
- _Is market mood influencing trade size, frequency, or profitability?_  
- _Can we build smarter trading strategies based on sentiment?_

---

## 📁 Data Sources

- **Historical Trade Data**: Includes execution prices, trade size, fees, PnL, and timestamps.  
- **Market Sentiment Data**: Daily sentiment label classified as either **Fear** or **Greed**.

Both datasets were merged on date for unified analysis.

---

## 🔧 Tools & Libraries

| Tool       | Purpose                     |
|------------|-----------------------------|
| `pandas`   | Data manipulation & merging |
| `numpy`    | Numerical operations         |
| `matplotlib` & `seaborn` | Visualizations |
| `Jupyter Notebook` | Interactive coding & EDA |

---

## 📊 Key Steps

### 🧼 1. Data Cleaning & Preparation
- Converted timestamps to datetime
- Merged sentiment and trade datasets
- Removed duplicates and outliers
- Engineered new features:
  - `is_profitable` → Flag for profitable trades
  - `PnL_per_USD` → Profit efficiency metric

### 📈 2. Exploratory Data Analysis (EDA)
- Sentiment distribution (Greed vs Fear)
- Daily trade volumes
- Profitability trends across sentiments
- Visualizations to detect patterns in trader behavior

---

## 💡 Key Insights

| Insight 🚀 | Description |
|------------|-------------|
| **1. Greed = More Trades** | Trader activity increased significantly during Greed days. |
| **2. Higher PnL on Greed Days** | Profitability and efficiency were both better when the market was optimistic. |
| **3. Fear = Smaller Trades** | On Fear days, traders were more conservative in trade size. |
| **4. Sentiment Drives Risk Appetite** | Greed sentiment led to larger trades and higher risk-taking. |

These patterns suggest that **sentiment-aware strategies** could improve trading decisions.

---

## 📌 Project Highlights

✅ Data merged and cleaned with robust validation  
✅ Outliers handled for more accurate analysis  
✅ Clear, story-driven visualizations  
✅ Actionable conclusions for real-world trading strategy

---


