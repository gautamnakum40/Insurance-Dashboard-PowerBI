# Insurance_Dashboard_Power-BI

## Overview
This project presents an interactive Power BI dashboard built using insurance data. The dashboard provides insightful visualizations and key performance indicators (KPIs) to analyze various aspects of the insurance industry, including customer demographics, claim trends, and policy distributions.

## Objective
The primary goal of this project is to transform raw insurance data into meaningful insights through interactive visualizations. The dashboard aims to help stakeholders:

- Understand customer segmentation
- Analyze claims and policy trends
- Identify key performance metrics
- Improve decision-making through data-driven insights

## Key Areas of Focus

- Customer Demographics: Analysis of age, gender, and region-wise distribution of policyholders.
- Policy Analysis: Breakdown of different insurance policy types and their distribution.
- Claims Analysis: Examination of claim frequency, amount, and trends over time.
- Financial Insights: Revenue trends, total claims paid, and profitability metrics.
- Interactive Filters: Dynamic slicers for users to drill down into specific data points.

## Tools and Technologies Used

- Power BI: For data visualization and dashboard creation
- Excel/CSV: For data storage and processing
- Power Query: For data transformation and cleaning
- ETL: Data was extracted, transformed, and loaded into Power BI for analysis.  

## Skills Demonstrated

- Data cleaning and transformation
- Dashboard design and visualization
- Interactive reporting using Power BI
- Data-driven decision-making

## Dataset

The Insurance dataset contains the following information :
  1.  Customers : CustomerID, Gender, Age
  2.  Transactions (Policies and Claims Information) : PolicyNumber, PolicyStartDate, PolicyEndDate,	PremiumAmount, CoverageAmount, ClaimNumber,	ClaimDate, ClaimAmount,	ClaimStatus.
  3.  Products : PolicyType

You can find the Insurance dataset [here](https://github.com/gautamnakum40/Insurance_Dashboard_Power-BI/blob/main/InsuranceData.csv).

## Key Metrics and Visualizations: 

1. Total Policies Issued : Displays the total of all active/Inactive policies.
2. Total Amounts : Shows Total of Premium Amount, Coverage Amount,Claim Amount.
3. Total Claims Processed : Displays all claims status (Settled, Pending, Rejected).
4. Top Policy Types by Premium Revenue : Showa Policy types contributing the most revenue.
5. Claim Amount By Age Group : Highlights Claim Amount using Age group.

## ETL Process:
An ETL (Extract, Transform, Load) process was implemented to prepare the data for analysis:

- Extract: Data was extracted from the Csv file and it's containg transactions, customer information, and product records.
- Transform: The data was cleaned, transformed, handle missing values, and format it for business intelligence analysis. Key transformations included:
   - Creating Age Group ranges using IF functions.
   - Determining Policy Status using IF functions with a date range.
- Load: The cleaned and transformed data was loaded into Power BI for building the dashboards and creating visual insights.

## Interactive Power BI Dashboard 

![Dashboard](https://github.com/gautamnakum40/Insurance_Dashboard_Power-BI/blob/main/img/Dashboard.png)

## Insights 

1. Customer Demographics :
   - Age Distribution: Most policyholders fall within the 30-50 (Adult) age group, making them the primary target audience.
   -  Gender Trends: Male customers purchase more health insurance, whereas female customers purchase travel insurance policies.

2. Policy Analysis :
   - Travel Insurance has the highest number of policies issued.
   - Home Insurance shows lower number of policies issued.

3. Claims Analysis Insights :
   - 4.4K of claims are Rejected, 2.3k are Pending, and 3.4k are approved (Settled).
   - Rejected claims are mostly from Travel Insurance

4. Financial Insights :
   - Total Premium Collected is significantly higher than Total Claims Paid, ensuring profitability.
   - Travel insurance contributes the most to premium revenue.
   - Home insurance has the lowest contribution to overall revenue.

  
