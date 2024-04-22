# Data Aggregation Pipeline Read Me

## Advanced Query Operations Demonstration

This repository serves as a demonstration of advanced query operations using MongoDB. The tasks outlined below aim to showcase the capabilities of MongoDB in analyzing data at the database layer programmatically.

### Purpose

The purpose of this repository is to provide a hands-on experience with MongoDB's advanced query features, particularly focusing on:

- Utilizing the mongoimport tool to create a database and load documents into a collection.
- Performing various queries to retrieve specific information from the database.
- Designing and implementing aggregation pipelines for more complex data analysis.

### Tasks Overview

#### Task 1: Database Creation and Document Loading

Using the mongoimport tool, the "companies" database will be created by loading documents from the "companies.json" file into the "research" collection. This file is located in the "/usr/local/datasets/" directory in Apporto. The following queries will be executed to verify the successful loading of documents:

1. `db.research.find({"name" : "AdventNet"})`
2. `db.research.find({"founded_year" : 1996},{"name" : 1}).limit(10)`

Screenshots of the statements and their results will be provided as evidence of completion.

#### Task 2: MongoDB Query Operations

Two tasks will be performed using MongoDB queries:

1. Listing the first 20 names of companies founded after the year 2010, ordered alphabetically.
2. Listing the first 20 names of companies with offices in either California or Texas, ordered by the number of employees in descending order.

Screenshots of the statements and their results will be provided as evidence of completion.

#### Task 3: Aggregation Pipeline Implementation

A MongoDB aggregation pipeline will be designed and implemented to show the total number of offices by state for all companies that have offices in the United States. Consideration will be given to the possibility that some companies have offices in multiple states. An explanation of the aggregation pipeline will be provided.

Screenshots of the statements and their results will be provided as evidence of completion.

### Folder Structure
- **screenshots**: Contains screenshots of the executed queries and their results.

### Usage

To replicate the tasks performed in this demonstration:

1. Ensure MongoDB is installed and running.
2. Use the mongoimport tool to load the "companies.json" file into the "research" collection.
3. Execute the provided MongoDB queries to perform the specified tasks.
4. Review the screenshots provided in the "screenshots" folder for verification.

### Contributors

- Larry Johnican


### License

This repository is licensed under the [MIT License](LICENSE).

For any questions or clarifications, please contact Johnicanlarry@gmail.com.

---

This Read Me serves as a guide to understanding the purpose of this repository and the tasks it demonstrates. It provides clear instructions for replicating the tasks and encourages contributions from other users.
