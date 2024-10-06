# Car Insurance Claims Analysis Dashboard

## Project Overview
This project focuses on building a Power BI dashboard that provides insights into customer claims, premiums earned, vehicle coverage, and regional performance. The data transformation, modeling, and visualization were performed using Power BI, leveraging tools such as Power Query and DAX.

## Datasets
The project involved working with four datasets:
- **Customer**: Contains customer details.
- **Vehicles**: Includes data about vehicles.
- **Region**: Contains information about regions where customers and vehicles are located.
- **Claims**: Includes data about insurance claims made by customers.

### Data Preprocessing:
#### **Customer Table:**
- Converted the `Date of Birth` column from an integer format to a proper Date format.

#### **Fact Table:**
- Converted the `Premium Amount`, `Deductible`, and `Claim Amount` columns into currency formats for accurate financial reporting.

#### **Vehicles Table:**
- Converted the following columns from Date Time format to Date format:
  - `Registration Date`
  - `Inspection Date`
  - `Coverage Start Date`
  - `Coverage End Date`
- Converted the `Current Value` column to currency format for accurate analysis of vehicle values.

## Calendar Table
- Created a **Calendar** table by generating a list of dates from January 1st, 2021 to December 31st, 2024.
- Added columns for Month, Day, and other date-based attributes to facilitate time-based analysis.

## Measures
To enhance data insights, several key measures were created using DAX:
- **Premiums Earned**: Summation of the total premiums earned across the dataset.

## Power BI Dashboard
The final Power BI dashboard provides a comprehensive view of the following:
- **Customer Claims**: Visualizing the total claims made by customers.
- **Premiums Earned**: Summarizing the revenue generated through premiums.
- **Vehicle Coverage**: Analyzing vehicle coverage data including start and end dates.
- **Regional Performance**: Insights into how different regions perform in terms of claims and premiums.

The data cleaning, transformation, and modeling were performed using Power Query and DAX to ensure accurate and insightful analytics.

## Technologies Used
- **Power BI**: Data visualization, dashboard creation, and DAX calculations.
- **Power Query**: Data cleaning and transformation.
- **DAX (Data Analysis Expressions)**: Creating custom measures and calculations.

## Conclusion
This project provided critical insights into car insurance claims, premiums, and vehicle coverage. The Power BI dashboard offers a detailed analysis that can assist in better decision-making regarding claims and policy management.
