# Medical Drug Interactions and Prediction

This project focuses on analyzing and predicting interactions between various medical drugs. Understanding drug-drug interactions (DDIs) is crucial for ensuring patient safety and effective therapeutic outcomes.

## Project Overview

This repository contains the following files:

**diseasesInfo.csv**: Data related to various diseases.

**drugsInfo.csv**: Includes data about different drugs.

**mapping.csv**: Mapping data of the relationships between diseases and drugs or between different drugs.

**neo4j.dump**: A database dump file for use with Neo4j graph database, containining graphical representation and analysis of drug-drug interactions (DDIs).

## Usage

To explore and utilize the data:

Clone the Repository:

```bash
git clone https://github.com/Patel4007/Medical-Drug-Interactions-and-Prediction.git
cd Medical-Drug-Interactions-and-Prediction
```

### Data Files:

Ensure you have the necessary software to open and analyze CSV files (diseasesInfo.csv, drugsInfo.csv, mapping.csv).
For the neo4j.dump file, you'll need to set up a Neo4j database to import and explore the data.

### Neo4j Database Setup

To utilize the neo4j.dump file:

1. Install Neo4j:

- Download and install Neo4j.

2. Import the Database Dump:

- Start the Neo4j server.

- Use the Neo4j browser or command-line tools to import the neo4j.dump file.

3. Explore the Data:

- Once imported, you can run Cypher queries to analyze drug interactions and related information.

## Contribution

Contributions to enhance the project are welcome. Feel free to fork the repository, make improvements, and submit pull requests.

## License

This project is licensed under the MIT License.
