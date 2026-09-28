## Gold layer data

For final tables data insights

**1. gold.dim_customers**
* Information about customers

| Colun name | Data type | Note |
|----------|----------|----------|
| Customer_key | bigint |Surrogate key|
| Customer_id | int ||
| Customer_nrumber | nvarchar(50) ||
| First_name | nvarchar(50) ||
| Last_name | nvarchar(50) ||
| Gender | nvarchar(50) ||
| Birth_date | date ||
| Country | nvarchar(50) ||
| Marital_status | nvarchar(50) ||
| Date_created | date ||

**2. gold.dim_products**
* Information about products that are still manufactured and sold

| Colun name | Data type | Note |
|----------|----------|----------|
| Product_key | bigint |Surrogate key|
| Product_id | int ||
| Category_id | nvarchar(50) ||
| Subcategory_id | nvarchar(50) ||
| Category_name | nvarchar(50) ||
| Subcategory_name | nvarchar(50) ||
| Product_name | nvarchar(50) ||
| Product_line | nvarchar(50) ||
| Product_cost | int ||
| Maintenance | nvarchar(50) ||
| Product_start_date | date ||
| Product_end_date | date ||

**3. gold.fact_sales**
* Information about product sales

| Colun name | Data type | Note |
|----------|----------|----------|
| Sales_key | nvarchar(50) ||
| Customer_key | bigint |Foreign key|
| Product_key | bigint |Foreign key|
| Price | int ||
| Quantity | int ||
| Sales | int ||
| Order_date | date ||
| Ship_date | date ||
| Due_date | date ||
