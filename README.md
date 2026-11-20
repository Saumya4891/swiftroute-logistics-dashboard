# 📊 SwiftRoute Logistics Performance Dashboard


 📖 Project Overview
The SwiftRoute Logistics Dashboard is a comprehensive Business Intelligence solution built using Microsoft Power BI. This project transforms raw logistics data into actionable insights, enabling stakeholders to monitor fleet performance, driver efficiency, hub operations, and overall supply chain health.

The dashboard is designed to answer critical business questions regarding On-Time Delivery (OTD), Customer Satisfaction (CSAT), Fleet Maintenance, and Hub Capacity Utilization.

## 🎯 Business Problem
A logistics company generates massive amounts of data daily regarding shipments, driver behavior, vehicle health, and hub throughput. Without a centralized view, it is difficult to:
1. Identify bottlenecks in delivery times.
2. Track underperforming drivers or hubs.
3. Monitor vehicle maintenance schedules to prevent breakdowns.
4. Correlate driver experience with customer ratings.

## 🚀 Key Features & Dashboards

### 1. Executive Summary (SwiftRoute Logistics)
High-Level KPIs: Tracks Total Orders (1225), On-Time Delivery Rate (77.6%), CSAT Score (82%), and Average Delivery Time (36.36 Hrs).
Comparative Analysis: Displays Month-over-Month (MoM) trends to compare current performance against the Previous Month (PM).
Fleet Snapshot: A consolidated view of Active Vehicles vs. Vehicles in Maintenance.

### 2. Drivers Overview
Performance Matrix: A scatter plot visualizing Experience Years vs. Performance Rating, helping HR identify top talent vs. those needing training.
Delay Analysis:A ranked bar chart of Delayed Delivery Rates by Driver Name, highlighting areas for operational improvement.
Individual Drill-Through: A dedicated profile section for specific drivers (e.g., Barbara Clark), showing hire date, tenure, and monthly delivery trends using a time-series area chart.

### 3. Hubs Overview
Capacity vs. Load: A comparison of Orders Processed vs. Hub Capacity to identify over-utilized or under-utilized hubs.
Heatmap Analysis: A color-coded matrix showing processing times (in hours) by Day of the Week for each hub, pinpointing specific days with operational slumps.
Ranking: A leaderboard of Hub Performance rankings based on efficiency percentages.

### 4. Vehicles Overview
Fleet Health: Breakdown of Active vs. Maintenance vehicles using Donut Charts.
Age Analysis: A scatter plot analyzing Vehicle Age vs. Breakdown Frequency, aiding in fleet replacement decisions.
Model Performance: Bar charts displaying order volume by Vehicle Model and Vehicle Code.

## 🛠️ Tech Stack & Skills Demonstrated

Tool: Microsoft Power BI Desktop
Data Modeling:Star Schema design connecting Fact tables (Orders/Deliveries) with Dimension tables (Drivers, Vehicles, Hubs, Calendar).
DAX (Data Analysis Expressions):
Created measures for MoM Growth, Rolling Averages, and Dynamic Titles.
     Calculated complex KPIs like `% On-Time Delivery`, `% CSAT`, and `Maintenance Rate`.
Power Query:Data cleaning, transformation, and handling missing values.
UI/UX Design:
     Custom navigation sidebar for seamless switching between report pages.
     Consistent color palette (Purple/Blue theme) for brand identity.
    Interactive slicers for Year and Month filtering.

## 💡 Key Insights Generated
Hub Efficiency: Identified that the Houston Hub has the highest order volume but struggles with capacity compared to the El Paso Hub, which has lower volume but higher performance ranking.
Driver Correlation: Analysis revealed that drivers with 5+ years of experience maintain a higher average performance rating, suggesting a need for mentorship programs for junior staff.
Fleet Risk: Highlighted specific vehicle models (e.g., Freightliner) showing higher breakdown frequencies, allowing the maintenance team to prioritize inspections.
<img width="1289" height="756" alt="image" src="https://github.com/user-attachments/assets/0a9a3efb-88e1-4a2b-8a15-6f1838d37c18" />
<img width="1284" height="746" alt="image" src="https://github.com/user-attachments/assets/2bb70fab-f170-46ec-a939-8e780b525a9e" />
<img width="1290" height="753" alt="image" src="https://github.com/user-attachments/assets/190b9b46-cdc9-4bed-96fa-6519774346cd" />
<img width="1291" height="751" alt="image" src="https://github.com/user-attachments/assets/2de40f00-5f35-4b77-a478-4822c151ecbc" />



