# INTRODUCTION

**Duration:** 2-3 days
"Mastering Apache Spark" is an extended workshop designed to familiarize attendees with Apache Spark - a well-known engine for fast Big Data processing. "From zero to hero" means that attende does not need to have prior knowledge of how Apache Spark works, but after two days workshop will be able to spin efficient, robust jobs running on Spark cluster from day one. He or she will not only gain general understanding of what Apache Spark is, what are its modules and how they work. Attendee will get detailed, in-depth insight of Apache Spark internals. This makes this workshop globally unique it prepares its graduates not only to start working with the framework, but also makes them right candidates to tackle any problems that might occur on production - A true heros that each distributed project needs.

# RELEVANCY
Being professional software developer requires keeping balance of both being an expert on a very narrow field but on the same time being up to date with changing challenges our industry. Big Data is one of those fields that simply can not be ignored by professional software engineer. Environments where infrastructure crash is part of the daily routine, collected data that can not fit on a single machine or data that needs to be processed fast (in matters of seconds, not hours) - are just the few challenges that Big Data face. Apache Spark is a fast and general engine for large-scale data processing. It was desighn upfront to handle efficently above mentioned problems.
Regardless whether you do Big Data right now or not, with exponential growth of our industry (in both terms of complexity & users space) & emerging new fields like data science - chances are that in-depth knowledge of Apache Spark might be crucial.

# CONCEPTS & SKILLS
Among the many concepts that attendees will learn are:

Big Data, Map-Reduce, Partitioning, HA & resilience in cluster environment, HDFS
Apache Spark architecture (logical & physical),
Driver program, Master node, Worker node, Executor,
RDD (Resilient Distributed Dataset), Transformations & Actions, Partitions, Tasks,
Pipelining, Shuffeling, DAG (Directed Acyclic Graph), data locality,
Spark Execution Model, Partitoner,
Caching, Checkpointing, Broadcast, Accumulators,
Spark Memory Model,
DataFrames, Datasets, Working with semi-structured & strucutred data (json, parquet, avro),
Spark Catalyst optimizer, predicate push down,
Project Tungsten, Streaming, DStream, Strucutred Streaming, Back pressure & Elastic Scaling

# COURSE OUTLINE
1. Introduction
   * What is Apache Spark?
   * What was before?
   * Challenges, proble & issues with MapReduce
   * The Big Picture
2. Spark Core
   * RDD
   * Transforamtions vs Actions
   * Partitions & Tasks
   * RDDs for key-value
   * Pipelining & Shuffeling
   * DAG & Stages
   * Resilience
   * Performance issues and how to handle them
        1. Common pitfals (groupBy)
        2. Deepr knowledge of how cluster works
        3. Classpath & Serialization issues
        4. Spark configuration
        5. Spark UI & Spark history server
   * Caching & Checkpointing
   * Broadcasts & Accumulators
   * Joins
3. Spark Core - internals
   * The 5 things definig RDD
   * Shuffeling algorithms
   * Spark Memory Model
4. Spark SQL
   * Adventages of semi-structured data
   * SQL
       * Introduction
       * Joins
       * Hive
   * Dataframes
       * Introduction
       * Joins
       * JSON
       * Parquet
       * Avro
   * DataSets
       * Problems with Dataframes
       * Dataset to the rescue!
   * What makes Spark SQL run faster
       * Structure vs Expression
       * Catalyst Optimizer
       * Predicate Push Down
       * Project Tungsten
5. Spark SQL - internals
   * How Dataframes & Datasets are implemented
   * How Catalyst Optimzer works?
6. Spark Streaming
   * Why Streaming?
   * General overview
   * Reciever - long running task
   * Resilence
   * Transforamtions
       * Stateless
       * Stateful (Window & Sliding duration, .reduceByWindow, .updateStateByKey vs .mapWithState)
   * Ultimate Apache Kafka Example
   * Structured Streaming
7. Other topics
   * Back pressure & Elastic Scaling
   * Running Spark on Mesos
   * Q&A

# INSTRUCTOR BIO
Pawel Szulc has more then 10 years of profesional experience as software engineer - during which he worked on numerous number of projects for veriety of clients.
He often call him self a veteran of early Apache Spark adoptions - his first big data project (based on Apache Spark) dates back to 2014. Back then Spark (version 0.9) was still under heavy development, where every problem encountered requried reading Spark's codebase - googling the question was pointless. That being a pain then, prove to be a great asset after a while. Experience gathered was invaluable, allowing Pawel to challange other Spark-based projects he worked on ever since. The knowledge he is now happy to share with you!
Recently he was hired to write Apache Spark connector between HDFS & SlamData's Quasar project.
