## Retail Store Data Modeling and Analysis using DataStage

### Project Overview:

This project aims to implement a star-schema data warehousing flow and utilize IBM InfoSphere DataStage to develop efficient ETL (Extract, Transform, Load) pipelines. The goal is to create data marts and perform analysis on them using data from a fictional retail store.

### Problem Statement:

A national department store is building a star-schema-based sales analysis data warehouse with dimensions for customer, store, and product. It's crucial to preserve versions of dimension attribute changes to ensure accurate results with queries relating to prior attribute versions.

### Data Source:

The data source for populating the star schema is the store's online transaction processing (OLTP) system.

### Project Steps:

1. **Building the Physical Data Model:** Develop a star schema with dimensions for product, retail, and customer, along with a fact table for transactions.

2. **Extraction:** Extract relevant data from the data warehouse, including customer, store, and product information.

3. **Transformation:** Transform the extracted data to align with business needs, such as converting customer name columns to uppercase.

4. **Data Mart Creation:** Develop a data mart named RETAIL_DATA_MART, containing transaction details categorized by customer type ("citizen" or "foreign"), product information, and purchased stock.

5. **Loading:** Load the transformed data into the RETAIL_DATA_MART data mart.

6. **Data Mart Analysis:** Utilize the RETAIL_DATA_MART to answer specific business needs, including:
   - Display the count of transactions for each employee in each store.
   - Identify the customer type generating the highest profit.
   - Attribute a bonus to the customer(s) contributing the most to profit.

### Project Files:

- **DataStage Jobs:** Contains the dsx files for the DataStage jobs.
- **Dataset:** Contains the data after modeling in a star schema data warehouse model.

### Conclusion:

This project demonstrates the use of IBM InfoSphere DataStage to build ETL pipelines for a retail store's data warehousing and analysis needs. By implementing a star-schema model and utilizing DataStage for ETL processes, the project ensures efficient data management and facilitates insightful analysis for informed decision-making in the retail domain.
