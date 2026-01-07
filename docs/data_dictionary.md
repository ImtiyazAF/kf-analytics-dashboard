# Data Dictionary: Kimia Farma Analytics

## Overview
This dataset contains transactional sales performance data for Kimia Farma branches.

**Source:** BigQuery / Looker Studio
**Granularity:** Per Transaction

## Column Definitions

| Column Name | Data Type | Description | Example Value |
| :--- | :--- | :--- | :--- |
| `transaction_id` | String | Unique identifier for each transaction. | `TRX9116515` |
| `date` | Date | The date of the transaction (YYYY-MM-DD). | `2020-05-12` |
| `branch_id` | Integer | Unique ID for the Kimia Farma branch. | `69213` |
| `branch_name` | String | Name of the branch location. | `Kimia Farma - Klinik...` |
| `branch_rating` | Float | The operational rating of the branch. | `4.8` |
| `city` | Geo | The city where the branch is located. | `Padang` |
| `province` | String | The province where the branch is located. | `Sumatera Barat` |
| `customer_name` | String | Name of the customer. | `Joseph Wolf` |
| `product_id` | String | Unique code for the product sold. | `KF483` |
| `product_name` | String | Name of the pharmaceutical product. | `Psycholeptics drugs...` |
| `product_category` | String | (Field labeled 'Product') The category of the drug. | `Psycholeptics` |
| `actual_price` | Integer | The base price of the product before discount. | `943000` |
| `discount_percentage` | Float | Discount applied to the transaction (0.02 = 2%). | `0.02` |
| `persentase_gross_laba`| Float | Gross profit margin percentage. | `0.3` (30%) |
| `sales` | Float | The final transaction value after discount. | `942811.4` |
| `profit` | Integer | The profit earned from this transaction. | `282900` |
| `target_sales` | Float | The sales target for this record. | `1084233.1` |
| `transaction_rating` | Float | Customer rating for this specific transaction. | `4.3` |
| `customer_satisfaction`| Float | Overall customer satisfaction score. | `4.55` |