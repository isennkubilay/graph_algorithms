## Graph Algorithms in Python

Social networks, maps, routing networks that commonly use Graph data structure today. I especially work the **shortest path** in graph, the core algorithm for mapping technologies.


I coded undirected/unweighted graph algorithm in python. My example consists of 4 node and 3 edges. In the below picture you can see visualization of **graph.py** 

![graph_example](graph_code_example.png)
undirected/unweighted graph example 

---
### BFS and DFS
Given a graph, i use the Depth-First-Search(DFS) and Breadh-First-Search algorithm to traverse the graph. I visualizated both algorithms. You can see implemented code on **traversal.py**

![bfs](bfs_graph_traversal.png)

bfs graph example 

![dfs](dfs_graph_traversal.png)

dfs graph example

---
### Topological Sort
Topological sort of Directed Acyclic Graph(DAG) is a linear ordering of the DAG's vertices in which each vertex comes before all vertices to which it has outbound edges. You can find implementation on  **topological_sort.py** 

![topo_sort](topological_sort.png)

my code result visualization --> [0,1,2,5,3,7,4,6,8]

---