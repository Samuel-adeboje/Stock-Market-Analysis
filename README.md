# 📈 Stock Market Analysis: Understanding Risk & Returns

## **1. Problem Statement**
Stock market prices fluctuate due to economic, social, and political factors. Investors require **data-driven insights** to make informed decisions about their investments. This project analyzes historical stock prices to identify trends, correlations, and risk factors using Python.

---

## **2. Objectives**
✅ **Analyze historical stock price data** for selected companies.

✅ **Compare multiple stocks** to identify performance trends.

✅ **Calculate and visualize stock correlations** to understand relationships between assets.

✅ **Assess market volatility and risk vs. return trade-offs** to help investors make better decisions.

---

## **3. Dataset & Methodology**
### **3.1 Data Source**
The dataset was obtained from Yahoo Finance using the `yfinance` Python library. It includes:
- **Stock tickers:** Tesla (TSLA), Apple (AAPL), Amazon (AMZN)
- **Timeframe:** January 2024 – January 2025
- **Features:** Date, Opening Price, Closing Price, Daily Returns, Moving Averages, etc.

### **3.2 Methodology**
1️⃣ **Data Collection:** Retrieve historical stock prices using Python’s `yfinance` library.

2️⃣ **Data Preprocessing:** Clean the dataset, handle missing values, and normalize prices.

3️⃣ **Exploratory Data Analysis (EDA):** Visualize trends, calculate correlations, and analyze volatility.

4️⃣ **Performance Comparison:** Compare stock performance over time.

5️⃣ **Risk Analysis:** Compute daily returns and stock correlations.

6️⃣ **Risk vs. Return Analysis:** Evaluate the risk-return profile of each stock.

---

## **4. Key Insights & Findings**
📊 **Stock Trends:**
- Tesla (TSLA) exhibited high volatility, while Apple (AAPL) showed more stable growth.
 
![4](https://github.com/user-attachments/assets/7e7f1c17-5283-433e-bfc2-fb80740aca1c)


📉 **Risk vs. Return:**
- Tesla had the highest potential returns but also the highest volatility.

![6](https://github.com/user-attachments/assets/b2597317-48af-48a0-a7cd-3c956c278682)


🔄 **Correlation Analysis:**
- Weak positive correlations between AAPL, AMZN, and TSLA, indicating portfolio diversification benefits.
- AAPL & AMZN = 0.34 → Weak positive correlation
- AAPL & TSLA = 0.33 → Weak positive correlation
- AMZN & TSLA = 0.32 → Weak positive correlation

 
![5](https://github.com/user-attachments/assets/ca5cfef4-7bde-461e-8bd1-30b5bcabfda7)


📈 **Sharpe Ratio Calculation:**
- Apple and Amazon provided **better risk-adjusted returns** compared to Tesla.

---

## **5. Investor Strategy Recommendations**
🔹 **Low-risk investors:** Apple (AAPL) for stability.

🔹 **Moderate-risk investors:** Amazon (AMZN) for balanced growth.

🔹 **High-risk investors:** Tesla (TSLA) for aggressive returns.

🔹 **Diversification is key:** A mix of all three stocks spreads risk while capturing growth.

---

## **6. Technologies Used**
🛠 **Python** (Pandas, NumPy, Matplotlib, Seaborn)

📊 **yFinance** (For stock data retrieval)

📈 **Data Visualization** (Line charts, Correlation Matrix, Risk-Return Scatter Plot)

---

## **7. How to Run the Analysis**
1️⃣ Clone this repository:
```bash
git clone https://github.com/Samuel-adeboje/stock-market-analysis.git
```

2️⃣ Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn yfinance
```

3️⃣ Run the Jupyter Notebook:
```bash
jupyter notebook
```

4️⃣ Open and execute the `STOCK MARKET ANALYSIS.ipynb` file.

---

## **8. Conclusion & Next Steps**
🔹 **If you prefer safety → Invest more in AAPL and AMZN (low to moderate risk).**

🔹 **If you seek high returns → Allocate a portion to TSLA, but balance it with safer stocks.**

🔹 **Diversification is key → Holding a mix of all three stocks can spread risk while capturing growth.**

🚀 **Future Enhancements:**
- Implement **Monte Carlo simulations** for portfolio optimization.
- Enhance risk analysis with **VaR (Value at Risk) calculations**.
- Explore **machine learning models** for stock price predictions.

📌 **Contributions & Feedback are Welcome!** If you find this project useful or have ideas for improvement, feel free to open an issue or submit a pull request.

🔗 **Check out the full project on GitHub: https://github.com/Samuel-adeboje/Stock-Market-Analysis/blob/main/Stock%20Market%20Analysis%20Report.pdf

🔗 Connect with me on LinkedIn: https://www.linkedin.com/in/samuel-adeboje-368320330/
