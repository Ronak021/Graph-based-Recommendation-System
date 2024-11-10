
# Graph-Based Recommendation System

A graph-based recommendation system for an online shopping platform, developed using Neo4j and Cypher. This system models user-product relationships to enhance recommendation accuracy and performance.

## Features
- **Flexible Data Modeling**: Uses graph database nodes and edges to represent entities (Users, Products) and relationships (`RATED`, `PURCHASED`, `FRIENDS_WITH`).
- **Personalized Recommendations**: Employs PageRank algorithm to suggest products based on user behavior, social connections, and preferences.
- **Efficient Performance**: Optimized for handling high volumes of transactional data effectively.

## Project Structure
- **Data Generation**: Generates test data in CSV format using Python.
- **Data Import**: Imports CSV data into Neo4j with Cypher queries.
- **Recommendation Algorithms**: Implements PageRank to derive product recommendations.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ronak021/Graph-based-Recommendation-System.git
   cd Graph-based-Recommendation-System
   ```

2. **Generate and Import Data**:
   - Run the Python script to create CSV files for users, products, and interactions.
   - Import CSV files into Neo4j with the provided Cypher queries.

3. **Run Neo4j Queries**:
   - Start the Neo4j database and execute the recommendation queries to retrieve product suggestions.

## Requirements
- **Neo4j**
- **Python**
