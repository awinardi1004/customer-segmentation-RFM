# Customer Segmentation using RFM Analysis
This project performs customer segmentation using the RFM (Recency, Frequency, Monetary) model to understand customer value and behavioral patterns. The analysis transforms raw transaction data into actionable customer groups that can support targeted marketing, retention strategies, and business decision-making.
## Project Overview
Customer segmentation is essential for identifying high-value customers and optimizing marketing efforts. Using historical transaction data, this project calculates RFM scores for each customer and classifies them into meaningful segments such as Champions, Loyal Customers, Potential Loyalists, At Risk, and Hibernating.

The entire workflow includes data cleaning, feature engineering, RFM scoring, segment assignment, and visualization.

## Workflow
1. Import Libraries <br>
Pandas, NumPy, Matplotlib, Seaborn, datetime
2. Load Transaction Dataset <br>
Load raw transactional data into a DataFrame for cleaning and processing.
3. Data Preparation <br>
- Convert date columns
- Remove duplicates
- Handle missing values
- Standardize data types
4. Calculate RFM Metrics
- <b>Recency</b>: days since last purchase
- <b>Frequency</b>: number of transactions
- <b>Monetary</b>: total amount spent
5. Score RFM Values <br>
Use quantile-based scoring to assign scores (1–4 or 1–5) for each R, F, and M metric.
6. Build RFM Segments <br>
Combine RFM scores to classify customers, e.g.:
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Hibernating
## Key Insights
- High-value customer groups contribute the largest portion of revenue
- Several customer segments show declining activity and require re-engagement.
- RFM segmentation helps prioritize marketing budgets based on customer value.
## Technologies Used
- Python
- Pandas
- NumPy
## Contact
Created by Winardi <br>
Linkedin : https://www.linkedin.com/in/winardi-/