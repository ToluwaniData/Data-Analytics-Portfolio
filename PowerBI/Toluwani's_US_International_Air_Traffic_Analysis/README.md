# U.S. International Air Traffic Analysis  
*By Toluwani Emmanuel*  

## Objective  
This project analyzes international air traffic between U.S. and foreign airports using data from the Department of Transportation. The dashboard highlights flight activity, busiest airports, top carriers, seasonal patterns, and the dominance of scheduled flights in the industry.  

## Tools Used  
- **Power BI** (dashboard design and visualization)  
- **Power Query** (data cleaning and transformation)  
- **DAX** (custom measures and calculations)  

## Data Preparation  
- Appended two flight data tables in Power Query to create a unified table called **Combined Reports**.  
- Built three dimension tables: **Airlines**, **Foreign Airports**, and **U.S. Airports**.  
- Connected tables in a **star schema** for efficient analysis.  
- Created a **Calendar table** to support time-based analysis.  
- Added interactive slicers for **Year**, **Month**, **Carrier**, and **Flight Type**.  

## KPIs Displayed  
- Total Flights  
- Scheduled Flights  
- Charter Flights  
- Top U.S. Airport  
- Top Carrier  

## Key Insights  

1. **Top 10 Busiest U.S. Airports (Clustered Bar Chart)**  
   - JFK is the busiest with over 639M flights.  
   - LAS ranks lowest among the top 10 with 53,537 flights.  
   - Insight: Clear view of U.S. gateway airports handling the most international traffic.  

2. **Top 10 Busiest Foreign Airports (Clustered Bar Chart)**  
   - YYZ (Toronto Pearson) leads with 262M flights.  
   - SYD (Sydney) ranks lowest among the top 10 with 40M flights.  
   - Insight: Highlights the global reach of U.S. air traffic.  

3. **Top 10 Airline Carriers by Flights (Clustered Bar Chart)**  
   - American Airlines (AA) dominates with 593M flights.  
   - Lowest carrier in the top 10 has 36M flights.  
   - Insight: Strong indicator of airlines most active in international operations.  

4. **Monthly Flights Total (Clustered Bar Chart)**  
   - July consistently has the highest traffic (455M flights).  
   - February sees the least (326M flights).  
   - Insight: Clear seasonal patterns in international travel.  

5. **Monthly Total of Flights by Year (Line Chart)**  
   - Peak: July 2019 with 24M flights.  
   - Lowest: February 1991 with 4.7M flights.  
   - Insight: Helps understand long-term trends and disruptions.  

6. **Charter vs Scheduled Flights Share (Pie Chart)**  
   - Scheduled flights dominate (97.04%).  
   - Charter flights account for just 2.96%.  
   - Insight: Reinforces the scale and consistency of commercial air travel.  

## Outcome  
This dashboard provides a comprehensive view of international air traffic patterns. It helps stakeholders understand which airports and airlines are most active, how flight volumes shift over time, and the strong dominance of scheduled flights in the industry.  

## Screenshots  
![Dashboard Screenshot](US_International_Air_Traffic_Dashboard.png)  

## Live Walkthrough  
A live walkthrough of this project is available on my **LinkedIn profile**, where I explained the dashboard analysis and insights in real time.  

## Acknowledgement  
Dataset provided by the **Department of Transportation, Office of the Assistant Secretary for Aviation and International Affairs**.  
Last updated: **December 16, 2020**.  
Dataset owner: **Randall Keizer**.  
