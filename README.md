# Car-Sales-And-Revenue-Report
This project analyzes a dataset of **23,906 car sales transactions** to identify customer purchasing trends and regional performance. Using Python, I developed a data processing pipeline to clean raw sales data and extract insights regarding customer demographics, car model popularity, and dealer effectiveness.


## 📊 Dashboard Preview
**Tableau:** https://public.tableau.com/app/profile/sathwik.reddy.nalla/viz/CarSales_17678317240300/CarSalesDashboard

## 📂 Repository Structure
* **`Car_Sales.csv`**: The raw dataset containing transaction details including Date, Customer Name, Dealer info, and Vehicle specifications (Engine, Transmission, Body Style).
* **`Car_Sales_Data_Processing.ipynb`**: A Jupyter Notebook containing the end-to-end data workflow:
    * **Data Cleaning:** Handling missing values and removing duplicate records.
    * **Feature Engineering:** Formatting date columns and standardizing categorical variables.
    * **Exploratory Data Analysis (EDA):** Visualizing sales trends and correlations.
* **`requirements.txt`**: List of Python dependencies required to run the analysis.

## 🔍 Data Description
The dataset includes critical business metrics such as:
* **Transaction Info:** `Date`, `Price ($)`, `Dealer Name`, `Dealer No`.
* **Product Details:** `Company`, `Model`, `Engine`, `Transmission`, `Color`, `Body Style`.
* **Customer Demographics:** `Customer Name`, `Gender`, `Annual Income`, `Phone`.

## 🛠️ Tech Stack
* **Python:** Core programming language.
* **Pandas:** For data manipulation and aggregation.
* **Matplotlib / Seaborn:** For data visualization.
* **Jupyter Notebook:** Interactive development environment.

## 📈 Analysis Goals
* **Sales Performance:** Identify which car manufacturers (Company) and Models have the highest turnover.
* **Customer Profiling:** Analyze the relationship between Annual Income and Price ($) to understand purchasing power.
* **Temporal Trends:** Track sales volume over time using the Date column.
