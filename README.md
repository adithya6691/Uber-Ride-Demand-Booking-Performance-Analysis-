🚖 Uber Trip Analytics Dashboard

This project demonstrates the end-to-end process of cleaning, preparing, and analyzing an Uber ride-hailing dataset.
Using Python (Pandas) for data cleaning and Power BI for analytics and visualization, it uncovers key insights on trip patterns, revenue, customer behavior, and vehicle performance.

🎯 Project Objective

The goal of this project is to analyze a real-world Uber trip dataset to uncover operational and customer insights such as:

Revenue trends by month and vehicle type

Trip demand patterns by hour, weekday, and location

Customer behavior and high-value rider identification

Payment mode preferences

Forecasting future trips and demand

Pickup location hotspots and route behavior

🧰 Tools & Technologies

Programming Language: Python
Analytics & Visualization Tool: Power BI
Libraries: Pandas, NumPy, Matplotlib
Environment: Jupyter Notebook / VS Code
Dashboard File: uber_project.pbix
Dataset: (User-provided cleaned file)

🧼 Data Preparation (Python Cleaning Workflow)
Data Extraction

Raw trip data was loaded into Python using Pandas.

Data Transformation

Data cleaning included:

Removing unwanted characters (") from Booking IDs

Standardizing date columns and creating a unified trip_datetime

Converting fare, distance, and ratings to numeric

Handling missing values in payment method & ratings

Dropping duplicate records

Engineering new fields:

Trip Hour

Day Type (Weekend / Weekday)

Revenue Per KM

Trips Per Customer

Data Export

The cleaned dataset was saved as Uber_Final.csv and loaded into Power BI for modeling and visualization.

📊 Dashboard Overview (Power BI)

The dashboard consists of two interactive pages, providing insights into revenue, trips, customer behavior, and locations.

📍 PAGE 1 — Revenue & Business Insights
Key Metrics (KPIs)

Total Revenue: 52M

Average Fare: 345.64

Revenue per KM: 20.63

Insights Covered

Revenue by Vehicle Type
Auto and Go Mini contribute the highest revenue.

Monthly Revenue Trend
Seasonal peaks visible around April & November.

Top 10 Pickup Locations
High-demand hotspots such as Khandsa, Saket, Barakhamba Road, etc.

Revenue Per Customer
Identifies high-value customers and their trip frequency.

Revenue by Day Type
Weekday trips contribute significantly more than weekend trips.

Slicer: Vehicle Type

📍 PAGE 2 — Trip Trends & Customer Behavior
Key Metrics (KPIs)

Total Bookings: 150K

Average Distance: 16.75 km

Total Riders: 149K

Insights Covered

Ride Trends by Hour
Peak ride demand around 10 AM and 6 PM.

Yearly Ride Trend (with Forecast)
Shows stable trend with future demand prediction.

Weekday vs Weekend Trips
Weekdays show higher ride volumes due to work commute.

Payment Method Preference
UPI leads as the most preferred mode.

Slicers:
Date Range | Day Type | Payment Method | Vehicle Type | Trip Hour

🧮 Key DAX Measures

The project includes essential measures such as:

Total Trips

Total Riders

Total Revenue

Total Distance

Average Fare

Avg Distance

Revenue Per KM

Trips Per Customer

High Value Customer Logic

(clean, optimized, and minimal)

💡 Business Insights
Sales & Revenue

Auto generates the highest revenue among vehicle types.

Revenue spikes occur in specific months due to seasonal demand.

Customer Behavior

UPI is the dominant payment mode.

A small percentage of customers contribute heavily to total revenue.

Operational Insights

Evening and morning hours show peak demand.

Weekday bookings significantly exceed weekend rides.

Top pickup hotspots help in resource allocation.

Forecasting

Future demand appears stable, supporting operational planning.

⚙ How to Run the Project

Clone/download your project folder

Ensure the cleaned dataset Uber_Final.csv is available

Open the notebook Dataset_Cleaning.ipynb to review Python cleaning steps

Open uber_project.pbix in Power BI Desktop

Refresh data → all visuals update automatically

🔍 Future Enhancements

Add RLS (Row-Level Security) for customer-level access

Integrate real-time data using Power BI Gateway

Add forecasting models using Python (Prophet / ARIMA)

Geospatial heatmaps for pickup and drop locations

Build a cloud-based automated ETL pipeline

👤 Author

Adithya
Data Analyst | Python  | Power BI
🔗 www.linkedin.com/in/adithya-senguttuvan-36923863/
