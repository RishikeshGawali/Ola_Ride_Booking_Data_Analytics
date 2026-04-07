Ola Ride Booking Data Analytics

Transforming raw ride-hailing data into actionable business intelligence using SQL, Python, and Power BI.


📌 Project Overview
This end-to-end data analytics project analyzes 100,000+ ride booking records from a ride-hailing platform similar to Ola Cabs. The goal was to uncover patterns in customer demand, driver performance, cancellation behavior, and revenue distribution — and present findings through an interactive Power BI dashboard.
The insights from this project can help operations and strategy teams make smarter decisions around driver allocation, surge pricing, and customer retention.

🎯 Business Objectives

Identify peak booking hours and high-demand zones
Analyze customer vs. driver cancellation patterns
Calculate key revenue and performance KPIs
Compare ride types by profitability
Build an interactive dashboard for stakeholder reporting


🛠️ Tech Stack
ToolPurposePython (Pandas, NumPy)Data cleaning & exploratory analysisMySQLKPI calculation & aggregationsPower BIInteractive dashboard & visualizationExcelRaw dataset

📊 Key Findings & Business Insights
MetricResultTotal Rides Analyzed100,000+ bookingsOverall Ride Success Rate82.4%Customer Cancellation Rate9.8%Driver Cancellation Rate7.8%Peak Booking Hours6 PM – 9 PM (accounts for 34% of daily rides)Top Revenue Ride TypePrime Sedan (contributes 41% of total revenue)Highest Demand CityBangalore (28% of total bookings)Average Ride Value₹312 per completed booking
🔍 Insights

Evening surge is critical — 6–9 PM drives over a third of daily bookings, suggesting dynamic driver incentives during this window could reduce cancellations significantly
Prime Sedan is the revenue engine — despite being a premium tier, it outperforms economy rides in total revenue contribution
Customer cancellations spike during surge hours — likely due to high wait times; reducing ETA by even 2 minutes in peak periods could improve retention
Top 3 cities drive 65% of bookings — hyper-local strategies for Bangalore, Mumbai, and Delhi could yield outsized ROI


🗂️ Repository Structure
Ola_Ride_Booking_Data_Analytics/
│
├── Bookings.xlsx               # Raw dataset
├── Ola_MySQL.sql               # SQL queries for KPI analysis
├── Ola_PowerBI.pbix            # Power BI dashboard file
├── Ola_PowerBI_ScreenShots.pdf # Dashboard preview (screenshots)
├── Ola_Documentation.pdf       # Full project documentation
├── DAX_Queries                 # DAX measures used in Power BI
└── README.md

⚙️ How to Run
bash# Clone the repository
git clone https://github.com/RishikeshGawali/Ola_Ride_Booking_Data_Analytics.git
cd Ola_Ride_Booking_Data_Analytics

Open Bookings.xlsx to explore the raw data
Run Ola_MySQL.sql in MySQL Workbench for KPI queries
Open Ola_PowerBI.pbix in Power BI Desktop for the interactive dashboard
View Ola_PowerBI_ScreenShots.pdf for a quick dashboard preview


📈 Power BI Dashboard Highlights

KPI cards: Total Rides, Revenue, Success Rate, Cancellation Rate
Hourly booking trend line chart
City-wise ride distribution map
Revenue breakdown by ride type
Customer vs. Driver cancellation comparison


👤 Author
Rishikesh Bharat Gawali
📧 rishigawali11@gmail.com
🔗 LinkedIn
💻 GitHub


⭐ If you found this project useful, consider giving it a star!
