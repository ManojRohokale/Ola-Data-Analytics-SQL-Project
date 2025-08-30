# 🚖 Ola Data Analytics Project

This project analyzes Ola Cab booking data using SQL for data cleaning & analysis and Power BI for interactive dashboard creation. The goal is to uncover insights into bookings, cancellations, revenue, and customer experience.

## 📊 Dashboard Preview  
![Ola Dashboard Demo](./Ola%20Project%20DEMO.gif)

## 📌 Project Overview
The ride-hailing industry generates millions of transactions daily. This project tracks:
- ✅ Total bookings and ride volumes
- 🚦 Booking success vs. cancellation patterns  
- 🚗 Vehicle type usage
- 💰 Revenue contribution
- ⭐ Customer ratings and satisfaction

## 🛠️ Tools & Technologies
- **SQL** (`Ola.sql`) → Data preprocessing, cleaning, and analysis
- **Power BI** (`Ola.pbix`) → Dashboard and visualization
- **CSV** (`Bookings.csv`) → Raw dataset

## 📊 Dashboard Features
1. **Overall Analysis** - Total bookings, success vs. cancellations, daily trends
2. **Vehicle Type** - Popular categories (Auto, Mini, Prime, etc.) and usage share
3. **Revenue** - Total revenue, revenue by vehicle type, time trends
4. **Cancellations** - Driver vs. customer cancellations, driver availability issues
5. **Ratings** - Average ratings and distribution by vehicle type

## 📈 Key Insights
- ✅ **62%** ride success rate, **38%** cancellation rate
- 🚗 **Prime Sedan & Prime SUV** generated highest revenue
- ❌ **Driver cancellations (18%)** higher than customer cancellations
- 📉 **"Driver not found" (~10%)** indicates demand-supply gaps
- ⭐ **Premium rides** received better ratings than budget rides

## 📂 Project Structure
```
├── Bookings.csv           # Dataset
├── Ola.sql                # SQL queries for analysis
├── Ola.pbix               # Power BI dashboard file
├── Ola Project DEMO.gif   # Dashboard demo preview
└── README.md              # Project documentation
```

## 🚀 How to Run
1. Clone repository: `git clone https://github.com/ManojRohokale/Ola-Data-Analytics-SQL-Project.git`
2. Import `Bookings.csv` into your SQL database
3. Run queries from `Ola.sql` for analysis
4. Open `Ola.pbix` in Power BI Desktop and explore dashboard

## 🔮 Future Improvements
- Add real-time booking tracking
- Implement predictive analytics for demand forecasting
- Integrate geographical heatmaps

## 🙌 Acknowledgements
Dataset used for educational purposes. Built with SQL & Power BI.
