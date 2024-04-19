# Customer-Segmentation-Analysis-for-E-Commerce
This project focuses on exploratory data analysis of an e-commerce dataset, including product and order information, to gain insights into the business.

## **Overview**

This project focuses on performing exploratory data analysis (EDA) on an e-commerce dataset, with the goal of gaining insights into the product catalog and customer purchasing behavior.

## **Dataset & Libraries**

**Dataset:**

- The dataset used in this project consists of two main files:
    1. **PRODUCTS.csv**: This file contains information about the products, including product ID, category, dimensions, and weight.
    2. **ORDERS.csv**: This file contains information about the orders, such as order ID, customer ID, order status, and timestamps.

**Libraries:**

- The project utilizes the following Python libraries:
    - Pandas: For data manipulation and analysis
    - Matplotlib and Seaborn: For data visualization

## **Results Summary**

The key findings and insights from the exploratory data analysis include:

1. **Data Inspection and Cleaning**:
    - Identified missing values in the "seller" and "prod" (product) DataFrames, with the highest number of missing values in "seller_zip_code_prefix" and "product_category_name" respectively.
    - Addressed data quality issues by handling the missing values.
2. **Product Data Analysis**:
    - Provided a high-level overview of the product data, including product categories, dimensions, weights, and number of photos.
    - Explored the distribution and characteristics of the product data.
3. **Order Data Analysis**:
    - Examined the order data, including order status, payment information, and delivery timelines.
    - Identified the number of new customers acquired over time by analyzing unique customer IDs.
4. **Recommendations for Future Analysis**:
    - Suggested areas for further investigation, such as exploring buying behaviors, seasonal trends, and customer segmentation based on RFM (Recency, Frequency, Monetary Value) analysis.

## **Features**

The key features of this project include:

1. **Exploratory Data Analysis (EDA)**: The project focuses on understanding the structure and quality of the e-commerce dataset, identifying data quality issues, and providing high-level insights.
2. **Customer Acquisition Analysis**: The project examines the number of new customers acquired over time, which could inform customer acquisition strategies.
3. **Recommendations for Future Analysis**: The project identifies opportunities for further analysis, such as exploring buying behaviors, seasonal trends, and customer segmentation.
