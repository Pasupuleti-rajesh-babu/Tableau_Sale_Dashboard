# Tableau_Sale_Dashboard

## Introduction

This user story outlines the specifications for building two dashboards using Tableau to aid stakeholders in analyzing sales performance and customer data. The dashboards are designed to present an overview of sales metrics and trends for understanding year-over-year sales performance and customer behavior.

## Sales Dashboard Requirements

### Dashboard Purpose

The sales dashboard aims to present an overview of sales metrics and trends to analyze year-over-year sales performance and understand sales trends.

### Key Requirements

1. **KPI Overview:**
    - Display a summary of total sales, profits, and quantity for the current year and the previous year.
2. **Sales Trends:**
    - Present monthly data for each KPI for the current year and the previous year.
    - Identify months with highest and lowest sales and make them easy to recognize.
3. **Product Subcategory Comparison:**
    - Compare sales performance by different product subcategories for the current year and the previous year.
    - Include a comparison of sales with profit.
4. **Weekly Trends for Sales & Profit:**
    - Present weekly sales and profit data for the current year.
    - Display the average weekly values.
    - Highlight weeks that are above and below the average to draw attention to sales & profit performance.

### Sales Dashboard Visualization

![Sales Dashboard](https://github.com/Pasupuleti-rajesh-babu/Tableau_Sale_Dashboard/blob/main/sales.png)

## Customer Dashboard Requirements

### Dashboard Purpose

The customer dashboard aims to provide an overview of customer data, trends, and behaviors to help marketing teams and management understand customer segments and improve customer satisfaction.

### Key Requirements

1. **KPI Overview:**
    - Display a summary of total number of customers, total sales per customer, and total number of orders for the current year and the previous year.
2. **Customer Trends:**
    - Present monthly data for each KPI for the current year and the previous year.
    - Identify months with highest and lowest sales and make them easy to recognize.
3. **Customer Distribution by Number of Orders:**
    - Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior, loyalty, and engagement.
4. **Top 10 Customers By Profit:**
    - Present the top 10 customers who have generated the highest profits for the company.
    - Show additional information like rank, number of orders, current sales, current profit, and the last order date.

### Customer Dashboard Visualization

![Customer Dashboard](https://github.com/Pasupuleti-rajesh-babu/Tableau_Sale_Dashboard/blob/main/customer.png)

## Design & Interactivity Requirements

### Dashboard Dynamic

- The dashboard should allow users to check historical data by offering them the flexibility to select any desired year.
- Provide users with the ability to navigate between the dashboards easily.
- Make the charts and graphs interactive, enabling users to filter data using the charts.

### Data Filters

- Allow users to filter data by product information like category and subcategory and by location information like region, state, and city.

### Filters Example

![Filters](https://github.com/Pasupuleti-rajesh-babu/Tableau_Sale_Dashboard/blob/main/filter.png)

## Usage

To use the Tableau dashboards:

1. Ensure you have Tableau Desktop or Tableau Server installed.
2. Download or clone the repository.
3. Open the Tableau workbook (.twb or .twbx) file in Tableau.
4. Interact with the dashboards using the provided filters and navigation options.

## Contributing

Contributions to enhance the dashboards or address any issues are welcome. Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for commercial or non-commercial purposes.
