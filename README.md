# Telecom Customer Churn Analysis & Prediction

This project delivers a complete business intelligence and machine learning solution for a telecom firm to combat customer churn. It follows a full end-to-end data science lifecycle, from data preparation and exploratory analysis to building a predictive model and providing actionable business insights.

The ultimate goal is to identify customers at high risk of churning and recommend targeted retention strategies to business stakeholders.

---

## Project Methodology

The solution was developed using a four-step process:

### Step 1: Data Preparation (SQL Server)
The raw customer data was ingested, cleaned, and structured using **Microsoft SQL Server**. This widely-used database system was chosen for its ability to handle large, recurring data loads and ensure data integrity. Key data cleaning and transformation steps included:
* Ingesting the raw data from a source file into a SQL Server production table.
* Handling missing values and ensuring consistent data types.
* Structuring the data for efficient analysis and modeling.

### Step 2: Exploratory Data Analysis (Power BI)
**Power BI** was connected to the cleaned data in the SQL Server database to perform an in-depth exploratory data analysis (EDA). A summary dashboard was created to visualize key metrics and trends related to churn, providing stakeholders with a clear overview of the customer base. This phase uncovered crucial insights that informed the machine learning model.

### Step 3: Machine Learning Model (Python - Jupyter Notebook)
A predictive model was built in Python using a **Jupyter Notebook**. The core of this step involved:
* Connecting to the SQL Server database to extract the cleaned data.
* Training a **Random Forest Classifier**, a robust machine learning algorithm, to predict customer churn.
* Evaluating the model's performance using key metrics to ensure its accuracy and reliability.

### Step 4: Final Visualization (Power BI)
The final, and most crucial, step was to translate the model's predictions into actionable business insights. The predicted churn data was loaded back into a new table, which was then used to create a **"Churn Prediction Summary"** report in Power BI. This report profiles potential churners, allowing the business to visualize and target high-risk customer segments.

---

## Key Results & Business Insights

The analysis and predictive model identified several critical patterns and areas for targeted intervention:

* **Age and Churn**: Customers **over 50** represent the largest segment of churners, with 2,838 customers in this age group leaving the company. This group accounts for 44.22% of the total customer base, indicating a significant retention opportunity.
* **Customer Loyalty**: Customers with a **tenure of over two years** show a strong loyalty trend. While this group is large (2,087 customers), their churn rate is very low, suggesting that long-term relationships are highly stable.
* **Gender and Churn**: A notable difference was observed between genders, with female customers having a **higher churn count** (1,111) compared to male customers (621).
* **Tenure Consistency**: The churn rate remains consistently within a narrow range (**26.1% to 27.5%**) across all tenure groups, highlighting that while the number of churners changes, the underlying churn rate is stable.

---

## Novelty & Conclusion: Actionable Recommendations

This project goes beyond simple analysis by providing specific, data-driven recommendations that the business can implement immediately to reduce churn.

1.  **Launch Targeted Retention Campaigns for Customers Over 50**: Since this age group has the highest churn rate despite being a large portion of the customer base, the firm should offer personalized plans such as senior discounts, simplified service bundles, or dedicated support lines to address their specific needs.

2.  **Strengthen Onboarding and Early Engagement**: The model suggests that building a strong connection in the **first 6–24 months** is key to long-term retention. The firm should focus on proactive support, loyalty rewards, and regular check-ins during this critical period.

3.  **Address Gender-Specific Preferences and Concerns**: Given the higher churn count among female customers, the firm should conduct surveys or focus groups to understand their pain points. Adapting marketing messages, service accessibility, or support options can better align with their expectations.

4.  **Refine Tenure-Based Marketing with Behavioral Triggers**: By leveraging the predictive model, the firm can implement a system to monitor customer behavior (e.g., usage patterns, complaints, or payment delays) and trigger personalized retention offers *before* customers show strong signs of leaving.

This project transforms raw data into a powerful tool for strategic decision-making, enabling the telecom firm to move from reactive problem-solving to proactive customer retention.
