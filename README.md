# Telecom Customer Churn Drivers Analysis

## Project Background

Nexa, a telecommunications service provider, is facing increased competition, leading to a significant loss of customers.Data indicates that 26.5% of the customer base has churned, with half of them leaving due to the belief that competitors offer a better alternative. To address this challenge, a data-driven approach is essential to uncover key factors influencing customer churn. As a data scientist, my objective is to analyze customer behavior, identify patterns contributing to churn, and provide actionable insights to enhance retention strategies. 

## Business Question

The key churn factors being analyzed can be grouped into the following categories:

- **Service Offerings**: This analysis aims to answer the following questions:

  1. **Internet Service**: Do customers with internet service have lower churn rates? Which internet type retains customers best?
  2. **Payment Methods**: How does churn vary among _Bank Withdrawal_, _Credit Card_, and _Mailed Check payments_?
  3. **Contract Types**: How do churn rates compare across _Month-to-Month_, _One-Year_, and _Two-Year_ contracts?
  4. **Additional Services**: Does subscribing to _Online Backup_, _Premium Tech Support_, or _Unlimited Data_ reduce churn?
 
- **Demographic factors**: These two questions will be addressed:

  1. **Age Groups**: Which age group — Under 30, 30-64, or Over 64 — experiences the highest churn rate?

  2. **Marital Status**: Do married customers churn less frequently than single customers?

## Insights Summary

- **Internet Service**: _Fiber optic_ has the highest churn rate at **40.7%**, followed by _cable_ and _DSL_. Customers with no internet service churn the least frequently (**7.4%**).

- **Payment Methods**: _Credit card_ payments have the lowest churn rate at **14.5%**, whereas _mailed checks_ (**36.9%**) and _bank withdrawals_ (**34.0%**) have churn rates more than double that of _credit cards_.

- **Contract Type**: **45.8%** of customers on a _month-to-month_ contract churn, compared to **10.7%** for _one-year_ contracts and only **2.5%** for _two-year_ contracts.

- **Premium Tech Support**: Customers who did not subscribe to _Premium Tech Support_ churned **twice as frequently** as those who subscribed (**31.2%** vs. **15.2%**).

- **Unlimited Data**: Customers who paid for _Unlimited Data_ churned **twice as often** as those who did not (**31.7%** vs. **16.0%**).

- **Online Security**: _Online security_ services **significantly enhance retention**, with only **14.6%** of subscribers churning, compared to **31.3%** of non-subscribers.

- **Age Groups**: Customers **over 65** have an **extremely high churn rate** (**41.7%**), while those **under 65** churn at **23.6%**.

- **Marital Status**: Single customers are more likely to churn compared to married customers (**33.0%** vs. **19.7%**).
