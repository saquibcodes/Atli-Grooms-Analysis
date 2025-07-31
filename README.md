# Atli-Grooms-Analysis
In this, I'm conducting data analysis for Atli Grooms, a company in the Hospitality domain. Atli Grooms operates multiple five-star hotels and is facing significant competition. The primary objective of the analysis is to generate crucial revenue insights for the management of these hotels.


**Steps** :

Began by outlining the problem statement for Atli Grands, collaborating with a revenue manager (role-play) to identify crucial metrics.

Data Preparation (Power Query): Raw CSV data was imported into Power BI. Power Query was then used for transformation and cleaning, including expanding files, promoting headers, and creating necessary columns (e.g., custom 'date_type' for weekends).

Data Modelling: A star schema was implemented in Power BI's data model view, establishing logical relationships between fact and dimension tables (e.g., 'dim_date' linked to 'fact_bookings' via 'check-in date').

DAX Calculations: DAX was extensively used to create calculated columns and all key measures (KPIs) such as Revenue, RevPAR, ADR, Occupancy, Realisation Percentage, and Cancellation Percentage.

Dashboard Visualisation: The Power BI dashboard was built with tables, KPI cards with week-on-week changes and trend tooltips, interactive slicers (City, Room Type, Month, Week Number), and conditional formatting for visual insights.


**Key Insights**:

The dashboard revealed evidence of a flat pricing strategy, as the Average Daily Rate (ADR) remained constant despite fluctuations in occupancy and RevPAR (Revenue Per Available Room). This indicates a missed opportunity for dynamic pricing or even weekday/weekend differential pricing, especially during peak seasons like summer holidays (May, June, July) when rates should ideally fluctuate.

Analysis of ADR by platform showed that the hotel was not utilising differential pricing on its own channels (e.g., direct offline/online bookings) to their full potential. While outright price differences across channels are not advised due to issues like bot scraping by aggregators, the hotel could leverage promotions or added value on its direct channels (e.g., discount coupons at checkout, complimentary services).

The dashboard highlights a strong, evident correlation between average customer ratings and hotel occupancy. Hotels with lower average ratings (e.g., Atle Grants Bangalore at 2.3) generally had the lowest occupancy rates compared to higher-rated properties (e.g., 4.2, 4.5).

Low occupancy and low ratings also coincided with higher cancellation rates. This suggests that customers might be booking these hotels as a backup or cancelling upon arrival due to unmet expectations (e.g., content mismatch with online photos/information, poor initial experience).

The dashboard facilitates Level 1 analysis (identifying overall problems) and Level 2 analysis (drilling down to specific cities, properties, room types, or channels to pinpoint the root cause of issues).

It enables the application of the Pareto Principle (80/20 rule), allowing management to identify and focus on the bottom-performing hotels (e.g., the lowest 20% in terms of occupancy or revenue) to address the majority (80%) of the problems and improve overall business.

The inclusion of week-on-week and month-on-month trends, alongside key metrics, provides crucial data movement insights for informed decision-making.
