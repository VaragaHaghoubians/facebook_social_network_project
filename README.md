# 🕸️ Facebook Social Circles — Complex Network Analysis

> Graph-theoretic analysis of the Facebook combined social network dataset,
> covering topology, centrality, community structure, and node influence.

---

## 🎯 Problem

Large social networks have hidden structure — some users are far more influential
than others, and groups of users cluster into communities that aren't visible from
raw data alone. This project applies **complex network analysis** to the Facebook
Social Circles dataset to uncover that structure.

---

## 🔍 What's Analyzed

### 1. 📐 Basic Network Topology
- Number of nodes and edges
- Average degree, variance, standard deviation
- **Degree distribution** — visualised as histogram

### 2. 🔗 Connectivity
- **Clustering coefficient** per node + average across the network
- **Largest connected component** size
- Average shortest path lengths

### 3. 🔄 Degree Correlation
- **Assortativity coefficient** — whether high-degree nodes connect to other
  high-degree nodes (assortative) or to low-degree ones (disassortative)

### 4. 👥 Community Detection
- **Label Propagation algorithm** to detect communities
- Number of communities identified and their size distribution

### 5. 🎯 Centrality Measures
Top 10 nodes ranked by four centrality metrics:
- **Degree centrality** — how many connections a node has
- **Betweenness centrality** — how often a node lies on shortest paths
- **Closeness centrality** — how quickly a node can reach all others
- **Eigenvector centrality** — influence based on neighbour quality

---

## 📁 Project Structure

```
facebook_social_network_project/
│
├── facebook_social_network_project/
│   ├── complex_network_codes_Varaga_Haghoubians.ipynb  ← main notebook
│   └── Complex_Network_Project__Varaga_Haghoubians.pdf ← full written report
└── README.md
```

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-2.x-blue?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Methods:** Graph Construction · Degree Distribution · Clustering Coefficient · Label Propagation · Degree / Betweenness / Closeness / Eigenvector Centrality · PCA Visualisation · Assortativity Analysis

---

## 🚀 How to Run

```bash
git clone https://github.com/VaragaHaghoubians/facebook_social_network_project.git
cd facebook_social_network_project
pip install networkx pandas numpy matplotlib scipy
jupyter notebook
```

Open `complex_network_codes_Varaga_Haghoubians.ipynb` and run all cells.

> **Dataset:** Facebook Social Circles — available from
> [SNAP (Stanford Network Analysis Project)](https://snap.stanford.edu/data/ego-Facebook.html).
> Download `facebook_combined.txt.gz` and update the `file_path` variable in the notebook.

---

## 👤 Author

**Varaga Haghoubians** — Junior ML/AI Engineer & Data Analyst
[LinkedIn](https://www.linkedin.com/in/varagahaghoubians) · [GitHub](https://github.com/VaragaHaghoubians) · [varaga.haghoubians@gmail.com](mailto:varaga.haghoubians@gmail.com)
