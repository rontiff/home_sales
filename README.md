
After caching the temporary table home_sales, the query runs about 0.000116 seconds faster compared to before caching.

Partitioning the data by "date_built" and creating a temporary table called homes_temp_view from the parquet data further improves query time by an additional 0.000160 seconds compared to using cached data.
