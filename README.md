#Bike Station Sharing System Analysis using Power BI

A complete Business Intelligence project that analyzes bike station operations using Power BI to generate actionable insights for improving bike availability, station capacity, and operational efficiency.



📌 Project Overview

This project analyzes a Bike Station Sharing System dataset using Power BI. The raw data was cleaned, transformed, and modeled into a Star Schema to build an interactive dashboard that provides insights into bike availability, station capacity, contract performance, and trends over time. The dashboard helps transportation operators make informed decisions regarding bike redistribution and resource planning.

🎯 Business Problem

Public bike-sharing systems require continuous monitoring to ensure bikes are available where users need them. This project addresses key business questions such as:

Which stations have the highest and lowest bike availability?
Which contracts (cities) operate the most stations?
How does bike availability change over time?
Which stations require immediate attention?
How can bike distribution be optimized?

✅ Objectives
Analyze bike station performance across contracts.
Monitor available bikes and station capacity.
Identify stations with low bike availability.
Track yearly and monthly availability trends.
Build an interactive Power BI dashboard for operational decision-making.

📂 Dataset
Attribute	Description
Source	Google Dataset Search / Open Data
Domain	Transportation / Smart City
Timeline	2022–2025
Dataset Type	Bike Station Status Data
Key Features	Station Name, Contract, Available Bikes, Bike Stands, Available Bike Stands, Status, Bonus, Latitude, Longitude, Date


🛠️ Tools & Technologies
Microsoft Power BI Desktop
Power Query
DAX
Data Modeling
Interactive Dashboard
Maps
KPI Cards
Charts
Slicers


🔄 Project Workflow
Data Collection
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Star Schema Data Modeling
      ↓
DAX Measures
      ↓
Exploratory Data Analysis
      ↓
Dashboard Development
      ↓
Business Insights & Recommendations
🧹 Data Cleaning


The following preprocessing steps were completed:

Removed duplicate records
Handled missing values
Corrected data types
Renamed columns
Created Date table
Added Year, Month, Quarter, and Week Number
Split data into Fact and Dimension tables
Filtered unnecessary records
Standardized text values
Built a Star Schema model


🗂️ Data Modeling
Star Schema

Fact Table

Fact_Station_Status

Dimension Tables

Dim_Station
Dim_Contract
Dim_Date
Relationships
Dim_Station → Fact_Station_Status
Dim_Contract → Fact_Station_Status
Dim_Date → Fact_Station_Status

Relationship Type:

One-to-Many (1:*)


📊 Exploratory Data Analysis (EDA)

The analysis answers important business questions, including:

Top 10 stations by available bikes
Stations with the lowest bike availability
Total bike stands and available bikes
Stations by contract
Bike availability percentage by contract
Bike availability trend by year
Average available bikes by month
Geographic distribution of bike stations
Stations requiring immediate attention

📈 Dashboard
KPI Cards
Total Stations
Total Available Bikes
Total Bike Stands
Total Available Bike Stands
Available Bikes %


Visualizations
📊 Bar Chart – Top 10 Stations by Available Bikes
🌍 Map – Bike Station Geographic Locations
📈 Line Chart – Bike Availability Trend by Year
📊 Column Chart – Average Available Bikes by Month
🥧 Donut Chart – Available Bikes % by Contract
📋 Matrix – Contract vs Bike Availability
📑 Table – Stations Requiring Immediate Attention
🎛️ Slicers – Year, Contract, Status, Bonus

💡 Key Insights
Marseille has the highest number of bike stations.
Stations such as Lacour / Artillerie and Livon Pasteur recorded the highest bike availability.
Several stations require immediate attention due to very low bike availability.
Bike availability differs significantly across contracts and years.
Closed stations contribute to lower bike availability.
High-demand contracts may require additional bike redistribution.

🚀 Business Recommendations
Rebalance bikes to low-availability stations.
Increase bike stands in high-demand locations.
Restore closed stations quickly.
Improve maintenance scheduling.
Optimize bike distribution using historical trends.
Continuously monitor contract performance.


🎯 Skills Demonstrated
Data Cleaning
Power Query
Data Modeling
Star Schema Design
DAX Measures
Dashboard Design
Data Visualization
Business Intelligence
Exploratory Data Analysis
Problem Solving

🔮 Future Improvements
Predict future bike demand
Automate dataset refresh
Integrate real-time station data
Publish dashboard to Power BI Service
Add advanced forecasting visuals

👨‍💻 Author

Kalaivani

📧 Email: Your Email

💼 LinkedIn: Your LinkedIn Profile

🌐 GitHub: Your GitHub Profile

⭐ If you found this project helpful, please give it a Star!
