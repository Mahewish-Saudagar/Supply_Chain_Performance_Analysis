# Supply Chain Performance Analysis

## Overview

This project focuses on analyzing supply chain data to understand product performance, supplier contributions, revenue, costs, transportation, and quality-related metrics.

I started by cleaning and preparing the dataset using Python, followed by SQL analysis in PostgreSQL. I then created interactive dashboards in Power BI and Tableau to explore the data and present the key findings in a visual and understandable way.

The goal was to turn raw data into meaningful insights and identify potential areas for improving supply chain performance.

## Tools & Technologies

- **Python** for data cleaning and preprocessing
- **Pandas** for data manipulation
- **Jupyter Notebook** for Python-based analysis
- **PostgreSQL** for database management and SQL queries
- **Power BI** for interactive dashboards
- **Tableau Public** for data visualization
- **Git & GitHub** for version control and project documentation

## Project Workflow

1. **Data Cleaning:** Checked for missing values, duplicate records, and potential outliers, and prepared the dataset for analysis.
2. **Database Management:** Loaded the cleaned data into PostgreSQL.
3. **SQL Analysis:** Used SQL queries to explore revenue, sales, supplier performance, manufacturing costs, transportation costs, and quality metrics.
4. **Dashboard Development:** Created interactive dashboards using Power BI and Tableau.
5. **Insights:** Summarized key findings and identified potential areas for improvement.

## Power BI Dashboard

The Power BI dashboard provides an interactive overview of supply chain performance through KPIs, charts, and filters. It helps explore revenue, costs, supplier contributions, product performance, transportation modes, and quality metrics.

![Power BI Dashboard](<Dashboard%20Images/PowerBI/Dashboard.png>)

## Tableau Dashboard

I also developed a Tableau dashboard to explore the same dataset through a different visualization approach. It presents key metrics and comparisons related to suppliers, product types, manufacturing costs, inspection results, defect-rate metrics, and transportation costs.

![Tableau Dashboard](<Dashboard%20Images/Tableau/Dashboard.png>)

### Note on Tableau Public

I used Tableau Public rather than Tableau Desktop. In my setup, I couldn't connect directly to PostgreSQL using the available connection options. To continue with the visualization, I exported the cleaned dataset from Python as a CSV file and used it as the data source in Tableau.

This allowed me to build the Tableau dashboard using the same cleaned dataset as the rest of the project, even though the data connection methods were different.

## 💡 Key Insights

- **Product Performance:** Skincare generated the highest revenue among the product types.
- **Supplier Performance:** Supplier 1 contributed the highest revenue among the suppliers.
- **Transportation Costs:** Road transportation had the highest total cost, while Sea transportation had the lowest.
- **Quality Control:** A considerable proportion of inspection results were marked as Pending or Fail, highlighting an area for further investigation.
- **Manufacturing and Defects:** Manufacturing costs and defect-rate metrics varied across product types, suggesting opportunities to investigate production efficiency and quality control.

These findings highlight patterns in the available dataset and can support further investigation into supply chain performance.

## 📁 Project Structure

```text
Supply_chain_performance_analysis/
│
├── Dashboard Images/
│   ├── PowerBI/
│   │   ├── Dashboard.png
│   │   ├── Dashboard_with_multiple_filters_applied.png
│   │   └── Dashboard_with_one_filter_applied.png
│   │
│   └── Tableau/
│       ├── Dashboard.png
│       ├── Dashboard_with_multiple_filters_applied.png
│       └── Dashboard_with_one_filter_applied.png
│
├── Dashboard/
│   ├── Dashboard(PowerBI).pbix
│   └── Dashboard(Tableau).twbx
│
├── Datasets/
│   ├── supply_chain_cleaned.csv
│   └── supply_chain_data.csv
│
├── Data_Analysis_Using_SQL.sql
├── Data_Cleaning.ipynb
├── Insights.pdf
├── .gitignore
└── README.md
```

## 📚 What I Learned

- Cleaning and preparing data using Python and Pandas
- Writing SQL queries to answer business-related questions
- Storing and querying data using PostgreSQL
- Creating interactive dashboards in Power BI and Tableau
- Choosing appropriate aggregations and visualizations for different metrics
- Presenting data-driven findings in a clear and meaningful way

## 🎯 Conclusion

This project gave me practical experience with the complete data analysis workflow, from data cleaning and SQL queries to dashboard development and insight generation.

It also helped me understand that effective data analysis involves more than creating visualizations. Understanding the metrics, selecting suitable aggregations, and communicating findings clearly are equally important.
