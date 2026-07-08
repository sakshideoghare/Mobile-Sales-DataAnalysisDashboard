# MOBILE SALES DATA
## Interactive Dynamic Dashboard for Sales Analytics

### 1. Project Objective
The objective of this project is to design and build an interactive, dynamic dashboard that transforms raw mobile phone sales transaction data into clear, actionable business insights. Rather than presenting static figures, the dashboard allows sales performance to be explored dynamically across multiple dimensions - month-wise, year-wise, brand-wise, city-wise, and payment-mode-wise - so that trends, patterns, and outliers can be identified quickly and intuitively.
The specific goals of the project are to:
●Consolidate raw, transaction-level mobile sales data into a clean, analysis-ready dataset.
●Track and compare sales performance (units sold and revenue) across different time periods - monthly and yearly.
●Identify top-performing mobile brands, models, and cities driving revenue.
●Understand customer behavior through payment method preferences, ratings, and demographic patterns.
●Present all of the above through a single, interactive dashboard that supports filtering and drill-down, enabling faster and more informed business decisions.

### 2. Dataset Used
The dashboard is built on a transaction-level mobile sales dataset containing 3,835 individual sales records spanning four years, from 2021 to 2024. Each record captures details of a single mobile phone sale, including the transaction date, brand, model, pricing, customer information, and payment method.
<a href="https://github.com/sakshideoghare/Mobile-Sales-DataAnalysisDashboard/blob/main/Mobile%20Sales%20Data.xlsx">Mobile Sales Dataset</a>

### Questions(KPIs)
What is the total revenue and units sold, and how have they changed year-over-year?
Which months/years performed best or worst in sales?
Which brand generates the highest revenue and units sold?
Which mobile models are the top sellers?
Which cities contribute the most to overall revenue?
What is the most preferred payment method among customers?
How satisfied are customers, based on average ratings?
Is there any seasonality in sales (e.g., certain months consistently higher)?
Which brand/city combinations are underperforming and need attention?

Dashboard Interaction <a href="https://github.com/sakshideoghare/Mobile-Sales-DataAnalysisDashboard/blob/main/DashboardImg.PNG">Visualization of Dashboard</a>

### 3. Process

The project followed a structured data analytics workflow, moving from raw data to a fully interactive dashboard:
3.1 Data Collection & Understanding
The raw mobile sales dataset was imported and reviewed to understand its structure, fields, and scope, identifying the year range, brands, cities, and transaction volume.
3.2 Data Cleaning & Preparation
The data was checked for inconsistencies (such as irregular date/day-name entries), missing values, and formatting issues. A calculated Revenue field (Units Sold x Price Per Unit) was derived to support financial analysis alongside unit-volume analysis.
3.3 Exploratory Data Analysis
Initial analysis was carried out to summarize overall trends - total revenue, total units sold, average price point, average customer rating, and the spread of sales across brands, cities, and payment methods.
3.4 Dashboard Design & Development
An interactive dashboard was built with slicers/filters for Month, Year, Brand, and City, enabling users to dynamically view sales performance for any combination of these dimensions. Visual elements such as trend lines, bar charts, and KPI cards were used to make comparisons intuitive.
3.5 Insight Generation
With the dashboard in place, key patterns were extracted and validated against the underlying data to form the basis of the project's business insights and recommendations.

### Dashboard

<img width="1167" height="661" alt="DashboardImg" src="https://github.com/user-attachments/assets/7da1d4f3-6a5b-4445-8b0c-dfd7cbd696e6" />

### 4. Project Insights

4.1 Year-wise Performance
Revenue grew sharply from 2021 to 2022 (from ~₹5.88 crore to ~₹26.20 crore), before gradually tapering in 2023 (~₹25.33 crore) and 2024 (~₹19.51 crore). This suggests 2022 was a peak sales year, with a mild but consistent decline in the two years following - a signal worth investigating further (e.g. market saturation, pricing, or competition).
4.2 Brand-wise Performance
All five brands perform competitively, with no single brand dominating the market. Apple leads narrowly in both revenue (~₹16.16 crore) and units sold (3,932), closely followed by Samsung, OnePlus, Vivo, and Xiaomi - indicating a fairly balanced, competitive brand landscape rather than one driven by a single market leader.
4.3 Top-Selling Models
The iPhone SE and Vivo Y51 are the top-selling individual models by unit volume, followed closely by the OnePlus Nord, Galaxy Note 20, and Galaxy S21 - showing strong demand at both premium and mid-range price points.
4.4 City-wise Performance
Sales are heavily concentrated in metro cities: Delhi alone contributes ~₹20.39 crore in revenue - by far the largest share - followed by Mumbai (~₹12.72 crore). All other cities, including Ranchi, Chennai, and Rajkot, contribute a much smaller share individually, highlighting Delhi and Mumbai as the primary revenue-driving markets.
4.5 Payment Method Preference
Customer payment behavior is fairly evenly split across methods, with UPI marginally the most preferred (1,011 transactions), followed closely by Debit Card (948), Credit Card (947), and Cash (929) - reflecting a healthy mix of digital and cash-based payment adoption.
4.6 Seasonality
Monthly revenue remains relatively stable throughout the year (roughly ₹5.7-6.9 crore per month) without extreme seasonal spikes, though January, March, May, and July show slightly stronger performance - useful for planning inventory and promotional timing.

### 5. Conclusion & Recommendations
The dashboard successfully demonstrates how transaction-level mobile sales data can be transformed into an interactive analytics tool that supports month-wise, year-wise, brand-wise, and city-wise exploration. It provides a clear, single view of business performance that would otherwise require manual analysis across a large raw dataset.
Key Recommendations
●Investigate the revenue decline post-2022 to identify whether it stems from market saturation, pricing pressure, or competitor activity, and adjust strategy accordingly.
●Prioritize Delhi and Mumbai for high-impact marketing and inventory planning, given their disproportionate share of revenue, while identifying growth potential in mid-tier cities.
●Continue to support and promote top-performing models (iPhone SE, Vivo Y51, OnePlus Nord) while monitoring lower-performing models for potential portfolio rationalization.
●Encourage UPI adoption further through incentives, given it is already the most-used payment method, to reduce cash-handling overhead.
●Use the average customer rating (3.69/5) as a baseline to investigate post-sale satisfaction drivers and identify opportunities to improve customer experience.
●Extend the dashboard with predictive elements (e.g. sales forecasting) in future iterations to move from descriptive to predictive analytics.
Overall, this project reflects a complete, end-to-end data analytics workflow - from raw data to a decision-ready interactive dashboard - and demonstrates the ability to extract meaningful, business-relevant insights from real-world sales data.




