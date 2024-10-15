#  TELCO CHURNING

### PROJECT BACKGROUND 
The telecom industry uniquely relies on both customer experience and emotional factors to drive retention. Providers must not only deliver reliable products but also build strong emotional connections to foster long-term loyalty. Understanding these elements is crucial for reducing churn and boosting customer satisfaction.

This project leverages the Telco Customer Churn Dataset from IBM Congos to delve into consumer psychology and its impact on customer retention. By analyzing this data, we aim to identify the variables that enhance customer loyalty and reduce the likelihood of churn. Specifically, the project will explore two key areas: 

## **Enhancing Customer Loyalty & Predicting Customer Churn.**


### PROJECT STRUCTURE


<img width="1256" alt="Screenshot 2024-10-15 at 14 52 04" src="https://github.com/user-attachments/assets/e6177d6c-f48f-4f4a-9217-2875dc29ac63">

•Interactive PowerBI Dashboard: Available for download [here].

•Jupyter Notebook: Python code and libraries [[here]](https://github.com/ManuelMebrat/TELCO_CHURNING/blob/e332f57bb493e15494778e493ec88b48f1cfa4e4/Churn_Files/Telco_EDA.ipynb).

•SQL Queries: For QA testing of the dashboard [[here]](https://github.com/ManuelMebrat/TELCO_CHURNING/blob/f8651f0e24319716efd08e31b1e4deb6349dab68/Churn_Files/SQL_QA_Churn.pages).

•CSV Dataset: Download [[here]](https://github.com/ManuelMebrat/TELCO_CHURNING/blob/5dcf90172e48c1c4f5202ba78a73255ef38373a3/Churn_Files/Cchurn.csv).


### Conclusions, and recommendations:

**Enhancing Customer Loyalty:** Analyzing key variables that contribute to increased customer retention and long-term loyalty.

**Predicting Customer Churn:** Identifying the factors that lead to customer churn and anticipating potential risks.



# Why is this happenning?

Companies today often focus on customer acquisition, but what’s really happening is a lack of loyalty and high early churn. New customers frequently leave soon after joining, pointing to deeper issues beyond initial attraction. Without strong retention strategies, businesses risk losing customers as quickly as they gain them, missing opportunities for long-term growth and loyalty.


![image](https://github.com/user-attachments/assets/89264236-b8cb-4f1b-91cf-46473b33c1cc)

Out of 1,869 customers who churned, an alarming 55.49% left within the first 12 months. This underscores the critical importance of early customer experience, prompting two key questions:

**1. What is driving customers to stay?
2. What is causing them to leave?**

# 1. What is driving customers to stay?

### • A Loyal customer

![image](https://github.com/user-attachments/assets/e4c03504-6dc8-44ff-99c4-b53655bd5602)

• Our highest customer density is within the first 12 months, with 2,186 customers out of 7,043. After this period, we observe more stable retention. We define a loyal customer as one who remains beyond this initial 12-month period. Let’s explore customer behavior over time in more detail.

## Relationships

![image](https://github.com/user-attachments/assets/36b4c31f-c1f0-47a2-af7a-d2b9a57c34f8)

• Customers with dependents or partners tend to perceive a potential loss of stability and security as more significant. According to [Prospect theory,](https://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Behavioral_Decision_Theory/Kahneman_Tversky_1979_Prospect_theory.pdf) the fear of losing benefits or support from their current services may outweigh the perceived gains of switching providers. Having a partner can reduce the churn rate from 33% to 19%,and a dependant from 31% to just 15%. 

In conclusion, customers with family responsibilities show a higher propensity to stay with their current provider, as they value the stability and security it offers. 

However we can't directly control this variable, so what can we control to make they stay?

## Extra ~~services~~ Value

In a telco company, extra services refer to additional features or options offered to customers beyond basic services like internet, phonelines and multiple lines. For this company  the extra services are Only security, Online backup, Device protection, and Tech support. 

![image](https://github.com/user-attachments/assets/146d161c-3285-4bd5-98ab-807b624afa5b)

Understaing the cost of oportunity of diference churn rate between having or not this extra services, will give us an image of how much or company is losing by not engagig our customer with this services: 

![image](https://github.com/user-attachments/assets/42b3b9c4-4e2a-49f7-8491-2464fef6bc0d)

Extra services play a crucial role in reducing churn rates for telco companies. By bundling these additional features, the perceived value of the service increases, and customers are more hesitant to switch providers. Contributing to customer retention:

• Increased Perceived Value: Extra services enhance the overall package, making it harder for customers to find equivalent value elsewhere.

• Loss Aversion: Customers fear losing added protections (security, backup), making them less likely to switch providers.

• Customer Inertia: A comprehensive service package creates a barrier to leaving, as switching feels more complex and risky.

# **So how to increase Loyalty?**

**Personalized Support:** 

Implementing tailored support for customers with family. By understanding their need for stability and security, personalized offers or family bundles could resonate strongly with these segments.

**Loyalty Programs:** 

Creating a rewards or loyalty program that builds value over time would encourage longer-term relationships. For instance, customers could earn points for maintaining their service or using extra services, redeemable for discounts or upgrades.

**Flexible Bundles:** 

Creating flexible service bundles that offer customers more control over choosing extra services like security or backup could increase perceived value and reduce churn. Customers are less likely to leave if they feel the package is designed specifically for them.

**Promotional Trials:** 

Offering free trials of services like device protection or tech support can showcase the benefits and create habits of use, making customers more reluctant to give them up.


# 2. What is causing them to leave?

## Straight reasons
![image](https://github.com/user-attachments/assets/6bb23a3c-8d30-4b6f-8f3f-ce8b66681910)

Competitor (841): A significant portion of customers are switching to competitors, suggesting they may perceive better value or service elsewhere. This highlights a need for competitive analysis and differentiation strategies.

Churn Reasons Due to Competitors:

• Competitor had better devices:  313 customers.

• Competitor made a better offer: 311 customers.

• Competitor offered more data:   117 customers.

• Competitor offered higher download speeds 100. 

Customers are more likely to switch when they perceive better value in terms of device quality, competitive pricing, and enhanced data and speed offerings. This underlines the importance for telecom providers to continually assess and potentially upgrade their device offerings and data plans to remain competitive and retain customers. So what are we doing wrong?


## TITLE

### Payment process


![PEque;a](https://github.com/user-attachments/assets/849136e4-0033-496f-883c-c49aa70f1540)

![file](https://github.com/user-attachments/assets/97a92709-ddeb-4a61-9a8a-484d005c4cb6)


The data suggests that the Electronic Check payment method is associated with a notably high churn rate of 45.29%, compared to much lower rates for other methods like Credit Card (15.24%) and Bank Transfer (16.71%). 

• This discrepancy indicates a potential problem with the Electronic Check option that could be driving customers away.

Additionally, customers using Paperless Billing also show a higher churn rate of 33.57% compared to those using paper billing (16.34%). 

• This difference raises questions about whether the Electronic Check users might have concerns related to billing preferences or whether there is a broader issue with digital payment experiences.


## Internet Service

![file2](https://github.com/user-attachments/assets/274a993a-e1b9-44d6-a7c8-e030d630959a)


The data reveals that Fiber Optic service users experience a high churn rate of 41.89%, which is significantly higher compared to DSL users (18.96%) and those without internet service (7.40%). This trend suggests potential issues specifically associated with Fiber Optic services that might be causing dissatisfaction among customers.

There are several potential reasons for this disparity:

• Service Expectations: Fiber Optic is often marketed as a high-speed and premium internet service. Customers who subscribe may have higher expectations for performance and reliability. If these are not met, they may be more likely to switch to competitors.

• Pricing: Fiber Optic plans are typically more expensive than DSL, and customers may not perceive the additional cost as justified by the quality. Competitors offering comparable or better plans could entice these customers with more appealing prices.

• Availability of Alternatives: Fiber Optic users might be more tech-savvy or bandwidth-intensive, making them more sensitive to offers from competitors that highlight speed, data, or other performance features. They could also be more willing to switch to get the best available service.

• Fiber Optic Infrastructure: Some areas might experience more technical issues with Fiber Optic connections, leading to frustration and, ultimately, churn.

To address this, it may be beneficial to explore the exact causes of dissatisfaction among Fiber Optic users through customer surveys or feedback channels. Improving reliability, offering competitive pricing, and highlighting unique benefits could help reduce churn in this group.


