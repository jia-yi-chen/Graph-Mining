# Graph Mining

Python implementation for some algorithms in Graph Mining and Recommendation by [Jiayi Chen](https://github.com/jia-yi-chen), including the following topics


* **Network**:
  - Scrabing Data
  - Network Construbtion and measurement (e.g., Pagerank, clustering coefficient, ...) 
* **Recommendation**: 
  - User-based Collaborative Filtering
  - Item-based Collaborative Filtering
* **Community Detection**: 
  - Spectral clustering algorithm
  - Modularity maximization algorithm


## Requirements

* python 3
* networkx
* pandas

## Getting Started

### Scrabing Data & Network Construbtion & Measurement
```
run "/graph_scraping_construction_measurement/main.py"
```
### Collaborative Filtering
```
run "/collaborative_filtering/main.py"
```
* User-based collaborative filtering: "/collaborative_filtering/user_based_CF.py"
* Item-based collaborative filtering: "/collaborative_filtering/item_based_CF.py"

### Community Detection

Community number is set to k=2.

```
run "/community_detection/main.py"
```
* Spectral clustering:  /community_detection/spectral_clustering.py
* modularity maximization:  /community_detection/modularity_maximization.py
* Result example:
 ![image](https://github.com/jia-yi-chen/Graph-Mining/tree/main/community_detection/figs/spectralresult.jpg)
 ![image](https://github.com/jia-yi-chen/Graph-Mining/tree/main/community_detection/figs/modularityresult.jpg)


