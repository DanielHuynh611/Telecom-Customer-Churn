# Telecom Customer Churn Drivers Analysis

## Project Background

Nexa, a telecommunications service provider, is facing increased competition, leading to a significant loss of customers.Data indicates that 26.5% of the customer base has churned, with half of them leaving due to the belief that competitors offer a better alternative. To address this challenge, a data-driven approach is essential to uncover key factors influencing customer churn. As a data scientist, my objective is to analyze customer behavior, identify patterns contributing to churn, and provide actionable insights to enhance retention strategies. 

## Business Questions

The key churn factors being analyzed can be grouped into the following categories:

- **Service Offerings**: This analysis aims to answer the following questions:

  1. **Internet Service**: Do customers with internet service have lower churn rates? Which internet type retains customers best?
  2. **Payment Methods**: How does churn vary among _Bank Withdrawal_, _Credit Card_, and _Mailed Check_ payments?
  3. **Contract Types**: How do churn rates compare across _Month-to-Month_, _One-Year_, and _Two-Year_ contracts?
  4. **Subscription Services**: Does subscribing to _Online Backup_, _Premium Tech Support_, or _Unlimited Data_ reduce churn?
 
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

## Recommendations

1. **Enhance Internet Service & Unlimited Data Plans**
  
    Customers who pay for _fiber optic internet_ and _unlimited data_ are significantly more likely to churn. It is recommended to **investigate service quality issues** and consider **improving reliability**, **speed**, or **pricing** to increase satisfaction and retention.

2. **Targeted Retention Strategies for Senior and Married Customers**
  
    Customers _over 65_ and _married individuals_ exhibit higher churn rates. Developing more **appealing offers**, **loyalty programs**, or **bundled services** that better tailored to their needs may encourage long-term commitment.

3. **Promote Online Security & Premium Tech Support**
  
    Subscribing to _online security_ and _premium tech support_ correlates with lower churn rates. **Promoting these services through discounts and bundled plans** could encourage adoption and improve customer retention.  
  
## Insights Deep Dive

### Impact of Service Offerings on Customer Churn  

#### Question 1: How does internet type affect churn rates among Fiber Optic, Cable, DSL, and No Internet Service?

- _Fiber optic users_ have the **highest churn rate (40.7%)** and the **lowest satisfaction score (2.9)**, indicating significant dissatisfaction.  
- _Cable_ (**25.7%**) and _DSL_ (**18.6%**) users experience lower churn rates and slightly better satisfaction scores (**3.2** and **3.3**, respectively), suggesting better retention.  
- **Customers without internet service** report the **highest satisfaction score (3.8)** and the **lowest churn rate (7.4%)**, showing minimal service-related dissatisfaction.  
- It is estimated with 99% confidence that **customers with any internet service** have a **churn rate that is 22 to 27 percentage points higher** than those without internet service, highlighting the need for service improvements.

*Figure 1: Churn rate and satisfaction score by internet type*
![Internet_Type](https://github.com/user-attachments/assets/4dad26c6-2bfb-4a48-a199-e2679105242d)

#### Question 2: how do churn rates vary by payment method: Bank Withdrawal, Mailed Check, and Credit Card?

- _Mailed Check_ and _Bank Withdrawal_ users have **higher churn rates** (**36.9%** and **34.0%**) and **lower satisfaction scores** (**3.0** and **3.1**), indicating potential inconvenience or dissatisfaction.
- _Credit Card_ users experience the **lowest churn rate** (**14.5%**) and the **highest satisfaction score** (**3.5**), suggesting a smoother payment experience.
- It is estimated with 99% confidence that customers who pay by _Mailed Check_ or _Bank Withdrawal_ have a **churn rate that is 17 to 22 percentage points higher** than those who pay by _Credit Card_.

*Figure 2: Churn rate and satisfaction score by payment method*
![Payment_Method](https://github.com/user-attachments/assets/ece638be-ad4a-43cd-be28-3d8d8a8b9748)

#### Question 3: how do churn rates vary across Month-to-Month, One-year, and Two-year contracts

- Customers on _Month-to-Month_ contracts experience the **highest churn rate** (**45.8%**) and the **lowest satisfaction score** (**2.9**).
- In contrast, _One-Year_ (**10.7%** churn, **3.6** satisfaction) and _Two-Year_ (**2.5%** churn, **3.7** satisfaction) contracts have significantly lower churn rates and higher satisfaction levels, suggesting that long-term contracts are associated with greater customer loyalty.

*Figure 3: Churn rate and satisfaction score by contract types*
![Contratcs](https://github.com/user-attachments/assets/b35ed65c-4da0-4462-9ecd-dd28d0ecfbb4)


#### Question 4: Do additional subscription services: _Premium Tech Support_, _Unlimited Data_ and _Online Backup_ reduce customer churn?

##### i. Premium Tech Support

- Customers with _Premium Tech Support_ have a **significantly lower churn rate** (**15.2%**) compared to those without it (**31.2%**), indicating a potential retention improvement.
- However, **premium tech support does not lead to higher customer satisfaction**, suggesting that while it may reduce churn, it does not necessarily enhance the overall customer experience.
- It is estimated with 99% confidence that customers who subscribe to_ Premium Tech Support_ have a churn rate that is **13 to 19 percentage points lower** than those who do not subscribe.

*Figure 4: Churn rate and satisfaction score by premium tech support subscription*
![Premium_Tech_Support](https://github.com/user-attachments/assets/2ada99ef-889b-45c8-a4bd-6fcb8fd66cbc)

#### ii. Unlimited Data Downloads

- Customers with _Unlimited Data_ exhibit a **higher churn rate** (**31.7%**) than those without it (16.0%), suggesting that this service may not effectively retain users.
- Furthermore, their **satisfaction score is lower** (**3.1** compared to **3.6**), indicating that Unlimited Data users may have heightened expectations or encounter issues that affect their overall satisfaction.
- It is estimated with 99% confidence that customers with _Unlimited Data_ have a churn rate that is **13 to 18 percentage point higher** than those without it.

*Figure 5: Churn rate and satisfaction score by unlimited data downloads subscription*
![Unlimited_Data](https://github.com/user-attachments/assets/e2c3242e-e964-40d2-8b2e-364f28c5455b)


#### iii. Online Security
- Customers with _Online Security_ experience a **significantly lower churn rate** (**14.6%**) compared to those without it (31.3%), indicating that this service may enhance customer retention.
- However, their satisfaction score is **slightly lower** (**3.1** vs. **3.3**), suggesting potential areas for improvement in the service experience.
- It is estimated with 99% confidence that customers who subscribe to _Online Security_ have a churn rate that is **14 to 19 percentage points lower** than those who do not subscribe.


*Figure 6: Churn rate and satisfaction score by online security service*
![Online Security](https://github.com/user-attachments/assets/afcb0624-a295-45da-b6c5-d07636696418)

### Impact of Demographic Factors on Customer Churn

#### Question 1: Do churn rates differ across different age groups?

- Customers _over 65_ have the **highest churn rate** (**41.7%**) and the **lowest satisfaction score** (**2.9**) compared to younger age groups.
- In contrast, customers _aged 30–64_ and _under 30_ have **lower churn rates** (**21.7%–24.2%**) and **higher satisfaction scores** (**3.3**).
- It is estimated with 99% confidence that customers _over 65_ **churn 14 to 22 percentage points more frequently** than those under 65, highlighting the need for targeted retention strategies.

*Figure 7: Churn rate by age groups*
![Age_Groups](https://github.com/user-attachments/assets/2406c845-b20c-46d5-a52d-f3d641d13b39)


#### Question 2: Are married customers more likely to churn compared to single customers?

- _Married customers_ have a **lower churn rate** (**19.7%**) and **slightly higher satisfaction** (**3.3**) compared to _single customers_ (**33.0% churn, 3.2 satisfaction**).
- It is estimated with 99% confidence that _single customers_ **churn 11 to 16 percentage points more frequently** than their _married_ counterparts, highlighting the need for targeted retention strategies.

*Figure 8: Churn rate by marital status*
![Marital_Status](https://github.com/user-attachments/assets/eb7c590d-63b6-48d1-9303-8b732c6fe91a)

## Limitations and Caveats

- This analysis examines each churn factor individually, without accounting for potential interactions between different factors.
- The 99% confidence intervals should be interpreted with caution. These estimates assume a randomly selected sample, but the data is likely observational, which means that selection bias may be present.

## Conclusion

This analysis identified key drivers of customer churn for Nexa, revealing that contract type, payment method, and additional service subscriptions significantly impact retention. Month-to-month contracts, fiber optic internet, and unlimited data plans are associated with higher churn, while long-term contracts, credit card payments, and security services improve retention. Demographic factors, such as age and marital status, also play a role. These insights provide a data-driven foundation for targeted retention strategies to address customer pain points and improve satisfaction.




