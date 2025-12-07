✈️ Airlines Analytics Dashboard Project

📊 A complete *end-to-end Data Analytics Project* built using *MySQL, Power BI, Tableau, and Excel* to analyze airline performance, passenger trends, and operational efficiency using real business KPIs.

This project focuses on *Load Factor Analysis, Carrier Performance, Route Demand, Travel Behavior Trends, and Distance-Based Flight Segmentation*.



 🚀 Project Objective

The main goal of this project is to analyze airline operational data and generate *business-ready insights* by:

- ✅ Measuring Passenger Load Factor
- ✅ Evaluating Airline Performance
- ✅ Identifying Busy Routes
- ✅ Understanding Travel Trends (Weekday vs Weekend)
- ✅ Segmenting Flights by Distance for Operational Planning



🛠️ Tools & Technologies Used

- 🗄️ MySQL – Data Querying, KPI Creation & Analysis  
- 📊 Power BI – Interactive Dashboard Development  
- 📈 Tableau – Advanced Visual Analytics  
- 📁 Excel – Raw Dataset & Data Cleaning  



 📂 Uploaded Project Files

- 📄 high cloud.sql → Contains *all KPI SQL queries*
- 📊 power bi airlines.pbix → *Power BI interactive report*
- 📈 high cloud airlines.twbx → *Tableau dashboard workbook*
- 📁 Airlines Dashboard.xlsx → *Raw airline dataset*



📌 Key Performance Indicators (KPIs) Created in SQL

 ✅ KPI 1: Total Load Factor %
Used to measure overall airline seat utilization.

Formula:
SUM(#Transported Passengers) / SUM(#Available Seats) * 100



✅ KPI 2: Load Factor by Time (Yearly, Quarterly & Monthly)

Created using:
- Date construction with MAKEDATE
- Time extraction using YEAR(), MONTH(), QUARTER()
- Aggregation with SUM()

Provides:
- 📆 Yearly Load Factor  
- 🗓️ Quarterly Load Factor  
- 📅 Monthly Load Factor  



 ✅ KPI 3: Load Factor by Carrier
Measures which airline is performing best based on passenger occupancy.

---

### ✅ KPI 4: Top 10 Airlines by Passenger Volume
Created using:
DENSE_RANK() window function to rank airlines based on total transported passengers.



 ✅ KPI 5: Most Busy Flight Routes
Identifies which *From–To City routes* have the highest number of flights.



✅ KPI 6: Weekday vs Weekend Load Factor
Separates travel demand based on:
- Weekday Travel
- Weekend Travel  
Helps in understanding customer travel behavior.



 ✅ KPI 7: Distance-Based Flight Grouping

Flights categorized into:
- Less than 500 Miles  
- 501–1500 Miles  
- 1501–5000 Miles  
- 5001–10000 Miles  
- Greater than 10000 Miles  

Used for *route planning, fuel optimization, and long-haul vs short-haul analysis*.



🔍 SQL Concepts Used

- ✅ Common Table Expressions (CTEs)
- ✅ Window Functions (DENSE_RANK)
- ✅ Date Functions (YEAR, MONTH, QUARTER, WEEKDAY, MAKEDATE)
- ✅ Aggregation (SUM, COUNT)
- ✅ Conditional Logic (CASE Statements)
- ✅ Sorting & Grouping (GROUP BY, ORDER BY)



 📊 Power BI Dashboard Features

- ✅ Load Factor Trend Analysis (Yearly, Quarterly, Monthly)
- ✅ Top 10 Airlines by Passenger Volume
- ✅ Route-wise Flight Distribution
- ✅ Weekday vs Weekend Travel Demand
- ✅ Distance-wise Flight Categorization
- ✅ KPI Cards for Quick Performance Insights



📈 Tableau Dashboard Features

- ✅ Interactive Airline Performance View
- ✅ Monthly & Quarterly Load Factor Trends
- ✅ Distance-Based Flight Distribution
- ✅ Busy Routes Visualization


 ✅ Business Insights Generated

- 🏆 Identified *Top Performing Airlines*
- 📈 Detected *Seasonal Travel Patterns*
- 🛣️ Found *High-Demand Flight Routes*
- 📅 Analyzed *Passenger Behavior on Weekdays vs Weekends*
- ✈️ Evaluated *Operational Efficiency using Load Factor %*
- ⛽ Improved understanding of *Distance-Based Operations*
- 📊 Helped in *Data-Driven Decision Making*

 🧠 Learning Outcomes

- ✅ Hands-on *Real-World SQL KPI Development*
- ✅ Strong Command over *Window Functions & CTEs*
- ✅ Professional *Dashboard Design using Power BI & Tableau*
- ✅ *Business-Oriented Data Storytelling*
- ✅ End-to-End *Data Analyst Project Experience*
