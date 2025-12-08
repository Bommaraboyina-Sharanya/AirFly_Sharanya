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

The Airline Performance and Delay Analysis Dashboard 🛬 provides a comprehensive operational overview of flight performance, delay patterns, cancellations, and route-level insights. Each visual serves a specific analytical role.

1. KPI Cards (Top Summary Metrics)

1.1 Total Flights (2M)

Purpose: Displays the total number of flights recorded in the dataset.
Insight: Provides a high-level operational volume overview and acts as a denominator for calculating performance ratios across the dashboard.

1.2 Average Delay (10 minutes)

Purpose: Shows the overall mean delay across all flights.
Insight: A single performance indicator used to assess general efficiency and identify whether aggregate delays are within acceptable industry thresholds.

1.3 Count of Cancelled Flights (1.75M)

-Purpose: Shows the total number of cancelled flights in the dataset.
-Insight: Offers an immediate view of flight reliability issues and helps correlate cancellations with other factors displayed in the dashboard.

2. Slicer Panel (Airline, Month, Delay Reason, Day of Week)

-Purpose: Enables users to filter the dashboard based on airline, month, reason for delay, or weekday.
-Insight: Allows stakeholders to perform targeted analysis, observe patterns for specific carriers, and identify seasonal or operational variations.

3. Count of FlightID by Flight Status (Pie Chart)

-Purpose: Represents the proportion of flights grouped by their final status (Cancelled, Diverted, Early Arrival, Small Delay, Medium Delay, etc.).
-Insight: 
  Highlights the distribution of operational outcomes.
  Shows what percentage of flights experience delays vs cancellations vs normal operations.
  Helps identify which statuses dominate the dataset.

4. Average of Delay Minutes by Airline (Horizontal Bar Chart)

-Purpose: Compares airlines based on their average delay duration.
-Insight:   Enables direct benchmarking between carriers.
                Helps identify which airline performs best and which consistently faces longer delays.
                Valuable for operational improvement and competitive analysis.

5. Count of Delay Status by Delay Reason (Doughnut Chart)

-Purpose: Breaks down the total number of delay instances by the corresponding reason (Weather, Maintenance, Security, Air Traffic, etc.).
-Insight:  Shows which operational areas contribute most to delays.
              Helps management prioritize areas for process improvement.
              Highlights dominant delay categories such as weather or system maintenance.

6. Airline vs Destination: Average Delay Patterns (Scatter Plot)

-Purpose: Visualizes how different airlines perform on various destinations in terms of average delay.
-Insight:  Identifies destination-specific delay .
              Shows variations across airports such as BOS, JFK, MIA, SEA, SFO.
              Helps reveal if certain routes consistently face longer delays, regardless of the airline.

7. Count of Flights by Month and Flight Status (Clustered Column Chart)

-Purpose: Displays monthly distribution of flights categorized by status (Cancelled, Diverted, Early, etc.).
-Insight:  Helps identify seasonal trends (e.g., cancellations in winter or peak traffic in summer).
              Supports forecasting and resource allocation.
              Shows how operational status fluctuates month-by-month.

8. Average of Delay Minutes by Delay Reason (Bar Chart)

-Purpose: Shows the average delay minutes for each delay reason category.
-Insight: Quantifies severity of each delay reason.
              Allows comparison between frequency  and impact (this visual).
              Useful for prioritizing improvements e.g., weather may be frequent but maintenance may cause longer delays.

9. Average Delay by Airline and Flight Status (Column Chart)

-Purpose: Displays delay averages for each airline based on flight status (Cancelled, Diverted, Early Arrival, Small Delay, Medium Delay).
Insight:  Enables multi-dimensional performance assessment.
              Shows not just overall delay (Visual #4) but how each status contributes to an airline’s delay pattern.
              Helps identify whether a carrier suffers more from cancellations or late departures.

-> Overall Purpose of the Dashboard

 This dashboard provides a complete analysis of airline operational behaviour, focusing on:

-Total operational scale
-Delay patterns and their root causes
-Airline-wise performance benchmarking
-Route and destination-specific variability
-Seasonal flight analysis
-Status distribution and reliability metrics


📌 Submission Details

Fork this repository to your own GitHub account, naming it AirFly_-[YourName] (replace [YourName] with your actual name).

Create a folder with your name inside your forked repo and place all your work (code, dataset links, results, and a README).

Make regular and meaningful commits for every milestone.

Push your changes to your forked repository or upload your work manually.

Update your repository at every milestone to reflect your progress.
