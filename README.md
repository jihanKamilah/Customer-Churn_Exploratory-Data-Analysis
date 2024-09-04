# Customer Churn Exploratory Data Analysis

## Introduction
<p align="justify"> In the highly competitive telecommunications industry, understanding customer behavior, particularly customer churn — when customers discontinue their service with a provider — is critical for maintaining profitability and customer satisfaction. Retaining customers is just as crucial as acquiring new ones, and churn poses a significant challenge to businesses. By applying exploratory data analysis (EDA) to churn data, companies can uncover patterns and trends that offer valuable insights, enabling them to implement strategies that enhance customer retention and reduce losses.
</p>

## Objectives
- <p align="justify"> Identify significant factors contributing to customer churn.</p>
- <p align="justify"> Explore and visualize key patterns and trends in the dataset.</p>
- <p align="justify"> Gain insights into customer behavior to inform retention strategies.</p>

## Dataset
<p align="justify"> The dataset used is about customer churn and is sourced from the <a href="https://www.kaggle.com/c/customer-churn-prediction-2020/overview">Kaggle</a> which consists of 4250 data with 20 columns. Below are the attributes or column names contained in this dataset:

| No. | Column | Description |
|---|---|---|
| 1 | state | 2-letter code of the US state of customer residence |
| 2 | account_length | Number of months the customer has been with the current telco provider |
| 3 | area_code | Customer's telephone area code |
| 4 | international_plan | The customer has international plan |
| 5 | voice_mail_plan | The customer has voice mail plan |
| 6 | number_vmail_messages | Number of voice-mail messages |
| 7 | total_day_minutes | Total minutes of day calls |
| 8 | total_day_calls | Total number of day calls |
| 9 | total_day_charge | Total charge of day calls |
| 10 | total_eve_minutes | Total minutes of evening calls |
| 11 | total_eve_calls | Total number of evening calls |
| 12 | total_eve_charge | Total charge of evening calls |
| 13 | total_night_minutes | Total minutes of night calls |
| 14 | total_night_calls | Total number of night calls |
| 15 | total_night_charge | Total charge of night calls |
| 16 | total_intl_minutes | Total minutes of international calls |
| 17 | total_intl_calls | Total number of international calls |
| 18 | total_intl_charge | Total charge of international calls |
| 19 | number_customer_service_calls | Number of calls to customer service |
| 20 | churn | Customer churn — target variable |

## Research Questions
- <p align="justify"> How is the data distribution of the customers who churn and those who don’t?</p>
- <p align="justify"> How do numerical and categorical features impact churn?</p>
- <p align="justify"> How is the correlation between numerical features?</p>
- <p align="justify"> Which states have the highest churn cases?</p>
- <p align="justify"> How is the correlation between features and churn?</p>

## Exploratory Data Analysis
<p align="justify"> The analysis has been briefly explained through the program code listed (.ipynb), but I made an article that explains in detail on the <a href="https://medium.com/@jihankamilah/eda-exploratory-data-analysis-customer-churn-datase-eaf0357581ab">Medium</a> platform.</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/b377942a-2587-4e8e-a801-172aa9d428fe" width="75%"/>
</p>

<p align="justify"> Don't forget to check it out and let me know any improvement suggestions if you find any errors in it!</p>

## Conclusion
- <p align="justify"> 14.1% of customers (598 customers) have churned, indicating a moderate churn rate that warrants attention even though the proportion of customers who continue to use the service is higher.</p>
- <p align="justify"> States like New Jersey (NJ) have the highest churn rates, suggesting potential regional issues affecting customer retention.</p>
- <p align="justify"> Customers with an international plan are more likely to churn, making it a significant factor in customer dissatisfaction.</p>
- <p align="justify"> Customers without a voice mail plan show higher churn rates, highlighting the potential value of this service in retaining customers.</p>
- <p align="justify"> High total day minutes correlate positively with churn, suggesting that customers with higher usage may be experiencing unmet needs or issues.</p>
- <p align="justify"> Longer-term customers are less likely to churn, emphasizing the importance of building and maintaining long-term relationships for better retention.</p>

## Recommendation
- <p align="justify"> Target High Churn Regions: Focus on areas like New Jersey with high churn rates by implementing targeted marketing strategies, personalized offers, or special loyalty programs to strengthen customer relationships in these regions.</p>
- <p align="justify"> Enhance International Plan Services: Customers with international plans show a higher likelihood of churn. To counteract this, improve the quality of these services and consider offering incentives like discounts or trial periods to increase satisfaction and reduce churn.</p>
- <p align="justify"> Promote Voice Mail Plans: Customers without voice mail plans are more prone to churn. Increase the promotion of these plans, possibly through bundling with other popular services or offering free trials to encourage adoption and reduce churn.</p>
- <p align="justify"> Address Needs of Heavy Users: The positive correlation between high total day call minutes and churn suggests that heavy users might face unmet needs or service quality issues. Engage with these customers to gather feedback and offer tailored solutions, such as addressing call quality concerns or providing cost-effective plans, to prevent churn.</p>
- <p align="justify"> Strengthen Long-Term Relationships: Develop loyalty programs and maintain regular communication with long-term customers to keep them engaged. These efforts can help in building stronger relationships and reducing the likelihood of churn among this valuable customer segment.</p>
