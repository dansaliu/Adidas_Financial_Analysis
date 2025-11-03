# Adidas_Financial_Analysis
This project does a deep dive into the major drivers of sales and profit at adidas for the years 2021 and 2022.
Technical Report: Adidas U.S. Performance Analysis (2021-2022)
Author: Saliu Victor Date: November 1, 2025
A. Outline
This report follows a structured format to provide a comprehensive overview of the analysis. The key sections include:
•	Introduction
•	Story of Data
•	Data Splitting and Preprocessing
•	Pre-Analysis
•	In-Analysis
•	Post-Analysis and Insights
•	Data Visualizations & Charts
•	Recommendations and Observations
•	Conclusion
•	References & Appendices




B. Introduction
This section introduces the project, establishing its context and goals.
•	Objective of the Project: The primary aim was to analyze Adidas's sales and profit performance in the United States from 2021 to 2022. The analysis aimed to identify key trends, top-performing segments, and drivers of profitability.
•	Problem Being Addressed: The analysis aims to answer critical business questions: Which regions and states are most valuable? Which sales channels (In-store, Online, Outlet) are most profitable? Which retail partners drive the most profit? And which product types are the biggest sellers?
•	Key Datasets and Methodologies: The analysis was conducted on an internal Adidas sales dataset spanning 2021-2022. The primary methodology involved data aggregation, segmentation, and visualization using Microsoft Excel, specifically Pivot Tables and interactive Dashboarding.

C. Story of Data
This section details the data used for the analysis.
•	Data Source: The data was sourced from an internal company sales database, representing transactional records.
•	Data Collection Process: Data was assumed to be collected automatically through point-of-sale (POS) systems, e-commerce platforms, and partner sales reports.
•	Data Structure: The data is transactional, with each row representing a sale. Key columns (variables) used for this analysis include: Invoice Date, Total Sales, Total Profit, Marging, Units Sold, Retailer, Sales Method, Region, State, and Product Type.
•	Data Limitations or Biases: The analysis was limited to the U.S. market and the 2021-2022 timeframe. It did not include data on marketing expenses, operational costs, or customer demographics, which could affect deeper causal analysis.

D. Data Splitting and Preprocessing
This section explains how the data was prepared for analysis.
•	Industry Context: The data belongs to the Retail (Sportswear & Apparel) industry.
•	Stakeholders: Key stakeholders for this report include the U.S. Head of Sales, Regional Managers, Marketing Department, and Partnership/Account Managers.
•	Value to the Industry: The insights helped decision-makers optimize inventory, tailor regional marketing, and manage partner relationships to drive profitability.
•	Data Cleaning: Steps were taken to ensure data quality, including checking for and removing duplicate entries and handling missing values (e.g., ensuring all sales had a "Sales Method" assigned).
•	Data Transformations: A new "Month" column was extracted from the "Date" field to enable monthly trend analysis.
•	Data Splitting: For the analysis, Total Sales, Total Profit, and Units Sold were treated as dependent variables (metrics). The categorical data—Region, State, Retailer, Sales Method, and Product Type—were used as independent variables for segmentation.

E. Pre-Analysis
This section covers preliminary observations before the deep-dive analysis.
•	Identify Key Trends: An initial hypothesis was that sales would peak during the summer and end-of-year holiday seasons.
•	Potential Correlations: A strong positive correlation was expected between Total Sales and Total Profit, as well as between Units Sold and Total Sales.
•	Initial Insights: A quick review suggested that footwear would be a dominant category and that sales would be concentrated in populous states like New York and California.

F. In-Analysis
This section details the core analytical process.
•	Unconfirmed Insights (Hypotheses):
o	We hypothesized that the "In-store" sales method would be the most profitable channel, potentially due to lower overheads for returns and shipping compared to "Online".
o	We hypothesized that key accounts like Foot Locker would be among the top profit drivers.
•	Recommendations (Preliminary): Based on the hypothesis that certain partners are more profitable, we suggested a preliminary action to review the account management strategy for top-tier vs. lower-tier retailers.
•	Analysis Techniques Used in Excel: The core of the analysis was performed using Pivot Tables to aggregate the $899.9M in sales and $332.1M in profit across all dimensions. Slicers were used to filter the data by Year and Sales Method to create an interactive dashboard experience.

G. Post-Analysis and Insights
This section summarizes the final conclusions drawn from the analysis.
•	Key Findings:
o	Overall Performance: The company generated $899.9M in Total Sales and $332.1M in Total Profit over the 2-year period.
o	Geographic Sales: The West ($269.9M) and Northeast ($186.3M) were the top two sales regions. New York ($64.2M) is the #1 performing state.
o	Geographic Profit: Profitability mirrored sales, with the West (27%) and Northeast (21%) being the most profitable regions.
o	Product Performance: Men's Street Footwear ($208.8M) was the single most dominant product category, generating significantly more sales than any other.
o	Partner Profitability: West Gear ($85.7M) and Foot Locker ($80.7M) were the two most profitable retail partners, far exceeding others.
o	Channel Profitability: In-store ($127.6M) wa the most profitable sales method, followed by Outlet ($108.0M).
•	Comparison with Initial Findings:
o	The hypothesis that "In-store" was most profitable was validated.
o	A surprising result was that the "Outlet" channel generated more profit ($108.0M) than the "Online" channel ($96.6M). This challenges the common assumption that e-commerce is always a high-margin channel.

H. Data Visualizations & Charts
Visuals were used to communicate complex insights effectively.
•	Charts and Graphs: The analysis is presented via a two-page dynamic dashboard. Visuals include:
o	KPI Cards: For top-line metrics (Total Sales, Total Profit, Units Sold).
o	Line Charts: To show Monthly Sales and Profit Trends.
o	Bar Charts: For "Sales by States (Top 5)" and "Profit by Retailer."
o	Donut Charts: For "Sales by Region," "Profit by Region," "Profit by Sales Method," and "Sales by Product Type."
•	Explanation of Visualizations: The "Profit by Retailer" bar chart, for example, clearly visualizes the outsized importance of West Gear and Foot Locker; their profit bars are more than double the next closest partner, Sports Direct. The "Monthly Sales Trend" line chart effectively displays the two key sales peaks in July and December.
  <img width="1136" height="516" alt="Adidas Sales Dashboard" src="https://github.com/user-attachments/assets/092c64b1-ee91-4d55-b4bf-51420a7b7e8a" />


<img width="1136" height="516" alt="ADIDAS Profit Dashboard" src="https://github.com/user-attachments/assets/2ca40e2b-6fc2-4c8d-a28e-2eca8232e094" />


I. Recommendations and Observations
This section converts the analytical findings into actionable business recommendations.
•	Actionable Insights:
1.	Partner Strategy: Strengthen strategic partnerships with West Gear and Foot Locker. Consider joint marketing campaigns and ensure premium inventory allocation, as they are the primary profit drivers.
2.	Channel Optimization: Investigate the Online channel's profitability. The fact it trails Outlets in profit (despite high sales potential) suggests high costs (e.g., shipping, returns, digital marketing). This area needs optimization.
3.	Product Focus: Double-down on Men's Street Footwear. This category is the clear sales leader and should be a priority for marketing, and product development.
4.	Regional Focus: Allocate additional marketing and sales resources to the high-performing West and Northeast regions.
5.	Retailer Partnerships: Deepen collaboration with West Gear and Foot Locker; re-evaluate Amazon and Walmart to optimize profit margins.
6.	Seasonal Operations: Align marketing and product launches to capitalize on summer spikes; employ clearance campaigns during March and October troughs.
•	Unexpected Outcomes: The most significant unexpected outcome is the low profitability of the Online channel relative to Outlets. This warrants a dedicated follow-up analysis.

J. Conclusion
This section wraps up the report, summarizing key findings and future implications.
•	Key Learnings: The analysis successfully identified the key pillars of Adidas's U.S. performance: high-value partners (West Gear, Foot Locker), critical regions (West, Northeast), a dominant category (Men's Street Footwear), and the most profitable channel (In-store).
•	Limitations: The analysis is limited by the dataset. Without cost-of-goods, marketing spend, or return-rate data, we cannot fully diagnose why the Online channel is underperforming in profitability.
•	Future Research: Two key areas for future research are:
1.	A deep-dive profitability analysis of the Online channel.
2.	An analysis correlating regional marketing spend to sales performance to build a predictive model for resource allocation.

K. References & Appendices
This section provides supporting materials.
•	References: Adidas U.S. Sales & Profit Dataset, 2021-2022 (Internal Company Database).

