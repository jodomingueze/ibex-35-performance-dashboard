# 📊 IBEX 35 Performance Dashboard (2022-2025)

**Bilingual Version 🇪🇸 / 🇬🇧**  
Advanced Power BI dashboard analyzing the performance, volatility, trend, and risk metrics of the **IBEX 35**, based on daily historical data from *Investing.com*.

---

## 📌 Summary (EN)

This project provides a **complete analytical view** of the IBEX 35 index using Power BI.  
Includes KPIs for returns, drawdown, volatility, moving averages, Sharpe Ratio, and a clean technical-analysis design.

**Key features:**
- Time-series evolution of the index  
- Cumulative and YTD returns  
- Rolling 30-day volatility  
- Max drawdown and current drawdown  
- Trend classification based on MA50 vs MA200  
- Interactive slicers and date filters  
- Clean professional layout for financial analytics  

---

## 📌 Resumen (ES)

Dashboard avanzado del **IBEX 35** construido en Power BI, con enfoque en análisis técnico y métricas de rendimiento.

**Incluye:**
- Evolución histórica del índice  
- Rentabilidad total y YTD  
- Volatilidad móvil de 30 días  
- Máximo drawdown y drawdown actual  
- Señal de tendencia (MA50 vs MA200)  
- Diseño profesional con KPIs destacados  

---

# 📁 Project Structure
```
/
├── pbix/
│ └── IBEX35_Performance_Dashboard.pbix
│
├── screenshots/
│ ├── dashboard_overview.png
│ ├── price_ma_chart.png
│ └── kpi_cards.png
│
├── docs/
│ └── methodology.md
│
└── README.md
```
---

# 🖼️ Dashboard Preview

## 📌 Main Dashboard
![Main Dashboard](screenshots/dashboard_overview.png)

## 📌 Price + Moving Averages
![MA chart](screenshots/price_ma_chart.png)

## 📌 KPI Cards
![KPIs](screenshots/kpi_cards.png)

---

# 🧠 Key Metrics (DAX)

### **Return Metrics**
- YTD Return  
- Total Return  
- Daily Return  
- CAGR  

### **Risk Metrics**
- Max Drawdown  
- Current Drawdown  
- 30-Day Rolling Volatility  
- Sharpe Ratio  

### **Trend Signal**
- MA50  
- MA200  
- Trend label (Bullish / Bearish / Neutral)  

Full list of DAX formulas available in:  
➡️ **`/docs/methodology.md`**

---

# 🔧 Data Source

- Website: **Investing.com**  
- Frequency: **Daily**  
- Fields: Date, Open, High, Low, Close, Volume  
- Period covered: **2022–2025**

---

# 🛠️ How to Use

1. Download the `.pbix` file:  
   👉 `pbix/IBEX35_Performance_Dashboard.pbix`

2. Open Power BI Desktop.

3. Interact with:
   - Date slicer  
   - Moving trend signal  
   - KPI cards  
   - Historical and cumulative return charts  

---

# 🧩 Technical Stack

- **Power BI Desktop**
- **DAX** (custom metrics)
- **Power Query** (cleaning & transformations)
- **GitHub** (version control)

---

# 📝 Author

👤 **José Gabriel Domínguez**  
Power BI & Data Analytics  
GitHub: https://github.com/jodomingueze

---

# 📄 License

This project is released under the MIT License.  
Feel free to use it for learning, portfolio, or job applications.
