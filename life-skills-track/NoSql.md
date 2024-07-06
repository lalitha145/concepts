# Introduction

## What is NoSQL?

NoSQL databases, short for "not only SQL," store data differently than traditional relational databases. They come in various types based on their data models: document, key-value, wide-column, and graph. These databases offer flexible schemas and can handle large amounts of data efficiently.

## What is a NoSQL Database?

NoSQL databases refer to non-relational databases that store data in a flexible, natural way. They are not restricted to SQL and can handle various types of data formats and structures.

## Types of NoSQL Databases
**1. Document-Oriented Databases:** Store data in documents similar to JSON objects.
Examples: MongoDB, Couchbase.

A typical document will look like the following:

```

{
  "_id": "12345",
  "name": "foo bar",
  "email": "foo@bar.com",
  "address": {
    "street": "123 foo street",
    "city": "some city",
    "state": "some state",
    "zip": "123456"
  },
  "hobbies": ["music", "guitar", "reading"]
}

```

**2. Key-Value Databases:** Store data as key-value pairs. Examples: Amazon DynamoDB, Redis.

A simple view of data stored in a key-value database is given below:

```
Key: user:12345
Value: {"name": "foo bar", "email": "foo@bar.com", "designation": "software developer"}

```

**3. Wide-Column Stores:** 
Store data in tables with rows and dynamic columns. Examples: Apache Cassandra, HBase.
A typical example of how data is stored in a wide-column is as follows:

| name      | id    | email        | dob        | city      |
|-----------|-------|--------------|------------|-----------|
| Foo bar   | 12345 | foo@bar.com  |            | Some city |
| Carn Yale | 34521 | bar@foo.com  | 12-05-1972 |           |



**4. Graph Databases:** Store data as nodes and edges, representing entities and their relationships. 
Examples: Neo4J, Amazon Neptune.

Below is an example of how data is stored:
![Screenshot from 2024-07-06 12-15-54](https://github.com/lalitha145/repo-concepts/assets/97296095/9ee0f082-6d3e-4da9-9527-d0504ccfba25)



**5. Multi-Model Databases:** Support multiple types of data models. Examples: CosmosDB, ArangoDB.

## Brief History of NoSQL Databases

NoSQL databases emerged in the late 2000s due to the need to store and manage large volumes of diverse data efficiently. They gained popularity as the cost of storage decreased and applications required more flexible data management solutions.

## Quick comparison of types of databases — NoSQL

![Screenshot from 2024-07-06 12-34-27](https://github.com/lalitha145/repo-concepts/assets/97296095/ad17d5c5-67a0-4d0e-869b-ff19f0d5a1b1)


## NoSQL Database Features

- **Distributed Computing**: Data is spread across multiple servers.
- **Scalability**: Easily handles growing data volumes.
- **Flexible Schemas**: Adaptable to changes in data structure.
- **Ease of Use for Developers**: Simplifies data management.
- **High Availability**: Ensures data is always accessible.
- **BASE Compliance**: Basic Availability, Soft state, Eventual consistency.

## Relational Database vs NoSQL Database Example

In a relational database (RDBMS), data about users and their hobbies would be stored in separate tables, requiring joins to retrieve all information. In a NoSQL document database, all related information can be stored in a single document, making queries faster and simpler.

## Differences Between RDBMS and NoSQL Databases

- **Data Modeling**: 
  - RDBMS uses tables
  - NoSQL uses various models (document, key-value, etc.)

- **Schema**: 
  - RDBMS has a fixed schema
  - NoSQL has a flexible schema

- **Query Language**: 
  - RDBMS uses SQL
  - NoSQL uses different query languages based on the database type

- **Scalability**: 
  - RDBMS is designed for vertical scaling
  - NoSQL is designed for both vertical and horizontal scaling

- **Data Relationships**: 
  - RDBMS uses joins
  - NoSQL can nest related data within documents

- **Transaction Type**: 
  - RDBMS transactions are ACID-compliant
  - NoSQL can be ACID or BASE-compliant

- **Performance**: 
  - RDBMS is suitable for read-heavy workloads
  - NoSQL is suitable for real-time processing and big data analytics

- **Distributed Computing**: 
  - NoSQL is designed for distributed data storage
  - RDBMS supports clustering and replication but is less flexible

- **Fault Tolerance**: 
  - NoSQL has built-in fault tolerance
  - RDBMS relies on replication and backup mechanisms

# Relational database vs NoSQL database example

In a relational database (RDBMS), data about users and their hobbies would be stored in separate tables, requiring joins to retrieve all information. In a NoSQL document database, all related information can be stored in a single document, making queries faster and simpler.

## Differences Between RDBMS and NoSQL Databases

- **Data Modeling**: RDBMS uses tables; NoSQL uses various models (document, key-value, etc.).
- **Schema**: RDBMS has a fixed schema; NoSQL has a flexible schema.
- **Query Language**: RDBMS uses SQL; NoSQL uses different query languages based on the database type.
- **Scalability**: RDBMS is designed for vertical scaling; NoSQL is designed for both vertical and horizontal scaling.
- **Data Relationships**: RDBMS uses joins; NoSQL can nest related data within documents.
- **Transaction Type**: RDBMS transactions are ACID-compliant; NoSQL can be ACID or BASE-compliant.
- **Performance**: RDBMS is suitable for read-heavy workloads; NoSQL is suitable for real-time processing and big data analytics.
- **Distributed Computing**: NoSQL is designed for distributed data storage; RDBMS supports clustering and replication but is less flexible.
- **Fault Tolerance**: NoSQL has built-in fault tolerance; RDBMS relies on replication and backup mechanisms.

## When Should NoSQL be Used?

## Use NoSQL databases when:

- Developing in an Agile environment.
- Storing structured and semi-structured data.
- Handling large volumes of data.
- Needing scalable architecture.
- Working with modern application paradigms like microservices.

 ## NoSQL database misconceptions
 
 Misconceptions About NoSQL Databases

1. **Misconception**: NoSQL can't handle relationship data.
   - **Reality**: NoSQL databases can store relationship data differently, often more efficiently.

2. **Misconception**: NoSQL doesn't support ACID transactions.
   - **Reality**: Some NoSQL databases, like MongoDB, do support ACID transactions.

 
# Summary

NoSQL databases provide a variety of benefits, including flexible data models, horizontal scaling, lightning-fast queries, and ease of use for developers. NoSQL databases come in a variety of types, including document stores, key-values databases, wide-column stores, graph databases, and multi-model databases.

# References

[NoSQL Explained](https://www.mongodb.com/resources/basics/databases/nosql-explained)





