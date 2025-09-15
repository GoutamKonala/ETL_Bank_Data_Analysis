# ETL and Bank Data Analysis

This repository contains a data analysis project focused on the market capitalization of the world's largest banks. The project involves extracting data from a Wikipedia page, cleaning and preparing the data, performing exploratory data analysis (EDA), and querying the data to derive business insights. The analysis is performed using Python and PySpark.

## Objective

The main objective of this analysis is to:
- Identify the top 10 largest banks by market capitalization.
- Perform data cleaning and preparation to ensure data quality.
- Conduct exploratory data analysis to understand the distribution and relationships in the data.
- Convert market capitalization values into multiple currencies (USD, GBP, EUR, INR).
- Derive actionable insights that can support financial decision-making.

## Dataset

The dataset used in this project is sourced from the Wikipedia page "[List of largest banks](https://en.wikipedia.org/wiki/List_of_largest_banks)". The data is programmatically scraped from the page and includes the following attributes:
- **Rank:** The rank of the bank based on market capitalization.
- **Bank Name:** The name of the bank.
- **Market Cap (USD Billion):** The market capitalization of the bank in billions of US dollars.

Additionally, exchange rate data is used for currency conversion.

## Technologies Used

- **Python:** The primary programming language used for the analysis.
- **Pandas:** For data manipulation and analysis.
- **PySpark:** For distributed data processing.
- **Matplotlib & Seaborn:** For data visualization.
- **Jupyter Notebook:** As the development environment.

## Setup and Execution

To run this project, you need to have a Python environment with the necessary libraries installed.

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Dependencies

You can install the required libraries using pip:

```bash
pip install pandas pyspark matplotlib seaborn
```

### Running the Notebook

1.  Clone this repository to your local machine.
2.  Navigate to the repository directory.
3.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4.  Open the `ETL_Bank_Data_Analysis_Lakshmi_Goutam_Reddy_Konala.ipynb` notebook and run the cells sequentially.

## Author

*   **Lakshmi Goutam Reddy Konala**
