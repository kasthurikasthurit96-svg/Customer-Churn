**Customer Churn Analysis System**

**Project Overview**

Customer churn is one of the most critical challenges faced by modern businesses, especially in sectors such as banking, telecommunications, e-commerce, 
and subscription-based services. Churn refers to the situation where customers stop using a company’s product or service. High churn rates directly 
impact revenue, profitability, and long-term business sustainability.

Organizations collect vast amounts of customer data, including demographic details, financial information, usage behavior, and engagement levels. 
However, analyzing this data manually is inefficient and time-consuming. Moreover, due to privacy concerns and data protection regulations, 
real-world datasets are often not accessible for students and researchers.

To overcome these challenges, this project introduces a **Customer Churn Analysis System using Synthetic Data**. The dataset is generated using the Python Faker library, which simulates realistic customer information without compromising privacy. The project then applies **Exploratory Data Analysis (EDA)** techniques to uncover patterns, trends, and relationships that influence customer churn.


**Objectives**

The primary goal of this project is to analyze customer churn behavior using a synthetic dataset and derive meaningful insights. The specific objectives include:

* Generate a large-scale, realistic synthetic dataset
* Simulate real-world customer behavior scenarios
* Perform data cleaning and preprocessing
* Apply statistical analysis techniques
* Identify patterns and trends influencing churn
* Perform group-based and relationship analysis
* Visualize data using various charts and graphs
* Provide actionable insights for reducing churn


**Dataset Description**

The dataset consists of **100,000 synthetic customer records** generated using Faker. Each record represents a customer with multiple attributes that influence churn behavior.

| **Column Name** | **Description**                         |
| --------------- | --------------------------------------- |
| Customer_ID     | Unique identifier for each customer     |
| Age             | Customer age (18–70 years)              |
| Gender          | Male / Female                           |
| Tenure          | Number of years with the company (0–10) |
| Balance         | Account balance (0–200,000)             |
| CreditScore     | Credit score (300–900)                  |
| EstimatedSalary | Annual income (10,000–150,000)          |
| NumOfProducts   | Number of products used (1–4)           |
| IsActiveMember  | Activity status (0 = No, 1 = Yes)       |
| Churn           | Target variable (0 = No, 1 = Yes)       |


**Technologies Used**

* Python 
* Pandas
* NumPy
* Matplotlib
* Heatmap
* Faker


**Project Workflow**

**1. Data Generation**

* Synthetic data is generated using the Faker library
* Randomized logic is applied to simulate real-world conditions
* Dataset includes realistic distributions for age, balance, salary, etc.

**2. Data Cleaning & Preprocessing**

* Checked for missing or null values
* Verified data types and corrected inconsistencies
* Ensured dataset is clean and ready for analysis

**3. Exploratory Data Analysis (EDA)**

* Calculated statistical measures such as mean, median, and standard deviation
* Analyzed distribution of features
* Identified outliers and anomalies

**4. Churn Behavior Analysis**

* Compared churned and non-churned customers
* Identified high-risk churn segments
* Evaluated impact of multiple features on churn

**5. Group-Based Analysis**

* Age groups vs churn
* Gender vs churn
* Active vs inactive customers
* Product usage vs churn

**6. Relationship Analysis**

* Balance vs churn
* Credit score vs churn
* Tenure vs churn

**7. Data Visualization**

* Bar charts
* Pie charts
* Histograms
* Box plots
* Scatter plots
* Heatmap


**Key Insights**

* Customers with **low account balance** are more likely to churn
* Customers with **low credit scores** show higher churn rates
* **Inactive customers** are at the highest risk of churn
* Customers using **multiple products** tend to stay longer
* Higher engagement and activity significantly reduce churn probability
* Customers with longer tenure are generally more loyal


**How to Run the Project**

**Step 1: Install Required Libraries**

pip install pandas numpy matplotlib seaborn faker


**Step 2: Run the Project**

* Google Colab
* Jupyter Notebook
* VS Code

**Project Structure**

Customer-Churn-Analysis/
│
├── churn_analysis.py
├── customer_churn_data.csv
├── README.md
└── visualizations/


**Future Improvements**

* Machine Learning models (Logistic Regression, Random Forest)
* Predictive churn system
* Dashboard using Power BI / Tableau
* Web deployment using Flask / Django

**Output Overview:**

<img width="862" height="563" alt="Screenshot 2026-03-29 123432" src="https://github.com/user-attachments/assets/82be06da-06e0-4ec6-b937-06b041d32bc4" />

<img width="829" height="558" alt="Screenshot 2026-03-29 123452" src="https://github.com/user-attachments/assets/1ea9c12e-8586-438b-9f0d-78f567413182" />

<img width="829" height="570" alt="Screenshot 2026-03-29 123514" src="https://github.com/user-attachments/assets/d6d6cf26-55bc-4026-9a4b-e56fa27eba70" />

<img width="869" height="575" alt="Screenshot 2026-03-29 123555" src="https://github.com/user-attachments/assets/07544858-6eb0-41cb-9130-df4522558555" />

<img width="897" height="565" alt="Screenshot 2026-03-29 123614" src="https://github.com/user-attachments/assets/8cf05382-ae95-4c9a-a02e-b7f0b28f2c52" />

<img width="1164" height="786" alt="Screenshot 2026-03-29 123937" src="https://github.com/user-attachments/assets/5e7c0045-b2c0-4c75-bb04-5f80f7801776" />

<img width="594" height="521" alt="image" src="https://github.com/user-attachments/assets/4e7c8858-3c27-4890-8f3c-184fa520796e" />



**Conclusion**

This project shows how synthetic data can be used for real-world analysis without privacy risks. It helps understand customer behavior and provides 
insights to reduce churn.



## 🙌 Acknowledgement

This project is created for educational purposes to learn data analysis and churn prediction.

---
