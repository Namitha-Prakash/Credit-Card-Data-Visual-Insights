# Credit Card Analytics Dashboard – Power BI Project

---

## 1. Project Overview

This project involves building two interactive Power BI dashboards using Customer and Credit Card Transaction datasets.

The objective was to generate meaningful and actionable insights related to:

1. Customer demographics and credit behavior  
2. Credit card spending patterns  
3. Revenue and transaction performance  

Both dashboards are fully interactive and allow filtering by Gender, Age Group, Income Group, Week, and Spending Category.

The primary focus was on clean visual design, robust DAX calculations, and business-driven insights.

---

## 2. Dashboard 1 – Credit Card Customer Report

### 2.1 Objective

To analyze customer demographics, income distribution, credit behavior, and ownership patterns while enabling filtering by gender.

### 2.2 Key Features

1. **KPI Cards**
   - Total Customers: 10.29K  
   - Average Customer Satisfaction Score: 3.19  

2. Income distribution by Customer Job  

3. Customer count by Marital Status  

4. Education Level distribution  

5. Dependent count distribution  

6. Geographic distribution (Map visualization)  

7. Car Owner vs House Owner comparison  

8. Filters: Gender, Age Group, Income Group  

---

## 3. Dashboard 2 – Credit Card Transaction Report

### 3.1 Objective

To analyze transaction behavior, spending trends, card performance, and revenue generation patterns.

### 3.2 Key Features

1. **KPI Cards**
   - Total Transaction Amount: 46M  
   - Total Revenue: 9.99M  
   - Customer Acquisition Cost: 991K  
   - Average Utilization Ratio: 0.27  

2. Revenue by Card Category (Blue, Silver, Gold, Platinum)  

3. Interest Earned by Quarter  

4. Transaction Amount by State (Map visualization)  

5. Delinquent Account Distribution  

6. Credit Limit vs Transaction Amount by Age Group  

7. Filters: Gender, Week Number, Expense Type  

---

## 4. Tools and Technologies Used

1. Power BI  
2. Excel / CSV datasets  
3. Power Query (for data cleaning and transformation)  
4. DAX (for calculated columns and measures)  

---

## 5. Key DAX Calculations

1. Age Group categorization  
2. Income Group classification (Low / Medium / High)  
3. Total Revenue calculation  
4. Week Number extraction  
5. Current Week Revenue calculation  
6. Previous Week Revenue calculation  

---

## 6. Challenges Faced

1. **Data Cleaning**  
   Handling missing values and ensuring proper linkage between customer and transaction datasets using Customer ID.

2. **Data Modeling**  
   Establishing accurate relationships between demographic and transaction tables.

3. **DAX Calculations**  
   Designing calculated columns for Age Group, Income Group, and weekly revenue comparisons.

4. **Dashboard Design**  
   Maintaining clarity and readability while incorporating multiple slicers and visuals.

---

## 7. Key Insights

### 7.1 Customer Dashboard Insights

1. Business professionals generate the highest income contribution among job categories.  
2. Married customers form the largest customer segment.  
3. Customers in their 40s and 50s demonstrate higher credit limits and transaction amounts compared to younger groups.  
4. The delinquency rate is relatively low, indicating stable credit behavior overall.  

### 7.2 Transaction Dashboard Insights

1. The Blue card category generates the highest revenue compared to other categories.  
2. Transaction activity is stronger in specific states, indicating geographic concentration.  
3. Interest earned shows a declining trend across quarters.  
4. Middle-aged customers (40s–50s) contribute the highest transaction volume.  

---

## 8. Recommendations

1. **Target High-Value Age Groups**  
   Focus marketing campaigns on customers in their 40s and 50s who generate higher transaction volumes.

2. **Upsell Premium Cards**  
   Encourage Blue card customers to upgrade to Gold or Platinum cards for increased revenue potential.

3. **Geographic Expansion Strategy**  
   Target high-performing states with customized offers and loyalty programs.

4. **Monitor Interest Decline**  
   Investigate the causes of decreasing interest earnings and optimize credit strategies accordingly.

5. **Segment by Income and Gender**  
   Develop personalized offers based on income groups and spending behavior.
