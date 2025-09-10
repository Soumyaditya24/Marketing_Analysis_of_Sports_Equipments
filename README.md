# Marketing_Analysis_of_Sports_Equipments

Marketing analysis of sports equipment with emphasis on conversions, customer engagement, and reviews. The project framework includes data preparation, visualization, and development of an interactive Power BI dashboard to evaluate product performance, derive insights, and support strategic marketing decisions.

🔗 **Interactive Dashboard Access:** Download the `PowerBi Dashboard.pbix` file and open it in **Power BI Desktop** to explore all interactive features.  

---

## 📂 Repository Contents  

| File Name                          | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `Dashboard PDF.pdf`                | Exported PDF version of the final dashboard.                                |
| `Dataset.csv`                      | Dataset containing customer, product, review, and engagement data.          |
| `PowerBi Dashboard.pbix`           | Power BI project file with all interactive visuals and KPIs.                |
| `Presentation PDF.pdf`             | Exported PDF version of the project presentation.                           |
| `Presentation PPT.pptx`            | PowerPoint presentation explaining the project workflow and insights.       |
| `Python for cleaning.py`           | Python script for data cleaning and preprocessing.                          |
| `README.md`                        | Documentation file (this one).                                              |
| `SQLQuery_CTE.sql`                 | SQL script using Common Table Expressions (CTEs) for advanced queries.      |
| `SQLQuery_categorize products.sql` | SQL script to categorize products into segments.                            |
| `SQLQuery_clean.sql`               | SQL script for cleaning duplicates and preparing raw data.                  |
| `SQLQuery_join.sql`                | SQL script for joining multiple tables into analysis-ready format.          |

---

## 🎯 Objectives  

- Analyze customer journey and conversion funnels.  
- Track social media engagement and performance trends.  
- Perform sentiment analysis on customer reviews.  
- Build an integrated dashboard with KPIs and filters.  
- Provide actionable recommendations for business growth.  

---

## 🧩 Key Features  

**KPIs:**  
- Conversion rates, engagement counts, sentiment distribution, top products.  

**Visuals:**  
- Funnel chart — Homepage → Product Page → Checkout → Purchase/Drop-off.  
- Line/Area charts — Monthly conversion & engagement trends.  
- Heatmap — Peak engagement hours/days.  
- Donut/Bar charts — Sentiment breakdown & rating distribution.  
- Comparison visuals — Platform-level engagement & product performance.  

**Slicers:**  
- Time period, Product category, Customer demographics (if available).  

---

## 🗂️ Data Overview  

- **Tables Used:**  
  - `customer_journey` (stages, actions, duration).  
  - `customer_reviews` (ratings, sentiments, review text).  
  - `engagement_data` (social media activity logs).  
  - `products` (product categories, IDs).  
  - `customers` (customer IDs, profiles).  

- **Data Model:**  
  - Star schema with **Products** as a central dimension.  
  - Fact tables: Customer Journey, Reviews, Engagement Data.  

---

## 🔧 How to Use  

1. Clone or download this repository.  
2. Run SQL scripts (`SQLQuery_clean.sql`, `SQLQuery_join.sql`, `SQLQuery_CTE.sql`, `SQLQuery_categorize products.sql`) in your SQL Server to prepare the database.  
3. Use `Python for cleaning.py` for preprocessing if needed.  
4. Open `PowerBi Dashboard.pbix` in **Power BI Desktop**.  
5. If prompted, update the dataset path to `Dataset.csv`.  
6. Refresh the dashboard and interact with filters/slicers. 
