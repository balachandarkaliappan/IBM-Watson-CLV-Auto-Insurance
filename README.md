## IBM Watson - Auto Insurance Claims and Influencing Factors

### Project Overview

In this project, I examine the IBM Watson auto insurance dataset that comprises of 25 columns that describes the characteristics of the customers and their claim behavior. 
Customer Lifetime Value, Total Claims, Monthly Premium, and demographics characteristics of the customers are included for the data analysis. The study aimed at examining the factors 
that drives the total claim and also creating customers segments with the dataset. 

#### Tableau Story Board: Presentation

### Objectives

Identify the factors that drives the total claim of the consumers. 
Identify customer segments to provide solutions to personalize marketing communications and products. 

### Key Questions:

1. Examine the relationship between total claim and monthly premium paid by the customers.
2. Does marital status of the customers impacts the total insurance claims.
3. What are the customers segments that are present based on the past customer data.

### Data Overview:

The data for the project is sourced from Kaggle (an open source data provider). The dataset contains the following columns

`customer_id` - ID of the customer

`state` - State the customer resides

`customer_lifetime_value` - Customer Lifetime Value in USD

`response` - Response provided by the customer for the marketing message (Yes/No)

`coverage` - Insurance coverage type (Basic, Premium, Extended)

`education` - Education level of the customer

`effective_to_date` - Date in which the customer bought the insurance

`employment_status` - Employment status of the customer

`gender` - Gender

`income` - Income of the customer in USD

`region` - Region of the customer (Rural/ Suburban/ Urban)

`marital_status` - Marital Status of the customer

`monthly_premium` - Monthly premium paid by the customer in USD

`months_since_last_claim` - No of months since the last claim was made by the customer

`months_since_policy_inception` - No of months since the policy was purchased

`no_of_open_complaints` - No of open complaints

`no_of_policies` - No of policies bought by the customer

`policy_type` - Type of auto policy (Personal Auto/ Corporate Auto)

`policy` - Type of auto policy (Corporate / Personal / Special - L1, L2, L3 across all levels)

`renew_offer_type` - Type of offer used to renew the auto insurance

`sales_channel` - Sales channel used to reach the customer

`total_claim` - Total amount of auto insurance claim made by the customer in USD

`vehicle_class` - Type of Vehicle Class

`vehicle_size` - Size of the vehicle

There are 9135 observations in the dataset. There are no duplicates or missing values. However, there were mixed data types present - check Exercise 6.1 Sourcing Open Data type for more information.

**Data Source**: [Kaggle - IBM Watson](https://www.kaggle.com/datasets/pankajjsh06/ibm-watson-marketing-customer-value-data)

## Tools used:

**Python**: Data analysis and statistical modeling | Package used: pandas, Numpy, seaborn, matplotlib, scikitlearn
**Jupyter Notebook**: Documentation and coding
**Github**: Version control and documentation
**Tableau Public**: Data visualization and dashboards

## Analytical steps:

1. **Data preparation and cleaning**: Identifying missing values, duplicates, and outliers
2. **Exploratory data analysis**: Distribution of total claims, vehicle types, region, marital status and its impact on claims
3. **Regression analysis**: How does monthly premium impact the total claim by the consumers
4. **Cluster analysis**: k-means clustering to identify potential customer segments
5. **Geospatial analysis**: Examining how average customer lifetime value and total claim is distributed among the states of the US
6. **Results and recommendations**: Provided recommendations based on the analysis conducted - check Tableau storyboard

## 
