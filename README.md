# tpch-oracle-sql-optimization
Project focused on the analysis and optimization of complex SQL queries using the TPC-H benchmark on Oracle Database Enterprise Edition 21c.

Data was generated using DBGEN, simulating large-scale analytical workloads.

The 22 standard TPC-H queries were executed using QGEN.

Query performance was evaluated using EXPLAIN PLAN and AUTOTRACE.

🛠 Optimization techniques applied:

Parallel query execution to improve response times on large data sets.

Use of Oracle In-Memory to accelerate query performance through columnar storage.

Creation of Materialized Views to precompute and store complex query results.

Implementation of Temporary Tables to simplify and optimize intermediate results.

Design and creation of indexes to reduce access time.

Query rewriting and reformulation for better execution plans.

Tuning Oracle configuration parameters for improved performance.
