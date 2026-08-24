---
layout: default
title: Demo Presentation Requirements
permalink: /teaching/fall2026/demo/
---

<style>
  table.demo-requirements {
    border-collapse: collapse;
    width: 100%;
  }
  
  table.demo-requirements th,
  table.demo-requirements td {
    border: 1px solid #ddd;
    padding: 8px;
  }
  
  table.demo-requirements th {
    background-color: #f2f2f2;
  }
  
  table.demo-requirements th:first-child,
  table.demo-requirements td:first-child {
    min-width: 70px;
    text-align: right;
  }
</style>

## FA26 CS511: Demo Requirements

### Overview

Students can earn up to 4% extra credit by presenting a demo related to a lecture topic. Demos should showcase practical implementations, tools, or systems discussed in class.

### Requirements

**Duration:** 20 minutes

**Content:**
- Demonstrate a working system or tool related to the lecture topic
- Explain the key concepts and how they relate to the course material
- Show interesting features or capabilities
- Discuss practical use cases or applications
- Be prepared to answer questions from the class

**Technical Setup:**
- Test your demo before class
- Have a backup plan if live demos fail (screenshots, recorded video, etc.)
- Ensure your demo works with the classroom equipment

### Sign-up

Use the [Demo Sign-up Form](https://docs.google.com/forms/d/e/1FAIpQLSdGjxA9EXm11DsGAdeNlAXehm3-PaAzP2HBSHdKYBjhHOkkFQ/viewform?usp=dialog) to reserve your slot.

Sign-ups open exactly 7 days before each class at 11:00 AM. First come, first served.




## Important Concepts that Should be Covered

| Lec # | Demo System | Objective |
| ---: | --- | --- |
| 1 | MongoDB | Demonstrate document-oriented NoSQL operations including CRUD, indexing, and aggregation pipelines. |
| 2 | Dask | Show how parallel data processing works with distributed dataframes and task scheduling. |
| 3 | Join through MapReduce | Demonstrate how relational operations, including joins and group-by aggregation, can be performed using the map-reduce interface. |
| 4 | HDFS | Explain distributed file system operations, including data get/put and replication. |
| 5 | Parquet | Demonstrate columnar storage format features with compression and encoding techniques for analytics. |
| 6 | Parquet (JSON) | Show how nested data encoding works for hierarchical structures. |
| 8 | PostgreSQL | Demonstrate query optimization by examining execution plans and cost-based query planning. |
| 9 | GraphX | Show vertex-centric graph processing model for iterative algorithms like PageRank. |
| 10 | Kafka | Demonstrate message streaming with topics, partitions, and consumer groups. |
| 11 | Spark - PageRank | Implement iterative graph algorithms with RDD operations and demonstrate convergence criteria. |
| 12 | Materialize | Show how incremental view maintenance and streaming SQL provide real-time updates. |
| 13 | PostgreSQL MVCC | Demonstrate multi-version concurrency control, transaction isolation levels, and snapshot isolation. |
| 16 | RocksDB | Explain key-value store's basic interface and operations. What happens if the system is killed? |
| 17 | Spark - HLL | Demonstrate probabilistic cardinality estimation using HyperLogLog sketches for big data. |
| 21 | HNSWlib | Show how hierarchical navigable small world graphs enable approximate nearest neighbor search. |
| 22 | FAISS | Demonstrate inverted file index with product quantization for large-scale vector search. |
| 23 | e5 | Show dense passage retrieval using transformer-based embeddings and similarity search. |
| 25 | Llama | Demonstrate language model inference, prompting techniques, and text generation capabilities. |
| 26 | mini-swe-agent | Show how AI agents perform automated code generation, testing, and repository navigation. |
| 27 | Kishu | Demonstrate process checkpointing, state serialization, and restoration for long-running computations. |
{: .demo-requirements}

