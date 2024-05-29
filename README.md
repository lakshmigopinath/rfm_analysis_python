# RFM Analysis

This repository contains a project for performing RFM (Recency, Frequency, Monetary) analysis on customer transaction data. The goal is to segment customers based on their purchasing behavior to aid in targeted marketing strategies.

## Dataset

The dataset used for this analysis contains the following columns:

| Column      | Non-Null Count | Dtype   |
|-------------|----------------|---------|
| msisdn      | 302031         | int64   |
| cdr_date    | 302031         | object  |
| product_id  | 302031         | int64   |
| total_amt   | 302031         | float64 |
| total_cnt   | 302031         | int64   |

### Column Descriptions

- `msisdn`: The unique identifier for each customer.
- `cdr_date`: The date of the transaction.
- `product_id`: The unique identifier for each product.
- `total_amt`: The total amount spent in each transaction.
- `total_cnt`: The total count of items purchased in each transaction.

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook
- Required Python packages: `pandas`, `numpy`, `matplotlib`, `seaborn`

