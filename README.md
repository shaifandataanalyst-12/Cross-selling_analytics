# Insurance Cross-Selling Strategy Analysis
## Project Overview

This project analyzes customer data from an insurance company to identify opportunities for cross-selling additional insurance products to existing customers. The objective is to understand customer behavior, evaluate current product coverage, and determine which customers are most likely to adopt additional insurance services.

The analysis combines business understanding, data engineering, exploratory data analysis (EDA), and predictive modeling considerations to support data-driven marketing strategies.

## Business Problem

Insurance companies aim to increase revenue by selling additional products to their existing customers. Cross-selling helps improve:

- Customer lifetime value (CLV)

- Customer retention

- Revenue per customer

- Long-term customer relationships

Instead of acquiring new customers, the strategy focuses on identifying existing customers who are likely to purchase additional insurance products. 

## Business Understanding

The project analyzes three possible scenarios when offering new insurance products to existing customers:
### Case 1 — New Coverage Greater Than Current Coverage
Customers already having insurance are offered an additional policy that increases their total coverage.
### Case 2 — New Coverage Equal To Current Coverage
Customers whose insurance policy has expired are offered a new product with similar coverage.
### Case 3 — New Coverage Less Than Current Coverage
Customers whose previous policy expired receive a smaller coverage policy. 

These strategies help insurance companies determine which customers are most suitable for cross-selling campaigns.

## Tools used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook

## Dataset Description

The dataset contains customer demographic, behavioral, and insurance product information.

Key variables include:

Age,
Gender,
Marital Status,
Family Members,
Education,
Occupation,
Job Title,
Income,
Current Product,
Current Product Type,
Current Coverage,
New Product Type,
New Coverage,
Converted (Target Variable)

The Converted variable indicates whether a customer purchased the cross-sell product.

## Data Engineering & Preprocessing

A structured data engineering strategy was applied to handle missing values and prepare the dataset for analysis.

Examples include:

- Missing Age values replaced using mean/median comparison

- Family members filled using median values

- Education, occupation, and job title replaced using mode

- Income imputed using occupation-level statistics

- Product and coverage fields derived using reference variables

- Target variable Converted handled using predictive modeling rather than simple imputation 

- Data Engineering Strategy

This ensured the dataset was reliable before performing analysis.

## Exploratory Data Analysis (EDA)

EDA was performed to understand customer demographics and purchasing behavior.

Key analysis areas included:

- Customer demographic distribution

- Income vs product coverage patterns

- Current insurance product adoption

- Customer rating analysis

- Cross-selling conversion patterns

- Coverage amount comparison

Visualization libraries such as Seaborn and Matplotlib were used to identify trends and correlations.

## Key Insights

### Customer Demographics
Certain demographic groups showed higher probability of purchasing additional insurance products.

### Coverage Patterns
Customers with existing insurance coverage were more likely to consider additional policies.

### Income Influence
Higher-income customers tended to opt for higher coverage products.

### Product Type Trends
Certain product types showed stronger cross-selling potential compared to others.

### Customer Rating Impact
Customers with better satisfaction ratings were more likely to convert.

## Business Impact

The analysis helps insurance companies:

- Identify customers with high cross-selling potential

- Improve targeted marketing campaigns

- Increase customer lifetime value

- Strengthen long-term customer relationships

- Optimize product recommendation strategies

## Screenshots from ppt
<img width="500" height="500" alt="Screenshot 2026-03-10 174454" src="https://github.com/user-attachments/assets/2ce8332e-92a5-42c5-9b55-d705f335f54b" />
<img width="500" height="500" alt="Screenshot 2026-03-10 174443" src="https://github.com/user-attachments/assets/e60ce5b2-53e8-44ab-a87d-22de7e5e97c6" />
<img width="500" height="500" alt="Screenshot 2026-03-10 174427" src="https://github.com/user-attachments/assets/232a76d5-fcbb-4c78-99dd-2d59e419c10a" />
<img width="500" height="500" alt="Screenshot 2026-03-10 174416" src="https://github.com/user-attachments/assets/45e41852-f639-4acb-8748-f7448f4d83e9" />
<img width="500" height="500" alt="Screenshot 2026-03-10 174409" src="https://github.com/user-attachments/assets/f37f7962-2374-489b-9b34-63cba95bcebe" />
<img width="500" height="500" alt="Screenshot 2026-03-10 174505" src="https://github.com/user-attachments/assets/5f70d9d9-d5a6-4b7f-81ca-fdc24206ff80" />
