**Data Dictionary for Gold Layer**

Overview

The Gold Layer is the business level data representation, structured to support analytical and reporting use cases. It consists of dimension 
tables and fact tables for specific business metrics.

_______________________________________________________________________________________________________________________________________________

1. gold dim_customers
   Purpose: Stores customer details enriched with demographic and geographic data.
   Columns:
   
   | Column Name  | Data Type | Description |
   
   |Customer_ key |INT | Surrogate key uniquely identifying each customer record in the dimension table|
