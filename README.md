# Lead-Scoring-Case-Study
A lead scoring model for the company Education X to improve lead conversion rate
# Lead Scoring Model for X Education

## Project Overview
X Education, an online education company, sells courses to industry professionals. The company receives a significant number of leads daily through various online marketing channels like websites and search engines. These leads are potential customers who have shown interest by browsing courses, filling out forms, or watching videos. However, despite the high volume of leads, the company struggles with a low lead conversion rate, typically around 30%.

To enhance efficiency and increase the conversion rate, X Education aims to identify the most promising leads—those with the highest likelihood of converting into paying customers. The goal is to create a model that assigns a lead score to each lead, helping the sales team focus their efforts on the most promising prospects.

## Problem Statement
X Education's current lead conversion rate is suboptimal, with only about 30% of leads converting into customers. The company wants to improve this conversion rate by identifying "Hot Leads," or leads with the highest potential to convert. The CEO has set an ambitious target of achieving a lead conversion rate of around 80%. To accomplish this, the company requires a data-driven solution that scores leads based on their likelihood of conversion.

## Data Description
The dataset provided for this project contains around 9,000 data points from past leads. It includes various attributes such as:

- **Lead Source:** The channel through which the lead was acquired.
- **Total Time Spent on Website:** The amount of time a lead spent on the website.
- **Total Visits:** The number of visits a lead made to the website.
- **Last Activity:** The most recent action taken by the lead.

The target variable is **Converted**, which indicates whether a lead was successfully converted into a customer (1) or not (0). Additionally, the dataset contains categorical variables with levels that need to be handled, such as 'Select,' which is treated as null.

## Project Goals
The main goals of this project are:

1. **Build a Logistic Regression Model:** Develop a logistic regression model that assigns a lead score between 0 and 100 to each lead. A higher score indicates a higher likelihood of conversion.
  
2. **Optimize Lead Conversion Rate:** Adjust the model to achieve the company's target conversion rate of 80%, focusing the sales team's efforts on high-scoring leads.
  
3. **Adapt to Future Requirements:** Ensure the model is flexible and can be adjusted to meet future changes in company strategy or market conditions.

## Business Impact
By implementing this lead scoring model, X Education can significantly improve its lead conversion process. The model will allow the sales team to prioritize high-potential leads, thereby increasing the conversion rate, reducing wasted effort on low-potential leads, and ultimately boosting the company's revenue and efficiency.

This project serves as a foundational analysis that can be further developed into a robust predictive model for lead conversion optimization, offering X Education a competitive edge in the online education market.
