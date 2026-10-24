# E-Commerce Sales & Customer Analytics

## Project Overview
This project focuses on analyzing e-commerce sales and customer behavior using Python. The analysis uses the Olist Brazilian E-Commerce Dataset to explore sales performance, product categories, customer purchasing patterns, payment methods, customer reviews, and delivery performance.

The goal is to extract meaningful insights from raw e-commerce data and support data-driven business decisions.

## Project Objectives
- Analyze overall sales performance and revenue.
- Identify top-performing product categories.
- Examine monthly sales trends.
- Analyze order status and delivery performance.
- Understand customer purchasing behavior and repeat customers.
- Explore payment methods and customer review scores.
- Analyze sales across different states and cities.
- Clean, process, and export filtered data for further analysis.

## Technologies Used
- **Python** — Data analysis and processing
- **Pandas** — Data cleaning, manipulation, and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Jupyter Notebook** — Interactive development and analysis

## Project Files

| File Name | Description |
|---|---|
| `E-Commerce Sales & Customer Analytics.ipynb` | Main notebook containing data cleaning, analysis, and visualizations |
| `ecommerce_filtered_data.csv` | Filtered dataset exported after data processing |
| `olist_customers_dataset.csv` | Customer information |
| `olist_order_items_dataset.csv` | Order item details, prices, and freight values |
| `olist_order_payments_dataset.csv` | Payment information |
| `olist_order_reviews_dataset.csv` | Customer reviews and ratings |
| `olist_orders_dataset.csv` | Order details and delivery timestamps |
| `olist_products_dataset.csv` | Product information and categories |

## Key Analysis Areas

### 1. Sales Analysis
- Total revenue
- Total orders
- Average order value
- Total items sold
- Monthly revenue trends

### 2. Product Category Analysis
- Revenue by product category
- Top-performing categories
- Comparison of category sales

### 3. Customer Analysis
- Customer purchasing patterns
- Repeat customer analysis
- Customer distribution by location

### 4. Payment Analysis
- Distribution of payment methods
- Payment values by payment type

### 5. Review Analysis
- Customer review score distribution
- Average review score
- Positive, neutral, and negative review analysis

### 6. Delivery Analysis
- Delivery time analysis
- Late delivery identification
- Order status distribution

### 7. Geographical Analysis
- Sales by state
- Sales by city
- Regional sales comparisons

## Visualizations
The project uses Matplotlib and Seaborn to create visualizations, including:
- Monthly sales trend line chart
- Top product category bar chart
- Order status chart
- Delivery time distribution plot
- Payment method chart
- Customer review score chart
- State-wise revenue chart

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/nitinsharma-official/E-Commerce-Sales-Customer-Analytics.git
   ```

2. Open the project folder:
   ```bash
   cd E-Commerce-Sales-Customer-Analytics
   ```

3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open `E-Commerce Sales & Customer Analytics.ipynb` and run the cells.

**Note:** Keep all required CSV files in the same folder as the notebook.

## Dataset
This project uses the **Olist Brazilian E-Commerce Dataset**, which contains information about orders, customers, products, payments, reviews, and deliveries.

## Key Learnings
- Data cleaning and preprocessing
- Handling missing values and duplicate records
- Merging multiple datasets using Pandas
- Working with dates and timestamps
- Exploratory Data Analysis (EDA)
- Customer and sales performance analysis
- Data visualization using Matplotlib and Seaborn
- Exporting filtered datasets to CSV

## Author
**Nitin Sharma**
GitHub: [nitinsharma-official](https://github.com/nitinsharma-official)

If you find this project useful, consider giving the repository a star!
