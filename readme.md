
# HeteroGraphNet: Advancing Cell Type Prediction in scRNA-seq with Enhanced Graph Neural Networks for Heterophilic Structures
Authors: Mahshad Hashemi, Sharjeel Mustafa, Alioune Ngom and Luis Rueda

## Introduction
Graph Neural Networks (GNNs) are a new type of neural network that operates on complex interconnected data for various tasks such as node prediction. These approaches benefit from using the relationships of nodes to make holistic predictions, for example, using the neighbours and connections of a cell for type prediction.

Utilizing interconnected data is particularly advantageous in computational biology, where the interactions encode important information. However, such data often exhibits heterophily (i.e., dissimilar nodes are connected), which most current GNNs do not account for. 

To this end, we propose HeteroGraphNet, a novel GNN approach that employs random walks and a gated design for efficient node prediction in heterophilic data.


## Dependences
```
Tested on:
Python          3.10.12
PyTorch         2.5.1+cu121
NetworkX        3.4.2
NumPy           1.26.4
Pandas          2.2.2
Scikit-Learn    1.5.2
```