# SNA
## Project Title:
Social Network Analysis 

## Project Description:
This project involves a comprehensive social network analysis (SNA) focused on a hypothetical scenario in the telecom industry. Utilizing a dataset representing connections (presumably customers or clients), the analysis aims to uncover key network properties and patterns that can inform marketing strategies. The project addresses a hypothetical marketing budget and targets specific groups within the network based on various network metrics.

## Data Source:
The analysis is conducted on a dataset named "connections.txt", representing a network of connections in a directed graph format. This data is crucial for understanding the structure and dynamics of the network under study.

## Methodology:
Graph Creation: A directed graph is created from the provided dataset to model the network.
Bridge Analysis: Identification of bridges in the network, which can signify critical points of connection or vulnerability within the network.
Degree Analysis: Examination of node degrees to understand the distribution of connections in the network.
Centrality Measures: Analysis of centrality metrics such as closeness, betweenness, and eigenvector centrality to identify influential nodes.
Community Detection: Employing methods like greedy modularity to detect communities within the network, which can be pivotal for targeted marketing strategies.
## Key Findings:
The analysis of bridges and centrality measures provides insights into the most influential nodes and potential key targets for marketing campaigns.
Community detection helps in understanding the clustering of nodes, which can be vital for segmenting the market and optimizing marketing efforts.
## Usage Instructions:
To run the analysis:

1. Ensure you have Python installed with libraries like networkx, matplotlib, infomap, and others as used in the notebook.
2. Load the notebook "SNA_homework4.ipynb" in a Jupyter environment.
3. Run the cells in sequence to replicate the analysis.
4. Modify the dataset or parameters as needed to fit specific scenarios or datasets.
