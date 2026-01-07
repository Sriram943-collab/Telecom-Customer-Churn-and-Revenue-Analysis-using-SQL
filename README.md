# Telecom Customer Churn and Revenue Analysis using SQL

## Project Overview
This project analyzes customer churn behavior and revenue patterns in a telecom company using SQL.  
The goal is to understand why customers discontinue services, identify high-risk customer segments, and measure the financial impact of churn.

The analysis focuses on customer demographics, service usage, contract details, billing behavior, and payment methods using structured SQL queries.

---

## Business Context
Customer retention is a major challenge in the telecom industry due to high competition and similar service offerings.  
Customer churn directly impacts revenue stability and long-term business growth.

This project demonstrates how SQL-based data analysis can support effective customer retention strategies, pricing decisions, and revenue optimization.

---

## Dataset Description
The project uses a real-world telecom customer dataset containing over **7,000 customer records**.

- **Customer Demographics** – Gender, senior citizen status, tenure  
- **Service Information** – Internet service type and add-on services  
- **Contract Details** – Contract type and billing preferences  
- **Billing Data** – Monthly charges and total charges  
- **Churn Status** – Indicates whether the customer has discontinued service  

Each row represents a single customer.

---

## Database Design
A structured relational database schema was designed to organize the data efficiently.

- The **customers** table stores demographic and tenure information.  
- The **services** table captures service subscription details.  
- The **billing** table contains contract type, payment method, charges, and churn status.  

All tables are linked using the **customerID** field with primary and foreign key constraints.  
This design avoids data duplication and supports accurate join-based SQL analysis.

---

## Objectives
- Design a normalized relational database schema from raw customer data  
- Analyze overall customer churn trends  
- Identify churn drivers based on contract type, tenure, services, and pricing  
- Quantify revenue loss caused by customer churn  
- Segment customers based on churn risk and revenue contribution  
- Support data-driven customer retention strategies  

---

## Key Analysis Questions
- What is the overall customer churn rate?  
- How does customer churn behavior vary across different demographics?  
- What impact does contract type have on customer churn?  
- How does customer tenure influence customer retention?  
- Are higher monthly charges associated with higher churn?  
- Which payment methods are linked to higher churn rates?  
- How much total revenue has been lost due to customer churn?  
- Which customer segments should be prioritized for retention?  

---

## Key Insights
- More than **26% of customers** have churned, indicating a significant retention challenge.  
- Customers on **month-to-month contracts** exhibit the highest churn, while long-term contracts show strong retention.  
- **Senior citizens** have a significantly higher churn rate compared to non-senior customers.  
- Customers with **short tenure** are more likely to churn, highlighting the importance of early engagement.  
- Higher monthly charges are strongly associated with increased churn.  
- Customers using **automatic payment methods** show lower churn compared to manual payment options.  
- Approximately **₹2.86 million in revenue** has been lost due to customer churn.  
- A small group of high-value customers contributes a large share of total revenue, making targeted retention essential.  

---

## Conclusion
This project demonstrates how SQL can be used to transform raw telecom customer data into meaningful business insights.  
The analysis highlights key churn drivers and their financial impact, supporting data-driven decision-making for improving customer retention and revenue stability.

---

## Author
**Krishnasagarapu Sri Ram**
