# Home_Sales

This project uses PySpark and SparkSQL to analyze a home sales dataset. The goal was to calculate average home prices based on different features such as year built, number of bedrooms and bathrooms, square footage, and view ratings. The analysis included creating temporary views, caching tables, and writing partitioned Parquet files to optimize performance. Query run times were compared across uncached, cached, and partitioned data to demonstrate the benefits of Spark's optimization tools. The entire assignment was completed in Google Colab using a dataset hosted on AWS S3.
