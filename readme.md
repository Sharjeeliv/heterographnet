
# HeteroGraphNet: Advancing Cell Type Prediction in scRNA-seq with Enhanced Graph Neural Networks for Heterophilic Structures
Authors: Mahshad Hashemi, Sharjeel Mustafa, Alioune Ngom and Luis Rueda

## Introduction
Graph Neural Networks (GNNs) are a new type of neural networks that operated on complex interconnected data for various tasks such as node prediction. Such appraoches benefit from using the relationships of a data entity to make holisitc predictions, for example using the neighbours and connections of a cell for type prediction.

The abilitiy to utilize interconnected data is particularly advantages in the field of computational biology where the interactions encode important information. However, such data often exhibits heterophily (i.e., that dissimilar nodes are connected) which most current GNNs do not account for. 

To this end we propose HeteroGraphNet, a novel GNN approach that employes randomg walks and a gated design for efficient node prediction in heterophilious data.


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