# Telecom Customer Churn Analysis & Prediction

This project delivers a complete business intelligence and machine learning solution for a telecom firm to combat customer churn. It follows a full end-to-end data science lifecycle, from data preparation and exploratory analysis to building a predictive model and providing actionable business insights.

The ultimate goal is to identify customers at high risk of churning and recommend targeted retention strategies.

* Total Number of Customer Records : 6418


---

## Project Methodology

The solution was developed using a four-step process:

Workflow:
*	It starts with ETL (Extract,Transform,Load) and data cleaning in MS SQL Server to prepare the data.
*	PowerBI is then used for data visualization and exploration , revealing key trends and summary of all insights. ("Churn Analysis - Summary" - Screenshot attached below)
*	Prediction section : The core of the project is building a Random Forest Machine Learning model in Python to predict churn.
*	Finally , the predicted data is visualized back in PowerBI creating a dashboard that profiles potential churners for actionable insights. ("Churn Analysis - Prediction" screenshot attached below)


---

## Key Results & Business Insights

The analysis and predictive model identified several critical patterns and areas for targeted intervention:

* **Age and Churn**: Customers **over 50** represent the largest segment of churners, with 2,838 customers in this age group leaving the company. This group accounts for 44.22% of the total customer base, indicating a significant retention opportunity.
* **Customer Loyalty**: Customers with a **tenure of over two years** show a strong loyalty trend. While this group is large (2,087 customers), their churn rate is very low, suggesting that long-term relationships are highly stable.
* **Gender and Churn**: A notable difference was observed between genders, with female customers having a **higher churn count** (1,111) compared to male customers (621).
* **Tenure Consistency**: The churn rate remains consistently within a narrow range (**26.1% to 27.5%**) across all tenure groups, highlighting that while the number of churners changes, the underlying churn rate is stable.

---

## Novelty & Conclusion: Actionable Recommendations

1.  **Launch Targeted Retention Campaigns for Customers Over 50**: Since this age group has the highest churn rate despite being a large portion of the customer base, the firm should offer personalized plans such as senior discounts, simplified service bundles, or dedicated support lines to address their specific needs.

2.  **Strengthen Onboarding and Early Engagement**: The model suggests that building a strong connection in the **first 6–24 months** is key to long-term retention. The firm should focus on proactive support, loyalty rewards, and regular check-ins during this critical period.

3.  **Address Gender-Specific Preferences and Concerns**: Given the higher churn count among female customers, the firm should conduct surveys or focus groups to understand their pain points. Adapting marketing messages, service accessibility, or support options can better align with their expectations.

4.  **Refine Tenure-Based Marketing with Behavioral Triggers**: By leveraging the predictive model, the firm can implement a system to monitor customer behavior (e.g., usage patterns, complaints, or payment delays) and trigger personalized retention offers *before* customers show strong signs of leaving.


## Screenshots



![Summary Report](https://github.com/Fatema-016/Customer-Churn-Analysis-and-Prediction-using-Machine-Learning/blob/7de15927fa36544bf830c3f3328f95e6a69e3eda/images/Churn%20Analysis%20-%20Summary%20Report%20Screenshot.png)
![Prediction Report](https://github.com/Fatema-016/Customer-Churn-Analysis-and-Prediction-using-Machine-Learning/blob/7de15927fa36544bf830c3f3328f95e6a69e3eda/images/Churn%20Analysis%20-%20Prediction%20Report%20Screenshot.png)

Author : Fatema Habil Saifuddin
fatemahab.786@gmail.com
Any project related Suggestions would be highly appreciated! :)



