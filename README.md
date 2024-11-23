## Customer Churn Analysis: Insights from Bank Data

### Problem Statement  
A bank wanted to understand the key factors contributing to customer churn in order to improve retention strategies. Using a dataset of 10,000 customers, the goal was to analyze customer behavior and identify at-risk customers. As a Data Analyst, I developed an interactive Power BI dashboard to provide actionable insights.

---

### Steps Followed & Learning from This Project

1. **Data Understanding**  
   - Explored the provided dataset containing 10,000 customer records to understand the features affecting churn, such as demographics, account details, and customer behavior.

2. **Data Connection & Cleaning**  
   - Connected the dataset to Power BI and performed ETL (Extract, Transform, Load) processes to clean the data, handling missing values, duplicates, and inconsistencies.

3. **Data Modeling**  
   - Created a **Date Table** using DAX functions to enable time-based analysis.  
   - Designed a **star schema** model to represent customer demographics, churn data, and financial attributes.

4. **Key Measures Creation**  
   - Built measures to calculate **Churn Rate**, **Retention Rate**, and customer **Lifetime Value (LTV)** using DAX.  
   - Applied functions like `CALCULATE`, `IF`, and `SUMX` to identify customer groups with high churn potential.

5. **Behavioral Segmentation**  
   - Segmented customers based on **demographics** (age, gender), **account balances**, **credit scores**, and **geography** (France, Germany, Spain) to identify churn drivers.  
   - Analyzed customer activity levels, credit card ownership, and product preferences to classify at-risk customers.

6. **Visualization & Dashboard Development**  
   - Created visualizations such as bar charts, line graphs, and heat maps to show churn trends across demographics, regions, and financial factors.  
   - Added slicers to enable the dynamic exploration of trends based on different segments (e.g., gender, age group, country).

7. **Insights & Storytelling**  
   - Used the dashboard to tell a clear story:  
     - Churn is highest among **middle-aged customers (41-50)** and **females**.  
     - Locations like **France** and **Germany** showed higher churn rates.  
     - **Low account balances (< $10K)** and **credit scores (700-800)** correlated with higher churn.  
     - Customers with low activity or without a credit card were at higher risk of churn.

8. **Final Report**  
   - Created an executive summary to present findings on churn drivers and actionable recommendations for targeted retention efforts.

---

### Final Result  
The **Customer Churn Analysis Dashboard** enabled the bank to:  
- Identify **key churn drivers** (age, gender, account balance, credit score, geography).  
- Segment customers based on **churn risk**, allowing for targeted retention strategies.  
- Visualize trends over time and monitor churn patterns across different customer groups.

The analysis revealed a **20.4% churn rate** and highlighted areas for strategic intervention.

![Screenshot 2024-11-21 124813](https://github.com/user-attachments/assets/314b30da-5beb-4e05-a2de-b8e7a7d3eff6)

[View the Interactive Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiYjlkOTcwNmItZTFmMi00ZDgxLWE3ZmQtNjY5OGU5NWJmMThjIiwidCI6IjZhYjJmZGI1LWNjOWUtNDJiMy04ZmI5LTA4ZWU1OGI5YzRhMSJ9)

---
