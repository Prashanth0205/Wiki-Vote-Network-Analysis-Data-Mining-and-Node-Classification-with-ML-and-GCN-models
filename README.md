# Wiki Vote Network Analysis Data Mining and Node Classification with ML and GCN models

This project conducts an in-depth analysis of the Wiki Vote network dataset, first employing data mining techniques to extract key information and identify community structures. Subsequently, machine learning algorithms and a Graph Convolutional Network (GCN) model are applied for node classification tasks, aiming to gain insights into network topology and effective classification methods.

## Part 1: Data Mining and Network Analysis Preparation

1. Data Loading: Loading the Wiki Vote network dataset to construct a directed graph representing the network, with nodes as individuals and edges as directed votes.
2. Administrative Data Parsing: Parsing administrative data to extract information such as user IDs, timestamps, and voting records.
3. Community Detection: Identifying communities within the network using Louvain and label propagation algorithms.
4. Data Visualization: Visualizing the network graph to understand its structure and connections.
5. Centrality Measures Calculation: Computing centrality measures to determine the importance of nodes in the network.
6. Statistical Analysis: Analyzing centrality measures and community structures to identify key nodes and patterns within the network.

## Part 2: Machine Learning-based Classification

1. Data Preprocessing: Preparing feature matrix and label vector for classification tasks based on node attributes and network structure.
2. Classification Algorithms: Implementing various classification algorithms such as KNN, SVM, Random Forest, and GBM for node classification tasks.
3. Model Training: Training classification models to classify nodes into categories based on their attributes and network interactions.
4. Model Evaluation: Evaluating trained models to assess their accuracy and performance in node classification tasks.
5. Graph Convolutional Network (GCN) Implementation: Implementing GCN for node classification leveraging both node features and network structure.
6. Training and Evaluation of GCN: Training and evaluating the GCN model's performance in classifying nodes within the Wiki Vote network dataset.
