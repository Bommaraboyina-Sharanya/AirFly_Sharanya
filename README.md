 ✈️ Airline Performance and Delay Analysis — Project Documentation

🔹Milestone 1: Data Foundation, Cleaning, and Initial EDA

Data Preprocessing & Setup

* Cleaned and standardized the raw flight dataset for consistency.
* Resolved missing values in delay and cancellation fields.
* Treated outliers to enhance analytical accuracy.
* Formatted datetime fields and derived key features such as Month, Day, Hour, and Route.
* Exported a refined dataset suitable for advanced analysis and dashboarding.

Exploratory Data Analysis

* Conducted univariate analysis to understand variable distributions.
* Performed bivariate analysis to explore relationships among carriers, routes, delays, and time factors.
* Generated visual insights that highlighted early performance patterns and outliers.


🔹Milestone 2: Visual Exploration and Delay Trends

Univariate & Bivariate Visual Analysis

* Created bar charts, histograms, boxplots, and line plots for variable-level exploration.
* Identified top-performing airlines, busiest routes, and high-traffic schedules.
* Analyzed flight distribution across months, days, hours, and airports.

Delay Analysis (Airline, Weather, NAS)

* Compared delay causes across different airlines.
* Assessed contributions of carrier, weather, and NAS delay factors.
* Identified delay behaviour across airports, time of day, and routes.
* Mapped peak delay hours and most delay-prone carriers.


🔹Milestone 3: Route, Cancellation, and Seasonal Insights

1) Route & Airport-Level Analysis

* Analyzed the **Top 10 Origin–Destination (OD) route pairs** to identify the busiest flight corridors.
* Developed **delay heatmaps** capturing route-level and airport-level congestion.
* Designed **geographical map visualizations** displaying busy airports and average delay metrics.
* Identified key airports contributing significantly to delay propagation.

2) Seasonal & Cancellation Analysis

* Examined **monthly cancellation patterns** to detect seasonal peaks.
* Categorized cancellation reasons: Carrier, Weather, Security, and NAS.
* Evaluated the influence of holiday seasons and winter weather events.
* Compared cancellation behaviour across airlines and major airport hubs.


🔹 Milestone 4: Dashboard Development & Reporting

Dashboard Preparation and Explanation :

The Airline Performance and Delay Analysis Dashboard provides a comprehensive operational overview of flight performance, delay patterns, cancellations, and route-level insights. Each visual serves a specific analytical role.


1. KPI Summary Cards

-> Total Flights (2M)

Shows the overall number of flights in the dataset, offering a high-level operational scale.

-> Average Delay (10 minutes)

Represents the mean delay across all flights and acts as a key performance indicator for operational efficiency.

-> Cancelled Flights (1.75M)

Displays total cancellations, highlighting reliability issues and overall system disruptions.


2. Slicer Panel : Filters for Airline, Month, Delay Reason, Day of Week.
   
Enables interactive drill-downs by airline, seasonality, and delay factors.

3. Flight Status Distribution (Pie Chart)

-> Shows the proportion of flights by status:
   Cancelled, Diverted, Early, Small Delay, Medium Delay, etc.
   Helps understand the overall operational outcome distribution.

4. Average Delay by Airline (Bar Chart)

-> Compares airlines based on average delay minutes.
-> Useful for benchmarking carriers and identifying best/worst performers.

5. Delay Status by Delay Reason (Doughnut Chart)

-> Breaks down delay instances across categories like Weather, Maintenance, Carrier, and NAS.
-> Provides clarity on major contributors to system-wide delays.


6. Airline vs Destination Delay Patterns (Scatter Plot)

-> Shows how airlines perform at various destination airports based on delay averages.
-> Highlights route-specific delay issues and airport congestion patterns.



7. Monthly Flight Count by Status (Column Chart)

-> Analyzes monthly operational behaviour and flight status frequency.
-> Useful to detect seasonal patterns and high-cancellation periods.


8. Average Delay Minutes by Delay Reason (Bar Chart)

-> Measures severity of each delay cause (e.g., weather delays might be fewer but longer).
-> Guides prioritization of operational improvement areas.


9. Average Delay by Airline & Flight Status (Column Chart)**

-> Displays the relationship between flight status and average delay for each airline.
-> Provides deeper insight into operational behaviour beyond simple averages.


📌 Submission Details

Fork this repository to your own GitHub account, naming it AirFly_-[YourName] (replace [YourName] with your actual name).

Create a folder with your name inside your forked repo and place all your work (code, dataset links, results, and a README).

Make regular and meaningful commits for every milestone.

Push your changes to your forked repository or upload your work manually.

Update your repository at every milestone to reflect your progress.
