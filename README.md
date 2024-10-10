# How I analyzed Customer Retention at MarketPro

## What is MarketPro?

MarketPro is a SaaS platform offering a suite of solutions for small and mid-sized businesses to manage operations and optimize customer relationships. With its diverse customer base spanning multiple industries, MarketPro enables businesses to improve customer engagement, reduce churn, and drive business growth.

## This Project

### Project Goals and Motivation

The main objectives of this project were to understand customer retention dynamics at MarketPro

1. **Primary reasons for customer churn**
   
<img width="959" alt="Screenshot 2024-10-10 at 15 59 51" src="https://github.com/user-attachments/assets/dbdebba7-a6f2-41e4-ade7-70dbd8638fe1">

   **Insight**: "Feature Gaps" was the most cited churn reason among Small Business customers, whereas "Price Concerns" dominated for Mid-Market and Enterprise customers. 
   **Actions**:  Addressing feature gaps through product enhancements and reviewing pricing models for Mid-Market segments could help reduce churn.


   
   
                  
2. **Visualisation of Churn rate by country**
   
<img width="957" alt="churn_by_country" src="https://github.com/user-attachments/assets/a772fb6f-aa66-4190-aa6b-f12bcb24622d">

  **Insight**: This visualization highlights the geographical distribution of churn rates, which is crucial for identifying regions with higher customer attrition.


  
  

3. **Influence of Feature adoption on customer satisfaction and retention?**

<img width="957" alt="feature_adoption_vs_CSAT" src="https://github.com/user-attachments/assets/7bfb08aa-0f5b-4e7e-9b03-9863ef74c60f">
   
   **Insight**: Customers with feature adoption rates above 70% had a churn rate of just 5%, significantly lower than the overall churn rate of 18%.
   **Hypothesis**: This suggests that increasing feature adoption and providing better onboarding experiences can have a major impact on retention.


   
                
   

4. **Average featuee adoption over time?**
   
<img width="958" alt="avg_feature_adoption" src="https://github.com/user-attachments/assets/ee6e085d-e905-4627-8cf1-fa65edba9925">

  **Insight**: This graph illustrates the trend of average feature adoption over time, helping identify periods of increased or decreased engagement.


  

  
5. **Monthly Churn rate over time?**
   
<img width="958" alt="churn_over_time" src="https://github.com/user-attachments/assets/2eb884b9-69a7-4727-953e-5e669f3265c4">

  **Insight**: Monthly churn trends are crucial for detecting seasonal patterns or the impact of new feature launches on customer retention.


  


6. **What is the revenue impact of churn, and which segments have the most revenue at risk?**

<img width="956" alt="total_gain_vs_loss" src="https://github.com/user-attachments/assets/6c1bc122-9afb-473e-bdb0-67b93025e990">

   **Insight**: Monthly revenue loss due to churn amounted to $20,000, with a significant impact from the Small Business and Mid-Market segments, highlighting the need for                         targeted retention strategies to minimize revenue loss in these high-risk segments.


   
   


### Key Insights and Recommendations

- **High Churn Segments**: Small Business customers on Basic plans showed the highest churn rate at 35%, indicating potential dissatisfaction or misalignment of value.
- **Revenue at Risk**: Monthly revenue loss due to churn amounted to $20,000, with significant impact from Small Business and Mid-Market segments.
- **Feature Adoption**: Customers who adopted more than 70% of available features had a churn rate of just 5%, suggesting that increasing feature engagement can significantly reduce churn.

> **Note**: The dataset used for this analysis is AI-generated and does not represent real-world customer data. The findings should be validated with business & custoner data before implementing any strategies.



## Project Overview

### Repository Structure

- `data/`: Contains the datasets used for analysis.
- `notebooks/`: Jupyter notebook with the full analysis and visualizations.
- `images/`: Folder containing images of the visualizations used in the project.

## How to Use This Repository

1. **Explore the Jupyter Notebook**: Start by reviewing the [cus_ret_analysis.ipynb] notebook, which contains the full analysis, code, and visualizations.
2. **Check Out the Visualizations**: All visualizations used in the analysis are stored in the `images/` folder for easy access.
3. **Run the Code Locally**: If you'd like to run the code locally, follow the setup instructions below.

## License

This project is licensed under the MIT License. See the [LICENSE] file for details.

## Connect

For more information, feel free to connect with me on:

LinkedIn = [https://www.linkedin.com/in/bartobenda]
Portfolio = [https://www.contra.com/bartobenda]
