# Bank-Loan-Analysis-Using-SQL-and-Power-BI
This project conducts a comprehensive analysis of bank loan data, leveraging **SQL** for data querying and manipulation, and **Power BI** for visualization and further analysis. The primary objective is to extract actionable insights related to loan applications, funding, repayments, and borrower demographics, facilitating informed decision-making in financial services.

## Objectives

- **Holistic Portfolio Assessment**: Provide an overarching view of the bank's loan portfolio performance.
- **Trend Identification**: Detect patterns in loan applications, approval rates, and repayment statuses.
- **Financial Health Evaluation**: Assess key performance indicators (KPIs) such as Total Funded Amount, Average Interest Rate, and Loan Status.
- **Strategic Decision Support**: Aid in strategic planning for the bank's credit and loan offerings.


## Methodology

1. **Database Creation and Data Ingestion**: Established a relational database in SQL Server to store and manage loan data.
2. **Data Analysis and Query Writing**: Developed SQL queries to extract KPIs, including total and monthly loan applications, funded amounts, average interest rates, and loan status breakdowns.
3. **Loan Categorization**: Classified loans as 'Good' or 'Bad' based on repayment status, enabling focused analysis on funded amounts and payments received.
4. **Temporal and Categorical Analysis**: Performed analyses based on issue month, state, loan term, employment length, loan purpose, and home ownership to uncover patterns and trends.
5. **Data Visualization**: Utilized Power BI to create interactive dashboards, providing a graphical representation of findings for enhanced interpretability.

## Why Use SQL?

**SQL (Structured Query Language)** is employed in this project for several reasons:

- **Efficient Data Management**: SQL excels at handling large datasets, allowing for efficient querying and manipulation of extensive loan records.
- **Data Integrity and Accuracy**: By using SQL, we ensure that data extraction and transformation processes maintain high levels of accuracy and consistency.
- **Complex Analytical Queries**: SQL enables the execution of complex analytical queries, facilitating in-depth analysis of various dimensions of the loan data.
- **Integration with Visualization Tools**: SQL databases integrate seamlessly with visualization tools like Power BI, streamlining the workflow from data extraction to visualization.

### Dashboard 1: Summary

#### Key Performance Indicators (KPIs) Requirements:

1. **Total Loan Applications:** Calculate the total number of loan applications received during a specified period, including Month-to-Date (MTD) and Month-over-Month (MoM) changes.
2. **Total Funded Amount:** Understand the total amount of funds disbursed as loans, monitor MTD Total Funded Amount, and analyze MoM changes.
3. **Total Amount Received:** Track the total amount received from borrowers to assess cash flow and loan repayment, including MTD Total Amount Received and MoM changes.
4. **Average Interest Rate:** Calculate the average interest rate across all loans, MTD, and monitor MoM variations.
5. **Average Debt-to-Income Ratio (DTI):** Evaluate the average DTI for borrowers, compute the average DTI for all loans, MTD, and track MoM fluctuations.

#### Summary Visualization:

**Loan Status Grid View:** Gain a comprehensive overview of lending operations and monitor loan performance categorized by 'Loan Status'. This grid view provides insights into metrics such as Total Loan Applications, Total Funded Amount, Total Amount Received, MTD Funded Amount, MTD Amount Received, Average Interest Rate, and Average DTI.
#### Summary Dashboard
![Summary Dashboard](/Output/Summary.png)

#### Overview Dashboard
![Overview Dashboard](/Output/Overview.png)

#### Details Dashboard
![Details Dashboard](/Output/Details.png)


### Dashboard 2: Overview

1. **Monthly Trends by Issue Date (Line Chart):** Identify seasonality and long-term trends in lending activities.
2. **Regional Analysis by State (Filled Map):** Identify regions with significant lending activity and assess regional disparities.
3. **Loan Term Analysis (Donut Chart):** Understand the distribution of loans across various term lengths.
4. **Employee Length Analysis (Bar Chart):** Assess how lending metrics are distributed among borrowers with different employment lengths.
5. **Loan Purpose Breakdown (Bar Chart):** Provide a visual breakdown of loan metrics based on stated purposes of loans.
6. **Home Ownership Analysis (Tree Map):** View how home ownership impacts loan applications and disbursements hierarchically.

### Dashboard 3: Details

#### Objective:

The Details Dashboard provides a comprehensive view of key loan-related metrics and data points, facilitating efficient access to critical information about loan portfolios, borrower profiles, and loan performance.

#### Dataset Used:

The bank loan analysis dataset comprises essential fields such as Loan ID, Address State, Purpose, Grade, Sub Grade, Annual Income, Loan Status, Last Payment Date, Verification Status, Debt-to-Income Ratio, and Interest Rates. These fields provide insights into borrower demographics, employment stability, loan characteristics, risk assessment, and payment behavior.


## Key Insights and Findings

- **Loan Application Trends**: Analyzed total loan applications, distinguishing between Month-To-Date (MTD) and Previous Month-To-Date (PMTD) applications to identify temporal trends.
- **Funding and Repayment Analysis**: Examined total funded amounts versus amounts received, providing insights into the bank's liquidity and loan performance.
- **Interest Rate and DTI Evaluation**: Assessed average interest rates and DTI ratios to understand the financial health of borrowers.
- **Risk Profiling**: Segmented loans into 'Good' and 'Bad' categories, offering a clear picture of the loan portfolio's risk profile.
- **Demographic and Purpose-Based Analysis**: Provided detailed breakdowns by loan status, purpose, state, term, and other factors to identify patterns and trends.

## Tools and Technologies Used

- **SQL Server**: For database management and data analysis.
- **Power BI**: For data visualization and dashboard creation.



## Conclusion

This project offers valuable insights into the bank's loan portfolio, highlighting areas of strength and opportunities for improvement. It serves as a robust model for data-driven decision-making in financial services.

---

