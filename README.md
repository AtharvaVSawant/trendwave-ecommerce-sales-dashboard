# TrendWave E-Commerce Sales Dashboard 📊

![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-yellow?logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-Measures-blue?logo=microsoft)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-purple?logo=microsoft)
![Data Source](https://img.shields.io/badge/Data-Yahoo%20Finance-720e9e?logo=yahoo)
![License](https://img.shields.io/badge/License-MIT-yellow)

An interactive Power BI dashboard analyzing sales, profit, and customer behavior for **TrendWave**, an e-commerce business. The dashboard provides a 360° view of revenue performance across regions, payment modes, product categories, and time periods.

![Dashboard Overview](https://github.com/AtharvaVSawant/trendwave-ecommerce-sales-dashboard/blob/35090a5848251b774d65434e703638c211ff5d94/Trendwave%20Ecommerce%20Sales%20Dashboard.png?raw=true)
## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Sales (Amount) | 438K |
| Total Profit | 37K |
| Total Quantity Sold | 5,615 units |
| Average Order Value | 121K |

## 📌 Dashboard Features

- **Quarter & Category Filters** — Slice the entire report by Qtr 1–4 and product category using the top navigation.
- **Sum of Profit by Month** — Waterfall-style monthly profit/loss trend, highlighting seasonal peaks (Jan–Apr, Nov) and dips (May, Jul, Sep, Dec).
- **Sum of Quantity by Payment Mode & State** — Regional breakdown showing Maharashtra (102K) and Madhya Pradesh (87K) as top-performing states.
- **Payment Mode Distribution (Donut)** — COD leads at 43.74%, followed by UPI (20.61%), Debit Card (13.2%), Credit Card (11.97%), and EMI (10.49%).
- **Top Performers by Quantity** — Individual contributor/agent-level performance (Harivansh, Madhav, Madan Mohan, Shiva, Vishakha).
- **Sum of Quantity by Category (Donut)** — Clothing dominates at 62.62%, followed by Electronics (20.55%) and Furniture (16.83%).
- **Sum of Profit by Sub-Category** — Printers and Bookcases are the most profitable sub-categories.

## 🛠️ Tools & Tech Stack

- **Power BI Desktop** — Data modeling, DAX measures, and dashboard design
- **Power Query** — Data cleaning and transformation
- **DAX** — Calculated measures (Sum of Amount, Profit, Quantity, Average Order Value)

## 📂 Repository Structure

```
trendwave-ecommerce-sales-dashboard/
├── data/                  # Raw/cleaned datasets used to build the dashboard
├── dashboard/             # Power BI (.pbix) file
├── images/                # Dashboard screenshots
└── README.md
```

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/AtharvaVSawant/trendwave-ecommerce-sales-dashboard.git
   ```
2. Open the `.pbix` file inside the `dashboard/` folder using **Power BI Desktop**.
3. If prompted, update the data source path to point to the files in the `data/` folder.
4. Explore the report using the Quarter and Category slicers.

## 📈 Insights & Takeaways

- Cash on Delivery (COD) remains the most preferred payment method, suggesting an opportunity to incentivize digital payments (UPI/cards) with discounts.
- Clothing drives the majority of sales volume, but Printers and Bookcases are more profitable per unit — indicating a potential margin-improvement strategy by promoting higher-margin sub-categories.
- Profit dipped in May, July, September, and December — worth investigating against marketing spend, returns, or discounting patterns in those months.
- Maharashtra and Madhya Pradesh together account for the majority of quantity sold, signaling strong regional demand that could guide inventory allocation.

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

## 🙋 Author

Built by Atharva Sawant — feel free to connect or raise an issue for suggestions!
