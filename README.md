# Greater Manchester Property Price Monitor
<div align="center">
  <img height="200" src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXk1dnhnMDhxcHprbHlrZm9wNWsyaXlpZGRkcDk2OW4zajl4aWthNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JHw6UnFuoe15yj6UdI/giphy.gif"  />
</div>

## 📄 Overview
This project analyzes property price trends in Greater Manchester using Power BI and Microsoft SQL Server. It focuses on extracting, cleaning, and visualizing transaction-level data from the UK Price Paid Dataset (2019–2022), creating an interactive dashboard to help stakeholders explore market insights.

## 🛠️ Tools & Technologies
- Microsoft SQL Server Management Studio (SSMS)
- Microsoft Power BI
- UK Government Price Paid Data (CSV format)

## 📊 Project Components
1. **Data Import & Cleaning**
   - CSV files from 2019 to 2022 downloaded from [gov.uk](https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads)
   - Null values removed before import
   - Database: `GreaterManchesterPricePaid`
   
2. **SQL View Creation**
   - Views were created to consolidate and clean data
   - Redundant columns removed for efficient analysis

3. **Dashboard Design**
   - Line Charts: Sales trend over time
   - Histogram: Price distribution
   - Map: Geospatial property sales analysis
   - Column Chart: Sales volume by price range

## 🎯 Objective
To provide real estate stakeholders a data-driven understanding of property trends across the Greater Manchester region using an interactive dashboard.

## ✅ Key Takeaways
- SQL + Power BI is a powerful combo for ETL + dashboarding
- The dashboard helps identify price trends, sales patterns, and geographic hot zones
- Limitations include Power BI’s performance on large datasets and reliance on internet connectivity

## 📁 File Structure
- `Report - Task 1.pdf`: Full technical report
- `dashboard.pbix`: Power BI dashboard file (not included here)
- `README.md`: Project overview
