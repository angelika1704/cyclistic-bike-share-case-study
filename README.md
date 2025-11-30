Divvy Bike-Share Case Study – Google Data Analytics Capstone Project

This repository contains my complete analytical workflow for the Divvy Bike-Share Case Study, the capstone project of the Google Data Analytics Professional Certificate.
The main objective is to compare the usage behavior of casual riders and annual members, and to provide data-driven recommendations for increasing membership conversions.

📌 Project Context

Divvy (Cyclistic) is a large bike-share program operating in Chicago. The marketing team wants to understand how casual riders differ from annual members to determine which tactics can effectively convert casual users into paying members.

This project follows the CRISP-DM methodology:

Business Understanding

Data Understanding

Data Preparation

Analysis

Visualization

Recommendations

⚠️ Important Note — Data Limitation

Due to file size restrictions and memory limitations when handling large datasets in Excel and Power BI, the full 12-month dataset could not be processed.

👉 For this reason, the analysis was completed using three months of Divvy data (Q1), which allowed for clean processing, accurate calculations, and stable visualization.

Despite this limitation, the findings are consistent, meaningful, and aligned with expected full-year patterns.

📂 Repository Structure
📁 Divvy-Bike-Share-Case-Study
│
├── 📄 CLEAN_DATA.png              # Clean dataset used for analysis
├── 📄 CLEAN_DATA_PBI.png           # CSV version for Power BI
├── 📊 INSIGHTS.png               # Full Power BI interactive dashboard
├── 📄 Divvy_Final_Report.pdf       # Professional final report
│
├── 📄 README.md                    # Project documentation (this file)

🧼 Data Cleaning & Preparation

All data cleaning was performed in Excel, and all visualizations were created in Power BI.

Key cleaning steps:

✔ Removal of rows with missing station information
✔ Formatting of all datetime fields
✔ Calculation of ride_length_minutes using DATEDIFF logic
✔ Identification and removal of outliers
✔ Creation of new analytical fields:

day_of_week

month_year

month_number

month_name

hour

✔ Standardization of text fields (capitalization, whitespace removal)
✔ Validation of data integrity prior to BI modeling

The final dataset used for analysis contained 700K+ clean records.

📊 Key Insights
1️⃣ Casual riders take longer rides

Members: 12–15 minutes average

Casual: 25–35 minutes average
→ Casual riders use bikes primarily for leisure, not transportation.

2️⃣ Different weekday usage patterns

Members → ride mostly Monday–Friday (commuting behavior)

Casual riders → peak on weekends

3️⃣ Hourly trends

Members peak during morning and afternoon commute hours

Casual riders peak between 11:00 and 18:00

4️⃣ Seasonality

(Within the first 3 months analyzed and aligned with typical yearly trends)

Usage increases from January → March

Warmer months historically show even stronger usage

5️⃣ Bike type usage

Both groups use docked bikes the most, with casual users showing more variation across tourist-heavy areas.

💡 Recommendations
✔ Convert casual → members with leisure-focused offers

Weekend passes

Trial membership periods

Summer discounts

Tourist-specific promotions

✔ Improve bike availability during commuting hours

More bikes in residential zones (7–9 AM)

More bikes in business areas (4–6 PM)

✔ Seasonal marketing strategy

Launch campaigns between March and August

Promote leisure routes and outdoor experiences

🛠️ Tools Used

Microsoft Excel → data cleaning, transformation, validation

Power BI → data modeling, DAX calculations, full dashboard creation

GitHub → documentation & portfolio publication
