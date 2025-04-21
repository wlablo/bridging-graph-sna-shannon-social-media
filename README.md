
# Bridging Graph Theory, Social Network Analysis, and Shannon's Information Theory in the Era of Social Media

This repository contains code, data, and visualizations accompanying the study:
**"Bridging Graph Theory, Social Network Analysis, and Shannon's Information Theory in the Era of Social Media"**.

The framework integrates network science techniques—including community detection, centrality analysis, entropy measurement, and communicability heatmaps—to model and interpret structural and informational dynamics in social media networks.

## Features

- Community detection using Louvain and Infomap algorithms  
- Centrality measures (degree, betweenness, closeness)  
- Graph entropy and information gain calculations  
- Node redundancy and communicability heatmaps  
- Synthetic social network generator  
- Ready for extension to real-world data (e.g., Twitter, Reddit)

## File Structure

```
├── data/
│   ├── dane1.csv
│   └── polaczenia1.csv
├── scripts/
│   └── network_analysis.py
├── figures/
│   ├── degree_centrality.png
│   ├── entropy_plot.png
│   └── louvain_communities.png
├── results/
│   └── topological_metrics_summary.csv
└── README.md
```

## Installation

Make sure you have Python 3.8+ installed.  
Install the dependencies:

```bash
pip install networkx matplotlib pandas python-louvain infomap
```

## Running the Analysis

```bash
python scripts/network_analysis.py
```

Or open the notebook:

```bash
jupyter notebook social_network_analysis.ipynb
```

## License

This project is licensed under the MIT License.

## Contact

Questions? Contact the authors via [wlablo@wp.pl]
