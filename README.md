# OLA-RIDE-INSIGHTS
This project focuses on analyzing Ola ride booking data using Power BI for dashboard visualization. The goal is to uncover booking trends, identify customer and driver behavior patterns, evaluate cancellation reasons, and assess revenue performance across vehicle types and payment modes.

🧰 Tools & Technologies Used
Microsoft Power BI – For interactive dashboard creation and data visualization
DAX Measures – For KPIs like cancellation rate, success rate, booking value
Power Query (ETL in Power BI) – For data transformation and cleaning
Excel/MySQL – For preprocessing raw data

🔍 Process Followed
1. Data Collection
Ride booking dataset containing details of bookings, cancellations, payments, vehicle types, distances, and ratings.
2. Data Cleaning & Preparation
Removed null values and inconsistent booking records.
Standardized date formats and payment categories.
Defined KPIs: Total Bookings, Booking Value, Success Rate, Cancellation Rate, Distance Travelled.
3. Data Analysis (via DAX in Power BI)
Calculated metrics for booking success and cancellations.
Derived total revenue and customer-level insights.
Segmented bookings by vehicle type and payment method.
4. Dashboard Creation (Power BI)
Developed five interactive views:
Overall Summary – Total bookings, booking value, status breakdown, and ride volume trends.
Vehicle Type Analysis – Booking values, distances, and performance of each vehicle category.
Revenue Analysis – Revenue by payment method, revenue vs distance, top 5 customers.
Cancellation Analysis – Cancellation rate with detailed reasons (customer vs driver).
Ratings Analysis – Driver and customer ratings across vehicle types.
5. Insights Extraction
Interpreted visualizations to generate business insights.

🧠 Project Insights
1. Overall Booking Trends
Total Bookings: 103,024
Total Booking Value: 35M
Success Rate: ~62%
Cancellation Rate: 28.08%
Bookings peak between early July and weekends, showing higher ride demand.

2. Customer & Driver Behavior
Top cancellation reasons by customers: Driver delays, change of plans, wrong addresses.
Top cancellation reasons by drivers: Personal/car issues, excess passengers, customer issues.

3. Vehicle Performance
Highest revenue vehicle type: Prime Sedan (8.30M) followed by E-Bike (8.18M).
Average trip distance for cars ~25 km, while autos cover ~10 km per ride.
Prime Plus and SUVs perform consistently with ~5M successful booking value each.

4. Revenue Analysis
Payment Method Insights:
Cash dominates (19M+) followed by UPI (14M).
Very low adoption of debit/credit cards.
Top Customers: Some frequent riders contributed significantly to revenue (~6K each).
Revenue increases with higher distance, indicating premium rides are more profitable.

5. Ratings Analysis
Both drivers and customers maintain ratings around 4.0 across all vehicle categories.
E-Bikes and SUVs slightly outperform others in driver ratings.


📈 Dashboard Highlights
The interactive Power BI dashboard includes:
KPI Cards: Total bookings, booking value, cancellation rate, success rate.
Pie Charts: Booking status, customer & driver cancellation reasons.
Line & Bar Charts: Ride volume trends, revenue vs distance, revenue by payment method.
Tables: Vehicle-wise performance, top customers.
Ratings: Customer vs driver comparison across vehicle categories.


Bottleneck #1: High Driver Cancellations (18%)
Bottleneck #2: “Driver Not Found” (10%)
Bottleneck #3: Customer Cancellations (10%)
Recommendations - 
Driver-Focused Solutions:
Implement Acceptance Score Incentives.
Provide Upfront Fare & Destination Information.
Offer Location-Based “Hotspot” Bonuses.

Platform & Technology Solutions:
Optimize the Dispatch Algorithm for shorter pickup times.
Enhance Predictive Analytics for Driver Positioning.
Refine ETA Calculation Accuracy.

Customer-Focused Solutions:
Revise the Cancellation Fee Policy to be fairer and more effective. Introduce a “Wait & Save” feature during peak demand.


🧾 Final Conclusion
The Ola rides data analysis uncovered valuable insights for business decision-making:
✅ Optimize driver allocation and customer communication to reduce cancellations.
✅ Promote digital payments (UPI/cards) to lower cash dependency.
✅ Focus on Prime Sedan & E-Bike as top-performing vehicle types for revenue.
✅ Plan marketing offers during weekends and evenings to leverage peak booking hours.
✅ Improve driver training and app reliability to reduce driver-side cancellations.
