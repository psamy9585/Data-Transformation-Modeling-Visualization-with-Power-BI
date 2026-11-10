🚲 Smart City Bike Sharing Analytics Dashboard
📌 Project Overview
This project analyzes smart city bike-sharing station data using Power BI to uncover operational insights, station performance metrics, and bike availability patterns across multiple cities.

The objective is to transform raw bike-sharing data into actionable business intelligence through data cleaning, modeling, DAX calculations, and interactive dashboard visualizations.

🎯 Business Problem
Public bike-sharing systems generate large amounts of real-time operational data from hundreds of stations distributed across multiple cities.

City administrators and transportation planners require analytical insights to:

Monitor bike availability across stations
Evaluate station utilization and capacity
Identify operational inefficiencies
Track station status (Open/Closed)
Support urban mobility planning
Improve bike distribution and resource allocation
This project leverages Power BI to convert raw operational data into meaningful insights for data-driven decision making.

🗂 Dataset Information
Dataset Name
Bike Sharing Station Data

Source
Public Bike Sharing Dataset

Domain
Transportation & Urban Mobility Analytics

Dataset Features
Station ID
Station Name
Address
Contract Name (City)
Latitude & Longitude
Banking Facility
Bonus Facility
Station Status
Bike Stands Capacity
Available Bike Stands
Available Bikes
Last Updated Timestamp
🛠 Tools & Technologies Used
Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Data Modeling
Star Schema Design
Microsoft Excel
🔄 Data Preparation
The following data transformation steps were performed:

Imported dataset into Power BI
Verified data types
Removed duplicates
Handled missing values
Split Position column into Latitude and Longitude
Extracted Date and Time from timestamp
Trimmed and cleaned text fields
Created dimension tables
Established relationships between tables
🏗 Data Modeling
A Star Schema model was implemented.

Fact Table
Fact_BikeStations

Dimension Tables
Dim_City
Dim_Station
Dim_Date
Relationships
City → Fact Table
Station → Fact Table
Date → Fact Table
📊 DAX Measures
Some key measures created include:

Total Stations
Total Bikes
Total Bike Capacity
Total Empty Stands
Open Stations
Closed Stations
Bike Utilization %
Bike Availability %
📈 Dashboard Features
KPI Cards
Total Stations
Total Bikes
Total Capacity
Open Stations
Closed Stations
Utilization %
Visualizations
Available Bikes by City
Station Capacity by City
Open vs Closed Stations
Geographic Station Map
Banking Facility Distribution
Bonus Station Distribution
Interactive Filters
City
Status
Banking
Bonus
Date
🔍 Key Insights
Most bike stations are operational and available for public use.
Bike availability varies significantly across cities.
Certain stations operate at higher utilization rates than others.
Geographic mapping helps identify station coverage and service distribution.
City-level comparisons reveal opportunities for resource optimization.
✅ Business Recommendations
Increase bike allocation in high-demand locations.
Monitor low-performing stations regularly.
Improve maintenance for frequently closed stations.
Expand infrastructure in highly utilized areas.
Implement predictive analytics for demand forecasting.

🎓 Skills Demonstrated
Data Cleaning
Data Transformation
Data Modeling
Star Schema Design
DAX Calculations
Dashboard Development
Data Visualization
Business Intelligence
Analytical Thinking
