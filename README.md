# Mobile-Sales-Power-BI-Dashboard
Interactive Power BI dashboard analyzing mobile sales performance, revenue trends, product performance, customer ratings, geographical sales and payment preferences using DAX, Power Query and data visualization.
Project Overview
An interactive Power BI report designed to analyze mobile phone sales, monitor key business metrics, and explore sales performance across months, cities, mobile models, payment methods, and customer ratings.
Dashboard Preview

Business Objectives
- Monitor overall sales revenue, units sold, and transactions.
- Identify monthly sales volume trends and geographical sales patterns.
- Compare revenue across mobile models and payment methods.
- Understand the distribution of customer ratings.

<img width="1314" height="810" alt="Screenshot 2026-11-25 185656" src="https://github.com/user-attachments/assets/4805a689-c714-446e-a98b-b00a8de8fb4e" />

Key Performance Indicators
Metric	Displayed value
Total Sales Revenue	769M
Total Units Sold	19K
Total Transactions	4K
Average (as displayed in report)	40.11K


Values are rounded as displayed in the dashboard. The currency and definition of the average measure should be confirmed against the source data and report calculations.
Dashboard Features

Visualization	Purpose
KPI cards	Summarize key sales metrics
Map		Explore sales by city across India
Line chart	Track monthly units sold
Column chart	Compare sales revenue for the three mobile models displayed
Pie chart	Compare revenue shares by payment method
Funnel chart	Display customer rating counts
Month slicer	Select months for focused analysis


Key Business Insights
- January recorded the highest monthly sales volume (1,688 units), while February recorded the lowest (1,493 units).
- iPhone SE generated the highest revenue among the three mobile models displayed, followed by OnePlus Nord and Galaxy Note 20.
- UPI contributed the largest revenue share (26.22%), followed by debit cards (25.45%), credit cards (24.27%), and cash (24.06%). The distribution is relatively balanced.
- Five-star ratings were the most common, with approximately 1.49K recorded ratings.
Tools and Skills
- Microsoft Power BI Desktop
- KPI reporting and dashboard design
- Data visualization and exploratory analysis
- Sales trend analysis and business intelligence reporting
- Slicers and interactive report design
Suggested Business Actions
- Investigate the factors behind February's lower sales volume before making inventory or promotional decisions.
- Evaluate demand and profitability of leading mobile models before allocating inventory.
- Maintain support for multiple payment methods given their similar revenue contributions.
- Investigate low customer ratings to identify potential service or product improvements.

Repository Structure
Mobile-Sales-Power-BI-Dashboard/
├── README.md
├── Dashboard.png
└── Mobile_Sales_Dashboard.pbix

How to View the Report
1. Download the Mobile_Sales_Dashboard.pbix file from this repository.
2. Open it using Microsoft Power BI Desktop.
3. Use the month slicer and report visuals to explore sales performance.
4. If refreshing the report requires a local data source, update the source path in Power Query.

Future Enhancements
- Add year and brand filters where supported by the dataset.
- Add month-over-month and year-over-year growth measures where historical data is available.
- Introduce sales targets and profitability analysis if target and cost data are available.
- Replace the customer ratings funnel with a horizontal bar chart for easier category comparison.

About This Project
This portfolio project demonstrates how sales data can be presented through business intelligence reporting to support informed decision-making.![Uploading Screenshot 2026-11-25 185656.png…]()
