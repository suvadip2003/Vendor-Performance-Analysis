# Vendor & Product Performance Analysis Dashboard

### Project Overview
This project analyzes sales and vendor data to identify top performers, pinpoint areas of weakness, and uncover opportunities for improving profitability. The final result is an interactive dashboard built in Power BI.

---
### Dashboard Preview
Here is a look at the final dashboard:
[Live Interactive Dashboard Link]([YOUR_PUBLIC_LINK_HERE](https://app.powerbi.com/links/0T_UBLdVq5?ctid=b1703185-2d99-40e5-86e1-3a22312faf76&pbi_source=linkShare))

---
### Key Insights
* **Top Performers:** Identified Diageo North America as the most valuable vendor ($62M in sales) and Jack Daniel's as the top-selling brand ($8M).
* **Low Performers:** Pinpointed vendors and brands with low profit margins, highlighting opportunities to renegotiate contracts or streamline the product catalog.
* **Unsold Capital:** Calculated $2.71M in unsold inventory, revealing capital tied up in non-performing stock.

---
### Tools & Technologies
* **Data Ingestion & Processing:** Python (Pandas, SQLAlchemy)
* **Database:** SQLite
* **Data Analysis:** Jupyter Notebook, Python
* **Dashboarding:** Power BI

---
### Project Pipeline
1.  **Data Ingestion:** Raw CSV data is loaded into a SQLite database using `ingestion_db.py`.
2.  **Data Processing:** The data is cleaned, aggregated, and key metrics are calculated using `get_vendor_summary.py`.
3.  **Analysis & Visualization:** The final summary data is analyzed and visualized in Power BI.
