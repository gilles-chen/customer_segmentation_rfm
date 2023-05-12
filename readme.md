# Customer Segmentation Using RFM Analysis

<img width="1098" alt="segmentation" src="https://github.com/user-attachments/assets/05247671-b5af-421b-9b29-433a0946017c" />


## Overview
This project implements a comprehensive customer segmentation analysis using the RFM (Recency, Frequency, Monetary Value) methodology to analyze retail transaction data. The segmentation allows businesses to identify and target different customer groups with tailored marketing strategies based on their purchasing behaviors.

## Project Description
The project analyzes a retail dataset containing transaction records with information about customer purchases, including invoice details, quantities, prices, and timestamps. Through careful data processing and analysis, the project identifies distinct customer segments that can be targeted with specific marketing approaches.

## Methodology
1. **Data Cleaning and Preprocessing**
   - Handled missing values in critical fields
   - Removed duplicate entries
   - Filtered out cancelled transactions
   - Converted data types for appropriate analysis
   - Removed outliers to ensure data quality

2. **Feature Engineering**
   - Created derived metrics for RFM analysis:
     - **Recency**: How recently a customer made a purchase
     - **Frequency**: How often a customer makes purchases
     - **Monetary Value**: How much money a customer spends

3. **Customer Segmentation**
   - Applied clustering techniques to identify natural groupings in customer behavior
   - Used RFM scoring to categorize customers into actionable segments
   - Created customer profiles based on purchasing patterns

4. **Visualization and Insights**
   - Created visualizations to understand customer distribution
   - Analyzed country-specific purchasing behaviors
   - Examined transaction trends and patterns

## Key Findings
- Identified ten distinct customer segments with unique purchasing behaviors

## Technical Implementation
- **Languages and Libraries**: 
  - Python
  - pandas for data manipulation
  - NumPy for numerical operations
  - Matplotlib and seaborn for data visualization
  
- **Techniques**:
  - Statistical analysis
  - Exploratory data analysis
  - Data clustering
  - RFM modeling

## Conclusion
This customer segmentation project demonstrates the power of RFM analysis in understanding customer behavior and informing business strategy. By identifying distinct customer groups, businesses can optimize their marketing efforts, improve customer retention, and maximize revenue.
