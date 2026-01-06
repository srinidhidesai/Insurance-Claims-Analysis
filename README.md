### Insurance Claims Analysis Dashboard


# Problem Statement

SD Insurance Pvt. Ltd. needs to understand its policy performance, claim behavior, and risk exposure to improve operational efficiency and profitability. The company faces high claim rejection rates, particularly in Travel and Health insurance, which may impact customer trust. Additionally, coverage exposure is significantly higher than premium revenue, and adult customers contribute the highest claim amounts, indicating potential risk concentration. This dashboard aims to identify key risk drivers and operational gaps to support data-driven decisions in underwriting, claim processing, and pricing strategies.

# Steps Followed

Step 1: Loaded insurance claims data into Power BI Desktop using a SQL Server connection.
Step 2: Opened Power Query Editor and enabled Column Distribution, Column Quality, and Column Profile under the View tab.
Step 3: Switched column profiling from Top 1000 rows to Entire Dataset for accurate data validation.
Step 4: Verified data quality, minor null values were found in a few numeric claim-related columns.
Step 5: Excluded null values from KPI calculations, as they represented a negligible portion of the dataset and did not impact overall analysis.
Step 6: Applied a professional report theme for consistent visualization.
Step 7: Created calculated measures using DAX to derive key metrics such as premium amount, coverage amount, claim amount, and claim status counts.
Step 8: Added slicers for interactive filtering by Policy Type, Claim Status, Customer Age Group, and Policy Category.
Step 9: Used card visuals, bar charts, and pie charts to present KPIs and claim distribution insights clearly.
Note: By default, blank values are ignored while calculating averages in Power BI.

# Key KPIs

Total Premium Amount
Total Coverage Amount
Total Claim Amount
Claim Status Distribution (Settled, Rejected, Pending)
Policy-wise Premium Contribution
Customer Age Group Claim Contribution

# Insights

[1] Overall Performance

Premium, coverage, and claim amounts provide a high-level view of business exposure.
Coverage exposure significantly exceeds premium revenue, indicating potential risk.

[2] Claim Status Analysis

Rejected claims are higher than settled claims across most policy types.
Travel and Health insurance show higher claim rejection and risk exposure.

[3] Customer Insights

Adult customers contribute the highest claim amounts.
Claim distribution varies across age groups, indicating risk concentration.

[4] Policy-wise Insights

Travel and Health policies drive a major share of premium revenue.
These policies also contribute significantly to total claims and require closer monitoring.

### Tools Used
- Power BI
- DAX (basic measures)
- Data Modeling

