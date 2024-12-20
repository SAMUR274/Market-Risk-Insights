# **Stock-Market-Analysis**

As a fourth-year computer science student, I developed this project to explore the practical application of **moving averages** in stock trading. The following code determines whether a user should **buy**, **sell**, or **hold** shares of a particular company based on technical analysis.

Using the provided SQL code, the system generates actionable signals by analyzing the closing prices of shares on individual days for various companies.

This project uses stock price data from companies like **Bajaj Auto**, **Eicher Motors**, **Hero Motocorp**, **Infosys**, **TCS**, and **TVS Motors**.

![Stock Market](https://api.time.com/wp-content/uploads/2020/03/stock-market-coronavirus-2.jpg)

---

## **Problem Statement**
India's two largest stock exchanges, **BSE** and **NSE**, process trades worth over 40,000 crores daily. These trades rely heavily on **technical and fundamental analysis** for decision-making.

One of the simplest and most widely used techniques in technical analysis is the **Moving Average Method**. This project applies moving averages to identify stock price trends and generate simple trading signals.

---

## **Moving Average Concept**
Moving averages are used to smoothen price trends, making it easier to identify upward or downward shifts.

### **Example Price Trend:**
- **Week 1:** 13, 14, 11, 17, 19  
- **Week 2:** 26, 23, 22, 22, 14  
- **Week 3:** 17, 19, 13, 16, 17  

In this project, I used **20-day** and **50-day moving averages** to analyze stock price trends and determine trading signals.

![Table](https://cdn.upgrad.com/UpGrad/temp/6cd1e9a9-e35c-4d45-9ae1-c11c90245e26/Assignment.png)

---

## **Trading Signals**
1. **Buy Signal (Golden Cross):**  
   A **Golden Cross** occurs when the shorter-term moving average (20-day) crosses above the longer-term moving average (50-day), indicating an upward trend. This is a signal to **buy** the stock as the price momentum is positive.

2. **Sell Signal (Death Cross):**  
   A **Death Cross** occurs when the shorter-term moving average crosses below the longer-term moving average, indicating a downward trend. This is a signal to **sell** the stock as the price momentum is negative.

3. **Hold Signal:**  
   If no crossover occurs between the two moving averages, the recommendation is to **hold**. If you own the stock, keep it. If not, avoid buying at the moment.

---

## **Why This Project?**
This project was an excellent opportunity to explore the intersection of data analysis and algorithmic trading. It helped me:
- Understand the **fundamentals of technical analysis**.
- Learn how to process and analyze financial data using **SQL**.
- Bridge the gap between academic knowledge and real-world applications in the stock market.

---

## **Features**
- **Clear Recommendations:** The system generates straightforward buy, sell, or hold signals based on stock price trends.
- **SQL-Based Processing:** Data analysis is handled efficiently through SQL queries.
- **Scalable Framework:** The methodology can be extended to analyze other datasets or markets.

---

## **How It Works**
1. **Input:** Historical stock price data, including daily closing prices, is loaded into a SQL database.
2. **Calculation:** The system calculates the **20-day** and **50-day moving averages** for each stock.
3. **Signal Generation:** Based on the moving average crossovers:
   - **Buy** if the 20-day average crosses above the 50-day average.
   - **Sell** if the 20-day average crosses below the 50-day average.
   - **Hold** if no crossover occurs.

---

## **Future Enhancements**
This project provides a foundation for further development:
- Adding **additional technical indicators** like RSI or Bollinger Bands for more comprehensive analysis.
- Creating an **interactive dashboard** for real-time stock analysis.
- Expanding the scope to include global stock exchanges like TSX or NYSE.

---

## **Getting Started**
1. Clone the repository:
   ```bash
   git clone https://github.com/SAMUR274/Market-Risk-Insights.git
