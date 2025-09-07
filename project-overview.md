# Project Overview: Retail Performance Analysis

## Project Context
This project is a job simulation designed to replicate real-world data science challenges, specifically addressing business requirements for senior management. The objective was to analyze a retail dataset to deliver actionable insights for the CEO and CMO, focusing on revenue trends, customer performance, market opportunities, and global demand. The task required careful selection of visualizations to effectively communicate data-driven insights, ensuring alignment with the executives' strategic goals.

### Business Requirements
The project brief emphasized:
- **Understanding Stakeholder Needs**: Identify the CEO’s and CMO’s priorities (e.g., revenue growth, customer retention, market expansion).
- **Effective Visualizations**: Select the most appropriate charts to present data clearly and support decision-making.
- **Actionable Insights**: Provide recommendations that drive business outcomes, such as increasing revenue growth and optimizing customer retention strategies.

## Data Description
The dataset, sourced from [Online Retail Data Set](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fcdn.theforage.com%2Fvinternships%2Fcompanyassets%2FifobHAoMjQs9s6bKS%2F5XsFFJu2oCLdmYJW2%2F1654309626143%2FOnline%2520Retail%2520Data%2520Set.xlsx&wdOrigin=BROWSELINK), contains transactional data for an online retail store. Below is a description of the key columns:

- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Product code for the item sold.
- **Description**: Description of the product.
- **Quantity**: Number of units sold in the transaction.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per unit of the product.
- **CustomerID**: Unique identifier for the customer.
- **Country**: Country where the transaction occurred.

### Derived Column
- **Revenue**: Calculated as `UnitPrice * Quantity` to measure the total revenue per transaction.

This dataset provides the foundation for analyzing revenue growth, customer retention, and market expansion opportunities, aligning with the business metrics outlined in [Business Success Metrics](https://asana.com/resources/success-metrics-examples).