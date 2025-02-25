# Bank Customer Insights Dashboard  

<img width="1397" alt="Screenshot 2025-02-25 at 00 06 53" src="https://github.com/user-attachments/assets/4b900ef9-0e1f-43d8-a931-5fee97b0640c" />

## Overview  
This Tableau dashboard provides insights into bank customer demographics, credit behavior, and financial patterns. By analyzing key attributes such as age, credit score, and credit limit, this dashboard helps identify trends and patterns useful for decision-making.  

## Data Source  
The dataset used for this project was obtained from **[Kaggle](https://www.kaggle.com/)**, which contains anonymized information on bank customers, including age, credit score, income, and account status.  

## Data Cleaning & Preparation  
Before visualizing the data in Tableau, I performed the following preprocessing steps using Excel:  

- **Formatted Data Types**: Ensured numerical values (e.g., credit score, income, and balances) were assigned the correct data format.  
- **Created Bins for Categorization**: Used the `IFS` function to group:  
  - **Age Ranges** (e.g., Young Adults, Middle-Aged, Seniors)  
  - **Credit Score Categories** (e.g., Poor, Fair, Good, Excellent)  
  - **Credit Limit Segments** (e.g., Low, Medium, High)  
- **Removed Inconsistencies**: Addressed missing values, duplicate records, and formatting errors to ensure data accuracy.  

**Before**
<img width="985" alt="Screenshot 2025-02-24 at 21 25 09" src="https://github.com/user-attachments/assets/92264b25-4cbc-475b-be74-620f419b866f" />

**After**
![Screenshot 2025-02-25 at 00 29 49](https://github.com/user-attachments/assets/84f6267d-4bc2-49e6-b5b1-6bfd51e4dd81)

## Dashboard Highlights  
The dashboard provides insights into:  

- **Customer Age Distribution** – Identifies key demographics of the bank's customers.  
- **Credit Score Segmentation** – Categorizes customers based on their creditworthiness.  
- **Credit Limit Analysis** – Highlights the distribution of credit limits across different customer segments.  
- **Income & Account Status Trends** – Examines how financial factors influence account types and banking behavior.  

### Dashboard Preview  

**View the full interactive dashboard here:** [Bank Customer Dashboard](https://public.tableau.com/app/profile/bunmi.oni8158/viz/BankCustomerInfo_17404419835650/Dashboard1?publish=yes)  

## Key Recommendations for Stakeholders  
Based on the insights from the dashboard, the following recommendations can help improve customer engagement and risk management:  

1. **Targeted Financial Products**: Develop tailored financial products for different age groups based on spending behavior and credit scores.  
2. **Credit Risk Mitigation**: Implement stricter credit policies for high-risk customers while offering incentives to those with strong credit histories.  
3. **Customer Retention Strategies**: Identify customers with declining credit scores or low account activity and offer financial planning support or loyalty rewards.  
4. **Optimized Credit Limits**: Adjust credit limits dynamically based on customer income, spending habits, and repayment behavior to reduce default risks.  
5. **Enhanced Customer Segmentation**: Use data-driven insights to create personalized marketing strategies and improve customer experience.  

## Future Enhancements  
- Expand the dataset with more financial attributes for deeper insights.  
- Integrate predictive analysis to forecast customer credit behavior.  
- Enhance interactivity by adding filtering options for deeper drill-down analysis.  

Let me know if you need any modifications or additional details.










