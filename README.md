# ForeXplorer

## Badges

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![NetworkX](https://img.shields.io/badge/NetworkX-2.6.3-brightgreen)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue)
![Numpy](https://img.shields.io/badge/Numpy-1.21.2-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-red)

## Link to Databricks repo
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3539441013186250/3005265614522302/5848867978677713/latest.html


## Overview

Forexplorer is a project that uses Python to identify arbitrage opportunities in forex exchanges through pathfinding algorithms. It analyzes graph properties, applies centrality measures, and uses community detection algorithms such as Louvain and Girvan-Newman.

## Dataset

The dataset includes exchange rates between various currencies. It consists of columns such as `slug`, `date`, `open`, `high`, `low`, `close`, `currency`, `slug1`, and `slug2`. The data is used to build a graph where nodes represent currency names and edges represent forex rates.

## Graph Analysis

### Pathfinding Algorithms

- **Bellman-Ford Algorithm:** Detects negative cycles in the graph, indicating potential arbitrage opportunities.

### Centrality Measures

- **Degree Centrality:** Measures the number of direct connections a node has.
- **Betweenness Centrality:** Measures the extent to which a node lies on the shortest paths between other nodes.
- **Closeness Centrality:** Measures how close a node is to all other nodes in the graph.

## Community Detection

- **Louvain Algorithm:** Detects communities by optimizing modularity.
- **Girvan-Newman Algorithm:** Identifies communities by removing edges and analyzing the resulting component structure.

# Forexplorer: Arbitrage Detection in Forex Exchanges

## Usage

1. **Load Data:** Import the forex exchange data into your Python environment.
2. **Run Analysis:** Use the provided Python scripts to perform graph analysis, detect arbitrage opportunities, and apply community detection algorithms.
3. **Visualize Results:** Generate and interpret visualizations for detected arbitrage opportunities and community structures.

## Results and Conclusion

This project evaluates the performance of pathfinding algorithms for arbitrage detection in forex exchanges and analyzes the resulting graph properties and community structures. The findings highlight potential arbitrage opportunities and provide insights into the network of forex exchanges.

## Acknowledgements
A big thank you to the developers of NetworkX, Pandas, Matplotlib, and other tools included in this.

