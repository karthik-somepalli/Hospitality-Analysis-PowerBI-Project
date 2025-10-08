🌟 Hospitality Performance Analytics Dashboard
This project transforms raw data into actionable business intelligence for a major hospitality chain.

<p align="center">
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=white" alt="Power BI Badge"/>
<img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL Badge"/>
<img src="https://img.shields.io/badge/Data%20Modeling-404040?style=for-the-badge&logoColor=white" alt="Data Modeling Badge"/>
</p>

📈 Live Interactive Dashboard
🔗 VIEW LIVE DASHBOARD HERE



💡 Project Overview & Business Goal
This project details a comprehensive Revenue and Occupancy Analysis for a hospitality chain, transforming raw booking records into actionable insights for management. The primary goal was to equip stakeholders with a dynamic, self-service reporting tool to monitor performance and answer critical Ad-Hoc Business Questions quickly.

Key Business Questions Addressed:
Revenue Contribution: Which cities generate the highest revenue and Gross Margin (GM)?

Occupancy & Efficiency: How does the occupancy rate (Occ%) compare to the available capacity across different booking platforms?

Pricing Strategy: Analyzing the relationship between the successful booking rates and the utilized room price (Realized Price).

🛠️ Technical Workflow & Skills
The project involved meticulous data cleaning, advanced modeling, and precise measure calculation.

1. Data Preparation and Modeling (The Foundation)
Source: Raw data files (simulated database dump) were loaded using Power Query.

Modeling: Developed a clean Star Schema architecture to enforce clear relationships between fact tables (fact_bookings) and dimension tables (dim_cities, dim_dates, etc.). This structure ensures report performance and calculation accuracy.

Data Integrity: Handled data quality issues, such as ensuring unique primary keys and consistent data formats across all tables.

2. DAX Measure Creation (The Intelligence Layer)
Complex, calculated fields were created using the Data Analysis Expressions (DAX) language to generate true business metrics:

ADR (Average Daily Rate): Measures the average daily revenue received for rented rooms.

RevPAR (Revenue Per Available Room): Measures occupancy efficiency by multiplying ADR by the Occupancy Rate.

Realized Price: A critical measure tracking the final successful transaction price, used for price optimization analysis.

Successful Booking Rate: Calculated as a percentage to assess sales funnel efficiency.

3. Reporting and Communication
SQL Integration: The project documentation includes AD_HOC_Requests.sql, demonstrating the ability to write custom SQL queries to fulfill specific, low-level data extraction needs from the database.

Data Storytelling: The final report structure prioritizes actionable insights, moving from high-level KPIs (Total Revenue) down to granular segment performance. Supporting files, like RPC4.pptx, ensure the technical findings are translated into a compelling narrative for management.

📂 Repository Contents
File Name	Description
Hospitality-analysis-Powerbi-project.pbix	The final Power BI Desktop file containing the data model, Power Query steps, and all DAX measures.
AD_HOC_Requests.sql	SQL script used for ad-hoc data retrieval and validation during the analysis phase.
RPC4.pptx / sample_challenge_presentation.pdf	Presentation slides and template used to communicate the project scope and final results to stakeholders.
Metadata.txt	Documentation detailing the database schema, including table and column definitions.
PDF Support Files	Documentation providing guidelines on data cleaning and transformation techniques used.
Author: Karthik Somepalli
