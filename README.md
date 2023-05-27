# Data-Driven Pricing Strategy and Simulation Development

## Project Overview

This project aims to optimize the pricing strategy of a sizeable enterprise with approximately 2,000 active customers and a diverse product range of around 40,000 SKUs. The organization's current pricing strategy, although functional, is believed to have room for improvement through the application of data science methodologies. The goal is to develop a personalized, data-driven pricing strategy and create a simulation model to analyze its potential impact on the organization's bottom line.

## Project Goals

- Analyze the existing pricing strategy and identify potential areas for improvement.
- Develop a personalized, data-driven pricing model that differentiates pricing on a product-customer level.
- Create a simulation to analyze the potential impact of this new pricing strategy on the organization's bottom line.
- Present the results of the simulation in a format that's easily understandable by non-data specialists.
- Develop a plan for implementing the new pricing strategy, given that it is validated by the sales team.

## Data

The project utilizes historical ERP data provided by the client, which includes details about product SKUs, customers, and their transaction history. In lieu of client provided data, we will use the following data Source:
https://archive-beta.ics.uci.edu/dataset/352/online+retail

## Instructions

- Analyze the ERP data to understand current pricing patterns and customer buying behavior.
- Develop a personalized pricing model based on the insights derived from the ERP data.
- Create a simulation model using the new pricing strategy to showcase potential outcomes.
- Present the outcomes of the simulation to the sales team for validation.
- If validated, devise a plan to implement the new pricing strategy in sales execution.

## About the placeholder dataset

"This is a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

## Data Dictionary

- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

- Description: Product (item) name. Nominal.

- Quantity: The quantities of each product (item) per transaction. Numeric.

- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.

- UnitPrice: Unit price. Numeric, Product price per unit in sterling.

- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

- Country: Country name. Nominal, the name of the country where each customer resides.

## Project Structure

<pre>
├── README.md
├── data
│ └── online_retail.csv
├── environment.yml
├── main.py
└── notebooks
└── EDA_price_optimization.ipynb
</pre>
