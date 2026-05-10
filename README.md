# Sales Customer Analytics Dashboard

This project presents an interactive **Sales and Customer Analytics Dashboard** developed using Tableau to help stakeholders analyze business performance, customer behavior, and sales trends.

The dashboard enables users to compare any two selected years dynamically, allowing all KPIs, charts, and dashboard text to automatically update based on the selected years.

The project is designed as a portfolio project showcasing:

* Business intelligence dashboard development
* Sales and customer analytics
* Interactive KPI reporting
* Data visualization and dashboard storytelling
* Dashboard interactivity and navigation design

---

## Project Objectives

The project was developed to help stakeholders monitor sales performance, analyze customer behavior, and evaluate historical business trends through interactive reporting and dashboard visualizations.

The dashboards enable users to compare business performance between any two selected years, helping identify sales patterns, customer purchasing behavior, profitability trends, and regional performance variations.

The project also focuses on improving analytical usability through dashboard-wide interactivity, dynamic filtering, and cross-dashboard navigation, enabling users to explore business insights more efficiently.

---

## Dashboard Overview   

The project contains two primary dashboards:

### Sales Dashboard

![Sales Dashboard](images/sales_dashboard_overview.png)

The Sales Dashboard provides an overview of sales performance and year-over-year business trends. 

It enables users to monitor key metrics such as total sales, profit, and order quantity while analyzing monthly and weekly performance patterns.

Users can compare sales metrics between any two selected years, identify high and low-performing periods, and evaluate product subcategory performance across different regions and locations.

### Customer Dashboard

![Customer Dashboard](images/customer_dashboard_overview.png)

The Customer Dashboard focuses on customer behavior, engagement, and profitability analysis. 

It provides insights into customer purchasing patterns, order distribution, and top-performing customers.

The dashboard helps stakeholders understand customer trends over time, evaluate customer contribution to profitability, and analyze customer activity across multiple dimensions using interactive filters.

---

## Dashboard Features

### Interactive Features

- Dynamic comparison between any two selected years with dashboard-wide automatic updates across all KPIs, charts, and dashboard text
- All visualizations and KPIs dynamically update based on the selected filters
- Cross-filtering between dashboard visualizations
- Interactive chart selections that update the entire dashboard
- Dashboard-wide filtering based on user interaction

#### Comparison Year Example 1
![Year Comparison 1](images/year_comparison_2022_2021.png)
year 2022-2021

#### Comparison Year Example 2
![Year Comparison 2](images/year_comparison_2021_2020.png)
year 2021-2020


### Navigation & Controls

- Navigation buttons for switching between dashboards
- Toggle buttons for showing and hiding filters
- Export buttons for downloading dashboards as PDF or image files
- Custom icons used for dashboard controls and navigation

### Filters

The dashboards support dynamic filtering, allowing users to analyze sales and customer performance across different product categories and geographic locations. 

- Category
- Subcategory
- Region
- State
- City

#### Before Filter Selection
![Before Filter](images/dashboard_before_filter.png) 
year: 2023, 2022
category: all
sub-category: all
region: all
state: all
city: all


#### After Filter Selection
![After Filter](images/dashboard_after_filter.png)
year: 2022, 2021
category: Furniture, Office supplies
sub-category: all
region: Central, East
state: all
city: all

---

## Repository Structure

```
sales-customer-analytics-dashboard/
│
├── datasets/                          # Source datasets used for dashboard development
│   ├── Customers.csv
│   ├── Location.csv
│   ├── Orders.csv
│   └── Products.csv
│
├── images/                            # Dashboard screenshots, icons, and logos used in the project
│
├── Sales Customer Dashboard.twbx      # Tableau packaged workbook containing dashboards and visualizations
│
├── README.md                         	# Project overview and instructions
├── LICENSE                             # License information for the repository
└── .gitignore                          # Files and directories to be ignored by Git
```
---

## [Tableau Public Dashboard](https://public.tableau.com/views/SalesCustomerDashboard_17782340995890/SalesDashboard)

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---
