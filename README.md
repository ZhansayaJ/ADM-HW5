# ADM-HW5

### This is the repository dedicated to Homework 5 for ADM course. 
#### Group 30 - Zhansaya Jumasheva.

- [__`main.ipynb`__]( ): - contains answers to Question 1 and functionalities 1 and 2 in Questions 2 and 3.

# Project Description

This Python project focuses on analyzing a dataset containing information about a group of papers and their citation relationships. The project is divided into two main parts: graph setup and controlling system implementation.

## 1. Data

### Graphs Setup
Based on the available data, two graphs are created to model relationships:

- Citation graph: Represents paper citation relationships. It is unweighted and directed.
- Collaboration graph: Represents author collaborations. It is weighted and undirected.

### Data Pre-processing
Due to the large dataset size, focus is placed on a subgraph, specifically the top 10,000 papers with the highest number of citations. The nodes of the graphs are defined as follows:

- Citation graph: Each paper is considered a node.
- Collaboration graph: Authors of the top 10,000 papers are nodes.

Edges are constructed based on citation relationships and collaborations between authors of the selected papers.

## 2. Controlling System

### 2.1 Backend Implementation

#### Functionality 1 - Graph's Features
This function examines a graph and reports on its features, including the number of nodes, number of edges, graph density, degree distribution, average degree, graph hubs, and whether the graph is dense or sparse.

#### Functionality 2 - Nodes' Contribution
Using various centrality measurements, this functionality identifies papers/authors who significantly contribute to the field of study. Centrality measurements include Betweenness, PageRank, ClosenessCentrality, and DegreeCentrality.

### 2.2 Frontend Implementation

#### Visualization 1 - Visualize Graph Features
This visualization presents the Functionality 1 report, including general graph information, a list of graph hubs, and plots depicting the distribution of citations received and given by papers, as well as the number of collaborations of authors.

#### Visualization 2 - Visualize Node's Contribution
This visualization presents the Functionality 2 report, including centrality values based on four centrality measurements for each node.

## Conclusion

This project aims to analyze paper citation relationships and author collaborations using graph-based techniques and centrality measurements. By examining graph features and node contributions, the project provides insights into the structure of the academic network and identifies key papers/authors in the field of study.
