# # Amazon Data Analysis Project

## Overview
This project delivers a deep and comprehensive analysis of Online Retail Data spanning two years (2009-2011). The core focus is on understanding customer behavior and evaluating financial and logistical performance through advanced RFM analysis (Recency, Frequency, Monetary) and the identification of geographical and seasonal trends. The ultimate goal is to transform voluminous raw data into a dynamic, actionable business dashboard using Power BI.

## Features
- **Data Cleaning and Merging**: Efficiently processing and merging large CSV files directly within Power query excel.
- **Advanced RFM Analysis**: Segmenting customers based on their purchasing behavior to identify the most valuable and at-risk clients.
- **Trend Analysis**: Identifying seasonal patterns and sales peaks using time-series analysis (Line Charts).
- **Custom Categorization**: Creating product categories based on text descriptions to enable category-level performance tracking.
- **Geographic Visualization**: Pinpointing core markets and sales performance by country using interactive maps.

## Technologies Used
**The project leveraged a blended approach, demonstrating proficiency in both traditional spreadsheet analysis and modern business intelligence tools to handle the full data lifecycle**
- **Microsoft Excel**: Served as the primary platform for initial data engineering and preparation. This included:
   - Data Appending and Cleaning: Merging the two years of data files and performing initial cleaning tasks (handling nulls, correcting data types).
   - Feature Engineering: Creating the Category column by applying conditional logic (e.g., IFS formula) to the product descriptions.
- **Power BI**: The core platform for advanced analysis, data modeling, and final visualization.
   - DAX (Data Analysis Expressions): Used to build all critical, dynamic measures, including RFM analysis (Recency, Frequency using DISTINCTCOUNT, Monetary), Total Sales, and other KPIs.
   - Visualization: Creating the interactive dashboard, including the Line Chart for trends, Scatter Plot for customer segmentation, and the Map for geographical analysis.
## Key Performance Indicator (KPI)
- **Total Sales**: The overall monetary value of revenue generated.
- **Number of Transactions**: The total count of unique invoices processed (actual purchases).
- **Unique Customers**: The size of the active customer base analyzed.
- **Recency**: The average number of days since a customer's last purchase (a measure of customer activity).
- **Frequency**: The average number of unique purchases made per customer.

## Usage
- raw data : https://github.com/hypersquier/Amazon-Data-Analysis-Project/blob/main/amazon.csv
- Project link : https://github.com/hypersquier/Amazon-Data-Analysis-Project/blob/main/Amzon%20Dahsboard.xlsx
Open the main Excel analysis file and follow the steps in each sheet to clean, explore, and visualize the data.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements.

## License
This project is licensed under the MIT License.

## Contact
For questions or collaboration, please contact [zarab99999@gmail.com].
