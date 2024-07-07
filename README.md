# BCG-Data-Science-job-simulation

Estelle and I have discussed the issue PowerCo is facing regarding customer retention and have formulated our approach using the 5-step Data Science methodology. Here is our outline:

## 1. Business Understanding & Problem FramingProblem Statement: 

PowerCo is experiencing a significant churn rate among its customers. We need to identify the key factors influencing customer decisions to switch to other energy providers and provide actionable insights to reduce churn.

## 2. Data Requirements 

To investigate this issue comprehensively, we will need the following data from PowerCo:

Customer Demographics:Age, gender, income, household size, etc.
Customer Behavior:Energy consumption patterns (monthly usage for the past 5 years).Customer service interactions (frequency, type of issues, resolution times).Payment history (on-time payments, defaults).
Contract Details:Contract type (fixed vs. variable rates), duration, renewal dates.Pricing information (rates, discounts, promotions).
Customer Feedback:Survey results, reviews, and ratings of service quality.External Factors:Competitor pricing and offerings.Economic indicators (employment rates, inflation).

## 3. Analysis Techniques

Exploratory Data Analysis (EDA):Use Python libraries (Pandas, Matplotlib, Seaborn) to identify patterns and correlations in the data.Visualize energy consumption trends, payment histories, and customer demographics.
Statistical Analysis:Perform hypothesis testing to determine the significance of identified factors.Use regression analysis to quantify the impact of each factor on customer churn.
Machine Learning Models:Apply classification algorithms (Logistic Regression, Random Forest, XGBoost) to predict customer churn.Use clustering techniques to segment customers based on behavior and demographics.
Customer Sentiment Analysis:Analyze customer feedback using Natural Language Processing (NLP) techniques to understand sentiments and key concerns.

## 4. Key Reasons for Customer Decisions

We hypothesize that the following factors are crucial in a customer’s decision to stay with or switch energy providers:

Price: Competitive pricing and cost-saving plans.Service Quality: Prompt and effective customer service.
Energy Source: Preference for clean and renewable energy options.
Location: Availability and reliability of service in specific areas.Contract Flexibility: Flexible contract terms and renewal options.

## 5. Data Analysis and Visualization 

Data Analysis:Calculate churn rates across different customer segments.Identify trends and patterns in energy consumption and payment behavior.Correlate customer service interactions with churn rates.
Data Visualization:Use Power BI to create dashboards showing key metrics and trends.Visualize customer segments and churn predictors using scatter plots, bar charts, and heatmaps.Create geographical maps to analyze churn rates by location.

## Conclusion 

By obtaining and analyzing the above data, we aim to uncover the underlying reasons for PowerCo’s customer churn and provide strategic recommendations to improve retention. We will follow up with a detailed project plan and timeline once we have access to the data.Please let us know if you need any further information or if there are additional aspects we should consider.


### What is price sensitivity?
Price sensitivity is the degree to which demand changes when the cost of a product or service changes.

In the context of PowerCo, the “demand” refers to the demand for energy consumption.

Price sensitivity is commonly measured using the price elasticity of demand, which states that some consumers won't pay more if a lower-priced option is available.


### What is price elasticity of demand?

Price elasticity of demand is a measurement of the change in consumption of a product in relation to a change in its price

Complete the quick knowledge check and move onto your exploratory data analysis.

### What is exploratory data analysis?

Exploratory data analysis (EDA) is a technique used by a Data Scientist to gain a holistic understanding of the data that they are working with.

It is mainly based around using statistical techniques (such as descriptive statistics) and visualizations to gain a deeper understanding of the statistical properties that the data holds.

Complete the quick knowledge check on the next step and let’s get started.

## The client has sent over 3 data sets (shown below):

#### Historical customer data: Customer data such as usage, sign up date, forecasted usage etc
#### Historical pricing data: variable and fixed pricing data etc
#### Churn indicator: whether each customer has churned or not

I need to analyze the following using Python:

The data types of each column
Descriptive statistics of the dataset
Distributions of columns

Estelle has provided a starter Jupyter notebook has been provided for you to use as a template to complete your work. 


