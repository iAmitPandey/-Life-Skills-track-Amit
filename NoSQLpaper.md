# A Review on NoSQL Databases

## Abstract:

As utilization of web is expanding step by step and consequently with this measure of information is likewise expanding. Relational database management system are confronting issues while taking care of huge measure of information because of low scalability, continuous information and unstructured information as information on web isn't appropriately organized, it can be semi-structure or unstructured. In this way, with a specific end goal to take care of the issues looked by Relational Database Management System, there is an up and coming classification of Database Management Systems that is "NoSQL". NoSQL databases normally known as "non-SQL" or "Not just SQL" databases. It isn't substitution of Relational Databases however it is another option to it. In this paper, we will examine about NoSQL: where they originated from, why NoSQL, nature of its sorts and correlation with social databases.

## 1. Introduction

The rapid growth of data-driven applications in sectors such as e-commerce, social media, and real-time analytics has presented new challenges in database management. Traditional relational databases, which rely on structured data and predefined schemas, often become obstacle when it comes to scaling horizontally and handling dynamic, unstructured data. NoSQL databases have gained prominence as they allow developers to break free from rigid schema designs and provide more flexible options for data storage and retrieval.

The paper investigates the potential impact of adoping NoSQL databases in adderessing performance and scaling in modern applications.

## 2. NoSQL Databases: An Overview

NoSQL, or "Not Only SQL," refers to a family of database technologies designed to handle large-scale data workloads. Unlike RDBMS, NoSQL systems are optimized for distributed computing, enabling them to scale horizontally by adding more servers. These databases support a variety of data models, including document, key-value, wide-column, and graph-based models, each tailored for different use cases.

### 2.1 MongoDB

MongoDB is a document-oriented database that stores data in a JSON-like format called BSON (Binary JSON). This database is designed for high availability, scalability, and flexibility. Its strengths lie in its ability to manage large volumes of unstructured or semi-structured data while allowing dynamic schema changes.

Use cases: MongoDB is widely used in e-commerce, content management, and real-time analytics​.

### 2.2 Cassandra

Apache Cassandra is a wide-column store designed to handle massive amounts of data across many servers without a single point of failure. It is especially well-suited for applications that require high write throughput and strong fault tolerance, such as IoT devices, time-series data, and recommendation systems. Cassandra achieves high availability and scalability through a masterless architecture, which distributes data evenly across all nodes​.

Use cases: Cassandra is employed by companies like Netflix and Facebook to manage distributed, large-scale workloads​.

### 2.3 Elasticsearch

Elasticsearch is a distributed, document-oriented search engine and database that excels in full-text search and analytics. Built on the Apache Lucene engine, Elasticsearch allows users to query large datasets quickly and efficiently, making it a popular choice for applications where real-time search capabilities are critical.

Use cases: Elasticsearch is commonly used for log and event data analytics, as well as powering search functions on websites and applications.

### 2.4 Neo4j

Neo4j is a graph database that focuses on representing and analyzing relationships between data entities. It leverages a graph structure composed of nodes and edges to store and retrieve interconnected data efficiently. Neo4j is highly suitable for applications involving social networks, fraud detection, and recommendation engines.

Use cases: Neo4j is often used in social media platforms, fraud detection, and network analysis​.

### 2.5 CouchDB

CouchDB is a document-based database that stores data in a schema-free JSON format. Its key feature is multi-master replication, which allows data to be replicated across multiple locations in a fault-tolerant manner. CouchDB is designed to work in distributed environments and provides an offline-first architecture, which makes it ideal for mobile and web applications.

Use cases: CouchDB is typically used in applications requiring synchronization between mobile devices and back-end systems​.

## 3. Conclusion

In this paper, we have examined about NoSQL databases, why we require them, its sorts. Subsecquent to checking on this we come to realize that NoSQL databases that is the reason it is at present embrased by Facebook, Google, Amazon and so forth. Because of their subsequential rate of reception they are ending up extreamly mainstream amoung rest of databases.

## References

[A Review on NoSQL Databases](https://www.researchgate.net/publication/327883334_A_Review_on_NoSQL_Databases)
[NoSQL resource](https://www.mongodb.com/resources/basics/databases/nosql-explained)
