🚖 Ola Data Analytics Project

This project analyzes Ola Cab booking data using SQL for data cleaning & analysis and Power BI for interactive dashboard creation. The goal is to uncover insights into bookings, cancellations, revenue, and customer experience.

## 📊 Dashboard Preview  
![Ola Dashboard Demo](./Ola%20Project%20DEMO.gif)

📌 Project Overview

The ride-hailing industry generates millions of transactions daily. To optimize business decisions, it is important to track:

✅ Total bookings and ride volumes
🚦 Booking success vs. cancellation patterns
🚗 Vehicle type usage
💰 Revenue contribution
⭐ Customer ratings and satisfaction

This project demonstrates how raw data can be transformed into insights through SQL queries and Power BI visualizations.

🛠️ Tools & Technologies
SQL (Ola.sql) → Data preprocessing, cleaning, and analysis
Power BI (Ola.pbix) → Dashboard and visualization
CSV (Bookings.csv) → Raw dataset
GIF (Ola Project DEMO.gif) → Demo preview of dashboard

📊 Dashboard Features
1. Overall Analysis
Total bookings & ride volumes
Booking success vs. cancellations breakdown
Daily booking trends

2. Vehicle Type
Popular vehicle categories (Auto, Mini, Prime, etc.)
Vehicle share across bookings

3. Revenue
Total revenue
Revenue by vehicle type
Trends over time

4. Cancellations
Cancelled by driver
Cancelled by customer
Driver not found

5. Ratings
Average ratings
Rating distribution by vehicle type

📈 Key Insights
✅ 62% of rides were successful, while cancellations accounted for ~38%.
🚗 Prime Sedan & Prime SUV generated the highest revenue.
❌ Driver cancellations (18%) were higher than customer cancellations.
📉 “Driver not found” (~10%) indicates demand-supply gaps.
⭐ Premium rides received better ratings than budget rides.

📂 Project Structure
├── Bookings.csv           # Dataset
├── Ola.sql                # SQL queries for analysis
├── Ola.pbix               # Power BI dashboard file
├── Ola Project DEMO.gif   # Dashboard demo preview
└── README.md              # Project documentation

🚀 How to Run

Clone this repository:

git clone https://github.com/ManojRohokale/Ola-Data-Analytics-SQL-Project.git
cd Ola-Data-Analytics-SQL-Project


Import Bookings.csv into your SQL database.
Run queries from Ola.sql for analysis and preprocessing.
Open Ola.pbix in Power BI Desktop → Load dataset → Explore dashboard.

🔮 Future Improvements
Add real-time booking tracking
Implement predictive analytics (ML) for demand forecasting
Integrate geographical heatmaps

🙌 Acknowledgements
Ola dataset (sample/synthetic data) used for educational purposes
SQL & Power BI for data analytics and visualization
