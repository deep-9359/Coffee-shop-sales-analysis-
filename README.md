# ☕ Coffee Shop Sales Analysis

An end-to-end sales analysis project for a multi-location coffee shop chain, built using **Python** and **Microsoft Excel**. This project uncovers revenue trends, peak hours, top products, and customer footfall patterns to support data-driven business decisions.

---

## 📊 Dashboard Preview

![Coffee Shop Sales Dashboard](dashboard_screenshot.png)

---

## 🎯 Objective

To analyse sales data from a coffee shop operating across multiple store locations and extract actionable insights around:
- Peak ordering hours
- Best-performing product categories
- Store-level revenue and footfall comparison
- Weekday vs weekend order behaviour
- Order size distribution

---

## 📁 Dataset Overview

| Field | Details |
|---|---|
| Total Sales | $6,98,812.33 |
| Total Footfall | 1,49,116 customers |
| Avg Bill/Person | $4.69 |
| Avg Order/Person | 1.44 |
| Store Locations | Astoria, Hell's Kitchen, Lower Manhattan |
| Time Period | January – June |

---

## 🔍 Key Insights

- **Peak Hours:** Highest quantity ordered between **8 AM – 10 AM**, indicating a strong morning rush
- **Top Category:** **Coffee** dominates with **39%** of total sales, followed by **Tea (28%)**
- **Top Product:** **Barista Espresso** is the highest revenue-generating product at **$91,406**
- **Store Performance:** All three locations perform similarly in revenue (~$2.3L each), but **Astoria** leads slightly in footfall
- **Order Size:** **Large** and **Regular** sizes are almost equally preferred (30% each), with **Small** at only 9%
- **Weekday Trends:** Orders are relatively consistent across weekdays with slight dips on weekends

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python (Pandas) | Data cleaning and aggregation |
| Python (Matplotlib, Seaborn) | Exploratory visualizations |
| Microsoft Excel | Dashboard creation with PivotTables, slicers, and charts |

---

## 📌 Project Structure

```
coffee-shop-sales-analysis/
│
├── data/
│   └── coffee_shop_sales.csv        # Raw dataset
│
├── notebooks/
│   └── coffee_analysis.ipynb        # Python EDA notebook
│
├── dashboard/
│   └── coffee_sales_dashboard.xlsx  # Excel dashboard
│
├── screenshots/
│   └── dashboard_preview.png        # Dashboard screenshot
│
└── README.md
```

---

## 💡 Business Recommendations

1. **Staff more during 8–10 AM** — peak hour demand requires more hands on deck
2. **Promote Tea and Bakery** — these are underpenetrated categories with growth potential
3. **Introduce loyalty offers for weekends** — footfall dips can be countered with targeted promotions
4. **Focus Barista Espresso promotions** — already top seller, upselling with add-ons can boost avg bill

---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/deep-9359/Coffee-shop-sales-analysis-
```
2. Install dependencies
```bash
pip install pandas matplotlib seaborn
```
3. Open the Jupyter Notebook
```bash
jupyter notebook notebooks/coffee_analysis.ipynb
```
4. For the dashboard, open `coffee_sales_dashboard.xlsx` in Microsoft Excel

---

## 👤 Author

**Deepanshu Gautam**  
BBA Graduate | Data Analytics Enthusiast  
📧 rishabgautam9359@gmail.com  
🔗 [GitHub](https://github.com/deep-9359) | 📍 Meerut, Uttar Pradesh
