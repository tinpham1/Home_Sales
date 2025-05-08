# Home_Sales

This project analyzes home sales data using PySpark and SparkSQL, completed in Google Colab.

## Project Summary

- Read a real estate dataset from AWS S3 into a Spark DataFrame.
- Created temporary SQL views and ran queries to calculate:
  - Average home prices by year for 4-bedroom homes.
  - Prices for 3 bed / 3 bath homes by year built.
  - Average prices for large, 2-story homes with specific features.
  - Price comparisons by view rating for homes priced at $350,000+.
- Measured query performance using:
  - Uncached DataFrames
  - Cached temporary tables
  - Partitioned Parquet data (by `date_built`)
- Saved the dataset as partitioned Parquet files and reloaded it for analysis.
- Verified caching behavior using Spark’s cache and uncache functions.

This project demonstrates scalable data processing, query optimization, and storage efficiency with PySpark.
