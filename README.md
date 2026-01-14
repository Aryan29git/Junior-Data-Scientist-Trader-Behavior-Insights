

 📊 Trader Performance vs Bitcoin Market Sentiment Analysis

 📌 Project Overview

This project analyzes the relationship between **Bitcoin market sentiment** (Fear & Greed Index) and **trader performance** using historical trading data from **Hyperliquid**.
The goal is to uncover **behavioral patterns**, **risk dynamics**, and **performance differences** across market sentiment regimes to derive insights that can support **smarter trading strategies**.

---

 🎯 Objectives

* Examine how **market sentiment** impacts trader profitability
* Identify **hidden behavioral patterns** under Fear vs Greed conditions
* Analyze **risk-taking behavior** (leverage, trade frequency)
* Provide **data-driven insights** for strategy optimization

---

 📂 Datasets Used

 1️⃣ Bitcoin Market Sentiment Dataset

* **Source:** Fear & Greed Index
* **Key Columns:**

  * `date` – Market date
  * `classification` – Market sentiment (`Fear` / `Greed`)

 2️⃣ Hyperliquid Historical Trader Data

* **Key Columns (subset):**

  * `account` – Trader identifier
  * `symbol` – Trading pair
  * `execution_price` – Trade execution price
  * `size` – Trade size
  * `side` – Buy / Sell
  * `time` – Trade timestamp
  * `event` – Trade event type
  * `closedPnL` – Profit & Loss
  * `leverage` – Applied leverage

---

🛠️ Tools & Technologies

* **Python**
* **Google Colab**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Visualization
* **SciPy** – Statistical testing

---

 📈 Methodology

1. **Data Cleaning & Preprocessing**

   * Timestamp normalization
   * Sentiment alignment with trade dates
   * Missing value handling

2. **Feature Engineering**

   * Profitability flags
   * Aggregated performance metrics
   * Sentiment-based trade grouping

3. **Exploratory Data Analysis**

   * PnL distribution by sentiment
   * Win-rate comparison
   * Leverage behavior analysis

4. **Statistical Analysis**

   * Mean & median comparisons
   * Significance testing between Fear & Greed regimes

---

 🔍 Key Insights

* Trader profitability varies significantly across **market sentiment regimes**
* **Risk-taking behavior** (leverage & position sizing) increases during Greed periods
* Fear-driven markets show **lower volatility but conservative positioning**
* Certain traders consistently outperform during specific sentiment conditions

---

 💡 Strategic Implications

* Sentiment-aware trading strategies can improve **risk-adjusted returns**
* Leverage controls should adapt dynamically to market sentiment
* Trader profiling can identify **sentiment-specialized strategies (Fear vs Greed traders)**

---

 📁 Repository Structure

```
├── market_sentiment_trader_performance.ipynb
├── README.md
```

---

 🚀 How to Run

1. Open the notebook in **Google Colab**
2. Upload the datasets when prompted
3. Run all cells sequentially

---

 🏁 Conclusion

This analysis demonstrates that **market sentiment is a critical contextual factor** in trader performance.
Incorporating sentiment signals into trading systems can lead to **more informed decisions**, **better risk management**, and **improved strategy design**.

---


