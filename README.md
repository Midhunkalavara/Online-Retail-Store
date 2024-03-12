# Online Retail Store: Exploratory Data Analysis with Python

## Table of Contents

- [Project Overview](#project-overview)
- [Project Tasks](#project-tasks)
- [Dataset Information](#dataset-information)
- [Summary](#summary)
- [Recommendations](#recommendations)

## Project Overview
This project focuses on leveraging data analysis techniques to gain insights into the operations of an online retail store. By examining real sales data, our objective is to facilitate informed decision-making, ultimately aiding the store in making better business choices. Key focus areas include understanding:

- What are the most purchased items?
- When is the peak buying time?
- Where are the customers located?
- What are data characteristics?

By addressing these questions, we aim to provide actionable recommendations for the store's improvement.

## Project Tasks
In pursuit of our objectives, we'll undertake the following tasks:

1. **Data Inspection:**
   - Load the sales information from a file into a computer program for efficient analysis.

2. **Data Cleaning:**
   - Ensure data accuracy and organization for reliable results.

3. **Data Summarization:**
   - Gain a basic understanding of the data, including average purchase amounts and the distribution of values.

4. **Visualization:**
   - Create charts and graphs to illustrate data trends, highlighting popular products and peak purchase days.

5. **Pattern Recognition:**
   - Identify connections between different pieces of information, exploring potential relationships.

6. **Conclusion Drawing:**
   - Based on findings, generate ideas to enhance sales and customer satisfaction.

## Dataset Information
**File:** Online Retail.xlsx

**Contents:**
- InvoiceNo: Invoice number of the transaction
- StockCode: Unique code of the product
- Description: Description of the product
- Quantity: Quantity of the product in the transaction
- InvoiceDate: Date and time of the transaction
- UnitPrice: Unit price of the product
- CustomerID: Unique identifier of the customer
- Country: Country where the transaction occurred

## Summary

### Busiest day:
Thursdays seem to be the busiest day of the week based on total quantity sold.

![Weekly sales trends](https://github.com/Midhunkalavara/Online-Retail-Store/assets/114302683/01868c7f-9d38-4d21-925d-09d4559577e8)

### Optimal Months: 
November takes the lead as the top-selling month, closely followed by October and December.

![Monthly sales trends](https://github.com/Midhunkalavara/Online-Retail-Store/assets/114302683/bd33f04c-c5f5-439e-8dc2-04beac1d133b)

### Top products:
The analysis identified the best-selling products by total quantity sold.
- "JUMBO BAG RED RETROSPOT" is the top-selling product, followed by "WORLD WAR 2 GLIDERS ASSTD DESIGNS" and "WHITE HANGING HEART T-LIGHT HOLDER".

![Top products](https://github.com/Midhunkalavara/Online-Retail-Store/assets/114302683/da5ac99a-f561-4a94-af28-eb1c771b4961)

### Top countries:
The analysis revealed the top countries contributing to sales.
- The United Kingdom is the leading country by total quantity sold, followed by the Netherlands and EIRE.

![Country-wise sales](https://github.com/Midhunkalavara/Online-Retail-Store/assets/114302683/7c6f23ca-e6a3-41ab-ad41-8aa5157c4553)

### Statistical summary of Quantity and UnitPrice:

|           | Count  | Mean                 | Std                  | Min  | 25%  | 50%  | 75%  | Max   |
|-----------|--------|----------------------|----------------------|------|------|------|------|-------|
| Quantity  | 534,500| 9.39                 | 26.17                | -635 | 1    | 3    | 10   | 666   |
| UnitPrice | 534,500| 3.54                 | 7.55                 | 0.0  | 1.25 | 2.08 | 4.13 | 296.61|

1. **Quantity:**
   - The dataset consists of 534,500 entries for the "Quantity" variable.
   - The mean (average) quantity sold is approximately 9.39 items per transaction.
   - The standard deviation of 26.17 indicates a notable variation in the quantity sold.
   - The minimum quantity is -635, which might indicate data anomalies or returns.
   - The majority of transactions (25th to 75th percentile) involve quantities ranging from 1 to 10 items.
   - The maximum quantity sold in a single transaction is 666.

2. **UnitPrice:**
   - Similar to "Quantity," there are 534,500 entries for the "UnitPrice" variable.
   - The mean unit price is approximately 3.54, indicating the average price per item.
   - The standard deviation of 7.55 suggests variability in unit prices across transactions.
   - The minimum unit price is 0.0, which might require further investigation.
   - Most transactions (25th to 75th percentile) have unit prices ranging from 1.25 to 4.13.
   - The maximum unit price observed is 296.61.

#### Scatter plot for Quantity vs UnitPrice:

![Scatter plot for Quantity vs UnitPrice](https://github.com/Midhunkalavara/Online-Retail-Store/assets/114302683/a8963acb-2bfc-4d77-8f54-6c59d3f7a016)

## Recommendations

1. **Optimize Thursday Promotions:** Since Thursdays are the busiest days, consider running special promotions or marketing campaigns specifically on Thursdays to capitalize on increased customer activity.
   
2. **Strategic November Planning:** Given that November is the top sale month, consider planning special promotions, discounts, or exclusive product releases to maximize sales during this peak period. Additionally, pay attention to October and December as they also show strong sales.

3. **Featured Products:** Highlight and promote the top-selling products, especially "JUMBO BAG RED RETROSPOT," "WORLD WAR 2 GLIDERS ASSTD DESIGNS," and "WHITE HANGING HEART T-LIGHT HOLDER" to maximize sales.

4. **Target Key Countries:** Focus on marketing efforts and promotions in the top countries – the United Kingdom, Netherlands, and EIRE – to enhance customer engagement and boost sales in these regions.

5. **Transaction Size Optimization:** Encourage customers to increase their transaction sizes by offering discounts for larger quantities or bundling related products together.

6. **Price Point Considerations:** Evaluate the pricing strategy, considering the wide range observed (from 0 to nearly 297). Ensure competitive pricing for popular items while re-evaluating the pricing of potential outliers.

7. **Identify and Address Outliers:** Investigate and manage outliers in quantity and price. This may involve reviewing product listings, ensuring accurate pricing, and addressing any potential data anomalies that could impact customer experience.

8. **Customer Engagement:** Leverage insights into average quantity sold per transaction to tailor marketing strategies and engage with customers in a way that encourages them to purchase more items.

9. **Supply Chain and Inventory Management:** Ensure that inventory for the top-selling products is well-stocked to meet the demand. Consider adjusting stock levels based on the observed variability in purchase quantities.

10. **Data-Driven Decision-Making:** Continue to use descriptive statistics and other analytics to inform further analysis and data-driven decisions for ongoing improvements in the online retail store's performance.

11. **Customer Feedback and Reviews:** Solicit and analyze customer feedback to understand preferences and areas for improvement. Positive reviews for top products can be leveraged in marketing efforts, while addressing concerns promptly can enhance customer satisfaction.

Implementing these tips should help the online retail store optimize its operations, enhance customer satisfaction, and ultimately increase sales.
