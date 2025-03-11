# Hospitality Domain Dashboard - Using Power BI

## Overview
This Power BI project presents interactive dashboards analyzing key metrics across multiple hotel properties under Atliq. The dashboards include detailed reports on revenue, occupancy rates, ADR (Average Daily Rate), and customer ratings, segmented by property and city. Weekly data tracking provides insights into performance trends, room utilization, and platform efficiency, aiding in optimizing hotel operations and decision-making.

## PDF File
You can view or download the following PDF file for more details:

- [Hospitality Domain Dashboard Report](https://github.com/saurabhtripathiworks/Hospitality-Domain-Dashboard---Using-Power-BI/blob/main/Hospitality%20Domain%20Dashboard.pdf)

## About this Dataset
The dataset includes five CSV files covering dates, hotels, rooms, aggregated bookings, and individual bookings. Key columns provide insights into room categories, booking details, guest counts, revenues, and ratings, supporting a comprehensive analysis of hotel operations and customer behavior.

In this project, data was initially loaded from Excel files into Power BI. I used Power Query to clean the data by removing duplicates, fixing missing values, and formatting columns. Relationships were then established between the tables to enable comprehensive analysis. A table called `Key Measures` was created to calculate important metrics and provide actionable insights.

## Tools Used
- **Excel**: Data loading and preparation.
- **Power Query**: Data cleaning and transformation.
- **DAX (Data Analysis Expressions)**: Data modeling and calculations.
- **Power BI**: Dashboard creation and visualization.

## Insights
  1.There is a fluctuation in PEVPAR (Per-Available-Room Revenue) with occupancy, but the ADR (Average Daily Rate) remains constant. Therefore, the hotel can adjust pricing       based on occupancy to maximize revenue.<br>
 2.Hotels with the lowest occupancy rates tend to have lower customer ratings as well. It’s important to identify the reasons behind these low ratings. Addressing these          issues can improve guest satisfaction and potentially increase both occupancy and ratings.<br>
  3.ADR remains almost the same across various booking platforms but is higher on direct offline bookings. Offering discount coupons for promotions on the hotel’s own             platform can attract more customers, as no commission is paid to third-party platforms.
  
- **Overall Metrics:**
  - Total revenue: 1,688 million
  - Average RevPAR: 7,337
  - Average Occupancy: 58%
  - Average ADR: 12,696
  - Realisation %: 70%
  - Cancellation %: 24%-26%
  
- **Top Performing Properties:**
  - Atliq Exotica, Mumbai: Revenue 117M, ADR 16,141, Occupancy 66%
  - Atliq Palace, Mumbai: Revenue 100M, ADR 16,016, Occupancy 66%
  
- **Lowest Performing Properties:**
  - Atliq Exotica, Hyderabad: Revenue 47M, ADR 9,111, Occupancy 45%
  - Atliq Bay, Mumbai: Revenue 51M, ADR 15,167, Occupancy 45%
