# Food Delivery Cost and Profitability Analysis

This project analyzes the cost and profitability of food delivery services in New Delhi. It involves data exploration, cleaning, and various analyses to understand key metrics and trends.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
- [Results](#results)

## Project Overview
The objective of this project is to analyze the cost and profitability of food delivery services. The analysis covers various aspects such as total revenue, delivery fees, discounts, and commissions to provide insights into the financial performance of the service.

## Dataset
The dataset used in this project is `food_orders_new_delhi (1).csv`, which contains the following columns:
- Order ID
- Customer ID
- Restaurant ID
- Order Date and Time
- Delivery Date and Time
- Order Value
- Delivery Fee
- Payment Method
- Discounts and Offers
- Commission Fee
- Payment Processing Fee
- Refunds/Chargebacks

## Installation
To run the analysis, you need to have Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn

You can install the required libraries using pip:
```
pip install pandas numpy matplotlib seaborn
```
## Usage
1. Clone the repository:
```
git clone https://github.com/JP5402/food_delivery_analysis.git
```
2. Navigate to the project directory:
```
cd cd food_delivery_analysis
```
3. Open the Jupyter Notebook:
```    
jupyter notebook food_delivery_cost_and_profitability_analysis.ipynb
```
Run the cells in the notebook to perform the analysis.

## Analysis
The analysis is divided into the following steps:

1. Data Loading: Loading the dataset into a pandas DataFrame.
2. Data Exploration: Exploring the dataset to understand its structure and contents.
3. Data Cleaning: Handling missing values and preparing the data for analysis.
4. Data Analysis: Calculating key metrics and visualizing data.

## Results
The key results of the analysis include:

- Total revenue generated from orders.
- Total delivery fees collected.
- Impact of discounts and offers on profitability.
- Commission fees and their effect on net profit.
