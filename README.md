Project 1 - Data Cleaning and Preparation

# DecodeLabs Project 2 – Exploratory Data Analysis

## Project Objective
The objective of this project is to perform Exploratory Data Analysis (EDA) on an e-commerce sales dataset to identify patterns, trends, distributions, and outliers.

## Dataset
The dataset contains e-commerce order-level information, including:

- Order ID
- Order Date
- Customer ID
- Product
- Quantity
- Unit Price
- Payment Method
- Order Status
- Items in Cart
- Coupon Code
- Referral Source
- Total Price

## Tools and Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel

## Project Structure

```text
DecodeLabs_Project_2_EDA/
│
├── README.md
├── requirements.txt
│
├── data/
│   └── Dataset_refined.xlsx
│
├── notebooks/
│   └── Project_2_EDA.ipynb
│
├── visuals/
│   ├── total_price_distribution.png
│   ├── product_order_count.png
│   ├── product_wise_revenue.png
│   ├── average_order_value_by_product.png
│   ├── monthly_sales_trend.png
│   ├── monthly_order_trend.png
│   ├── order_status_distribution.png
│   ├── payment_method_revenue.png
│   ├── referral_source_revenue.png
│   ├── total_price_boxplot.png
│   ├── correlation_heatmap.png
│   └── unitprice_vs_totalprice.png
│
└── report/
    └── EDA_Project_Report.pdf

Key Findings
The dataset contains 1,200 orders from 1,189 unique customers.
Gross order value is ₹1,264,761.50.
The average order value is ₹1,053.97, while the median order value is ₹823.60.
Chair and Printer were the strongest products by gross order value.
Laptop had the highest average order value.
June 2024 was the strongest month by sales.
Credit Card generated the highest gross order value, while Online was the most-used payment method.
FREESHIP was the most-used coupon code.
Instagram generated the highest gross order value among referral sources.
Eight high-value TotalPrice outliers were identified using the IQR method.
Cancelled and returned orders should be considered when calculating final realized revenue.
How to Run the Project
Clone or download this project folder.
Install the required libraries:
pip install -r requirements.txt
Open the notebook:
notebooks/Project_2_EDA.ipynb
Run all cells in order.
Conclusion

The EDA identified sales patterns, product performance, customer-order behaviour, marketing-channel performance, and high-value transactions. These findings can support later dashboard development, marketing decisions, inventory planning, and revenue analysis.
