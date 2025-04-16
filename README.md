# 🚀 PySpark-Databricks Learning Journey – Beginner to Advanced

## ✅ Day 1: Big Data & Spark Intro
- What is Big Data?
- Spark Architecture
- Why PySpark?

## ✅ Day 2: Setup + Hello World
- Setup Databricks
- Create Cluster & Notebook
- `spark.range()`, `.printSchema()`

## ✅ Day 3: RDD vs DataFrame + CSV I/O
- RDDs vs DataFrames
- Read CSV → `.read.option("header", True)`
- Write CSV → `.write.mode("overwrite")`

## ✅ Day 4: Aggregations & groupBy
- `groupBy().agg()`
- `count`, `avg`, `max`, `min`
- Order results using `.orderBy()`

## ✅ Day 5: Joins, UDFs & withColumn
- `df1.join(df2, on="key", how="left")`
- `withColumn("new", col("existing") * 0.1)`
- UDF creation + registration

## ✅ Day 6: Window Functions + SQL
- `rank()`, `dense_rank()`, `row_number()` with `Window`
- `.createOrReplaceTempView()` + `spark.sql()`

## ✅ Day 7: File Formats & Partitioning
- Read/Write CSV, JSON, Parquet
- `partitionBy("col").write.parquet()`
- Best practices (Parquet preferred)

## ✅ Day 8: Performance Tuning
- `repartition()`, `coalesce()`
- `cache()`, `broadcast()`
- `.explain()` to analyze plan

## ✅ Day 9–10: Final Project
- Read employee + dept CSVs
- Join, clean, transform
- Window function + Aggregation
- Save final data as Parquet (partitioned)

> 💡 Full project EDA → Join → Clean → Transform → Save  
> All code written in Databricks, production-style
