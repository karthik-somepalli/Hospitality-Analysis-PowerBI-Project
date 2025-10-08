🌟 Hospitality Performance Analytics Dashboard

Revenue, Occupancy & Pricing Intelligence for the Hospitality Industry

<p align="center"> <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black"/> <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/DAX%20Measures-0078D4?style=for-the-badge&logoColor=white"/> <img src="https://img.shields.io/badge/Data%20Modeling-404040?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgo=" alt="Data Modeling"/> </p>
🎯 Project Goal

To transform raw hospitality booking data into a decision-making dashboard that enables stakeholders to:

Track Revenue, Occupancy & Profitability across cities and platforms

Evaluate pricing efficiency using ADR, RevPAR & Realized Price metrics

Respond instantly to Ad-hoc business questions through dynamic visualizations

🧩 Live Interactive Dashboard

🚀 👉 Click Here to View the Live Power BI Report

(https://app.powerbi.com/view?r=eyJrIjoiNGVhYjc2ZjgtMjA4Zi00YjllLWFiZTctOTRjY2M0ZTMxOGI5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

🧠 Executive Summary

This project delivers a data-driven command center for hospitality businesses, integrating Power BI, SQL, and DAX modeling to provide:

🔹 Performance tracking across multiple booking channels

🔹 Occupancy optimization via real-time data visibility

🔹 Actionable pricing insights to enhance profitability

⚙️ Technical Architecture
🧱 1. Data Preparation & Modeling

Source: Simulated database dumps imported via Power Query

Model: Implemented Star Schema with:

fact_bookings

dim_cities

dim_dates

dim_rooms

Data Validation: Ensured referential integrity, unique primary keys & consistent data types

Outcome: Optimized model → high performance + accurate aggregations

🧮 2. DAX Intelligence Layer

The brain of the dashboard — transforming raw data into KPIs
Key Measures Created:
| Metric | Formula | Purpose |
|:--------|:---------|:--------|
| ADR (Average Daily Rate) | Total Revenue / Total Rooms Sold | Tracks average earning per room |
| RevPAR (Revenue per Available Room) | ADR * Occupancy% | Combines rate & occupancy efficiency |
| Realized Price | Final Booked Price | Used for price optimization |
| Successful Booking Rate | Successful Bookings / Total Bookings | Measures conversion efficiency |

🧰 3. Reporting & Data Storytelling

Visual Design: Multi-page report with KPI cards, trend visuals, city-level comparisons

SQL Integration: AD_HOC_Requests.sql used to answer analytical queries

Executive Deck: Summarized key insights in RPC4.pptx & sample_challenge_presentation.pdf

🧾 Repository Structure
File / Folder	Description
Hospitality-analysis-Powerbi-project.pbix	Main Power BI file (data model + visuals + DAX)
AD_HOC_Requests.sql	SQL scripts used for ad-hoc business queries
RPC4.pptx	PowerPoint presentation with final findings
Metadata.txt	Schema documentation (tables, columns, keys)
PDF Support Files/	Data cleaning & transformation guides
📊 Key Insights Unlocked

✅ Top Cities by Revenue: Identified highest revenue & gross margin generators
✅ Occupancy Efficiency: Highlighted low-performing regions with capacity under-utilization
✅ Price Elasticity: Correlated pricing with booking success rates for dynamic pricing strategy
✅ Data Transparency: Enabled real-time performance comparison across platforms

🚀 Business Impact

💼 Decision-makers now gain:

📈 Instant view of hotel network performance

💰 Deeper profitability insights

⏱️ 80% reduction in manual data extraction & Excel reporting time

🧠 Tools & Technologies
Category	Tools Used
Data Analysis	Power BI, SQL
Data Modeling	Star Schema, Power Query
Visualization	Power BI Dashboards
Metrics	DAX Measures
Communication	PowerPoint, Documentation
🎓 Learning Outcomes

Through this project, I strengthened:

💡 End-to-End BI pipeline understanding

⚙️ Advanced DAX modeling skills

🧠 SQL querying for analytics

🧩 Business storytelling for executive audiences

💼 Author

👤 Karthik Somepalli
📧 karthiksomepalli25@gmail.com

🌐 GitHub: karthik-somepalli

“Turning data noise into business intelligence.”

🏁 Next Steps

Add automated refresh with Power BI Service

Integrate Python scripts for predictive analytics (future version)

Build PowerPoint export automation

💎 If you found this project insightful — don’t forget to ⭐ Star this repo

Because excellence should never stay hidden. 🚀
