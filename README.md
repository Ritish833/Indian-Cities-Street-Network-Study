## 📂 Repository Structure & Notebook Pipeline
```

```
| Notebook | Stage | Description |
```

```
| :--- | :--- | :--- |
```

```
| `1_Extracting_graphml_cities.ipynb` | **Data Extraction** | Extracts empirical
street networks for 33 Indian cities from OpenStreetMap (OSM) as `.graphml`
files, filtering out self-loops during pre-processing. |
```

```
| `2_city_config_random.ipynb` | **Null Models & Topology** | Generates
spatially embedded random networks (preserving node coordinates) and
configuration models (preserving both node degree sequences and spatial
positions) to benchmark network efficiency and clustering coefficients against
empirical networks. |
```

```
| `4_Cities_robustness_random.ipynb` | **Random Percolation** | Evaluates
network robustness under random failures by iteratively removing edges at random
and tracking network fragmentation via the number of connected components
(subgraphs) at each step. |
```

```
| `5_Cities_robustness_target.ipynb` | **Targeted Attack** | Evaluates network
robustness under targeted attacks by iteratively removing edges in descending
order of their edge betweenness centrality and measuring the resulting subgraph
fragmentation. |
```

