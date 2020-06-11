## BREEDS: Benchmarks for Subpopulation Shift

This repository contains the modified ImageNet class hierarchy used for the paper, as well as a notebook for creating the relevant BREEDS datasets. As discussed in the paper, we obtain the class hierarchy by modifying [WordNet](https://wordnet.princeton.edu/).

Files:

- `class_hierarchy.txt`: Each line indicates an edge from a parent to a child node (via their IDs). 
- `node_names.txt`: Mapping from node ID to node name. (Modified from the original [WordNet](https://wordnet.princeton.edu/) naming to incorporate dummy nodes and node grouping.)
- `hierarchy.ipynb`: Jupyter notebook containing code to load and parse the hierarchy, as well as create all the superclasses used in the paper, along with the specific source-target splits we use for our BREEDS tasks.
