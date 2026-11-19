# ds-capstone-project

# Retail Sales Analysis 📊

## 1. About the Project

This project focuses on analysing an online retail sales dataset to understand product performance, sales trends and relationships between different numerical variables.

The analysis helps identify the best-selling products, products generating the highest revenue, monthly sales patterns and countries contributing the most to total revenue.

## 2. Objectives

- Identify the best-selling products based on total quantity sold.
- Find the products generating the highest revenue.
- Analyse monthly revenue trends.
- Compare sales performance across different countries.
- Calculate descriptive statistics and study relationships between variables.
- Present insights using charts and visualisations.

## 3. Tools and Technologies Used

- **Python** – Programming language used for data analysis.
- **Pandas** – Data loading, cleaning and manipulation.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualisation.
- **Seaborn** – Statistical charts and correlation heatmap.
- **Google Colab / Jupyter Notebook** – Development environment.

## 4. Dataset Description

The project uses the **Online Retail Dataset**, which contains transactional data from a UK-based online retail business.

The original dataset contains 541,909 records and 8 columns.

Important columns include:

- `InvoiceNo` – Invoice number for each transaction.
- `StockCode` – Product identification code.
- `Description` – Product name.
- `Quantity` – Number of products purchased.
- `InvoiceDate` – Date and time of transaction.
- `UnitPrice` – Price per product.
- `CustomerID` – Customer identification number.
- `Country` – Customer's country.

A new column named `Revenue` was calculated using:

`Revenue = Quantity × UnitPrice`

## 5. Steps Performed

1. **Data Loading:** Imported the dataset using Pandas.
2. **Data Inspection:** Checked the dataset's shape, columns, data types and statistical summary.
3. **Data Cleaning:** Removed duplicate records, missing product descriptions, invalid dates, cancelled invoices, negative quantities and non-positive prices.
4. **Feature Engineering:** Created Revenue, Year, Month, MonthName and YearMonth columns.
5. **Exploratory Data Analysis (EDA):** Analysed product sales, monthly revenue and country-wise performance.
6. **Statistical Analysis:** Calculated mean, median, standard deviation, quartiles and interquartile range.
7. **Correlation Analysis:** Examined relationships between Quantity, UnitPrice and Revenue.
8. **Visualisation:** Created bar charts, line charts, scatter plots and a correlation heatmap.

## 6. Key Findings

- **Best-selling product by quantity:** PAPER CRAFT, LITTLE BIRDIE, with 80,995 units sold.
- **Highest revenue-generating product:** DOTCOM POSTAGE, generating 206,248.77 in revenue.
- **Highest revenue month:** November 2011, with approximately 1.50 million in revenue.
- **Top-performing country:** United Kingdom, contributing approximately 9.00 million in revenue.
- **Correlation:** Quantity and Revenue showed a strong positive correlation of approximately 0.91.

*Note: The correlation between Quantity and Revenue is partly mathematical because Revenue is calculated using Quantity × UnitPrice.*

## 7. Conclusion

This project helped explore real-world retail transaction data using Python and its data analysis libraries. It provided insights into best-selling products, revenue patterns, country-wise performance and relationships between numerical variables.

Through this project, I gained practical experience in data cleaning, exploratory data analysis, statistical calculations, correlation analysis and data visualisation.

## 8. Project Limitations

- The dataset does not contain a dedicated product category column.
- Some customer identification values are missing.
- Negative quantity transactions and cancelled invoices were excluded from the analysis.
- December 2011 contains incomplete monthly data.
- The analysis focuses on historical data and does not include sales forecasting.


## 9. Project Files

- `capstoneproject.ipynb` – Main Python notebook containing the complete analysis.
- `Cleaned_OnlineRetail.csv` – Cleaned dataset generated during the project.
- `Product_Sales_Summary.csv` – Product-wise sales summary.
- `Retail_Sales_Capstone_Report.pdf` – Project report.


**Author:** Aditi Bisht  
**Course:** B.Sc. Data Science  
**University:** K.R. Mangalam University
