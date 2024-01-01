

# Introduction
  

This repository contains code and data for my article "[Graph or Grove? Ecosystem Services Valuation with Graph Machine Learning and Random Forest](https://medium.com/@dgg32/graph-or-grove-ecosystem-services-valuation-with-graph-machine-learning-and-random-forest-31d92f686396)". 

1. The Python ipynb scripts are for the data import and machine learning.

  

# Prerequisite

Neo4j Desktop or AuraDB

GDS

Sklearn

# Run
1. Prepare data as described in "[Graph or Grove? Ecosystem Services Valuation with Graph Machine Learning and Random Forest](https://medium.com/@dgg32/graph-or-grove-ecosystem-services-valuation-with-graph-machine-learning-and-random-forest-31d92f686396)". 
  
2. Install the necessary Python libraries

3. Run random_forest.ipynb to build Sklearn random forest model as the benchmark

4. Run graph_data_preparation.ipynb to prepare the data for Neo4j

5. Import the data into Neo4j with neo4j_command.txt

6. Run the various graph machine learning algorithms with gds_fastrp.ipynb, gds_graphsage.ipynb, gds_hashgnn.ipynb, and gds_node2vec.ipynb. Their Cypher codes are also provided in the txt files.


## Authors

  

*  **Sixing Huang** - *Concept and Coding*

  

## License

  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
