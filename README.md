# Data Ingestion for RAGs with dlt

#### What is data ingestion

The process of extracting data from a producer, transporting it to a convenient environment,
and preparing it for usage by normalizing it, sometimes cleaning, and adding metadata.
Sometimes the format in which it appears is structured, and with an explicit schema (e.g.
Parquet or a db table)
Most of the time, the format is weakly typed and without explicit schema (e.g. csv and json), in
which case some normalization and cleaning is required
In many data science teams, data magically appears - because the engineer loads it.