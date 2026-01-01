# Customer Purchase Behavior & Retention Analysis

## Project Overview

This project analyzes e-commerce customer transaction data to understand purchasing behavior and evaluate the impact of customer retention on spending patterns.

The primary objective of the analysis is to compare returning and non-returning customers, identify differences in product category preferences, and observe how average purchase values change over time. The project emphasizes clear business insights rather than visual complexity.

## Dataset

The dataset contains customer-level purchase records with the following information:

- Customer demographics such as age, gender, and location  
- Transaction details including product category, purchase amount, payment method, and device used  
- Purchase date information  
- A flag indicating whether a customer is returning or not  

The data is structured at the transaction level, where each row represents a single purchase.

## Data Preparation

Before analysis, the dataset was cleaned and prepared to ensure reliable results:

- Standardized categorical text fields (product category, device used, payment method) to prevent fragmented analysis  
- Validated numeric fields such as age and purchase amount to ensure logical ranges  
- Created derived features including:
  - Customer type (returning vs non-returning)
  - Month of purchase for time-based analysis  
- Handled missing or ambiguous values (e.g., unspecified device information grouped as `UNKNOWN`) to avoid misleading interpretations  

These steps ensured consistency and accuracy across all analyses.

## Key Insights

The analysis led to the following insights:

- Returning customers exhibit a slightly higher average purchase amount compared to non-returning customers, indicating a modest positive impact of retention on spending.
- Product preferences differ by customer type, with returning customers spending more on Books while non-returning customers spend more on Clothing.
- Average purchase values remain relatively stable across months, suggesting limited seasonality in spending behavior.
- Approximately one-third of purchases come from returning customers, highlighting retention as a meaningful but not dominant contributor to overall transactions.

## Dashboard

An Excel dashboard was created to summarize findings and guide interpretation:

- KPI cards at the top provide a quick overview of overall spending and retention metrics.
- A retention comparison chart visually validates differences in average spending between returning and non-returning customers.
- A product category comparison chart explains where spending differences originate.
- A monthly trend chart provides time-based context for purchase behavior.

The dashboard is designed to prioritize clarity and decision-oriented insights rather than visual complexity.

## Files in This Repository

- Due to file size constraints, two Excel files are uploaded. One contains dashboard and summary analysis only.
- `Analysis Screenshots` — Images of the cleaned data and intermediate pivot tables required for analysis
- `Raw_Data` — Raw dataset used for analysis
- `README.md` — Project documentation  


## Tools Used

- Microsoft Excel (data cleaning, pivot-based analysis, dashboard design)




This project focuses on analytical reasoning and business interpretation. Visual elements are intentionally minimal to emphasize insight clarity and reproducibility.
