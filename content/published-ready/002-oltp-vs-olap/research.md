# Research notes

- OLTP (Online Transaction Processing) supports operational workloads such as order creation and account updates, commonly many short transactions.
- OLAP (Online Analytical Processing) supports analytical queries, often aggregating larger datasets for reporting and decision support.
- ETL means Extract, Transform, Load; one way to prepare and move data into analytical platforms.
- Warehouses generally emphasize curated/structured analytical data; lakes can store a wider range of formats and processing states.

**Caveats:** Modern architectures blur boundaries. Not every OLTP query is a point lookup or every OLAP query a full scan. Warehouses/lakes vary by implementation. ETL is not the only integration pattern; ELT, CDC and streaming are also common.

Suggested reading: Microsoft Learn https://learn.microsoft.com/ ; AWS data lake/warehouse docs https://docs.aws.amazon.com/ ; Google Cloud analytics docs https://cloud.google.com/docs . Verify exact pages/claims before publishing.
