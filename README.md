# Maximum Weight Independent Set (MWIS)
Independent set means that the items in the set or not adjacents.  
A dynamic programming algorithm for computing a maximum-weight independent set of a path graph.  First an array is found where the element are MWIS of all subproblems. The n it is used in a reconstruction step to find the element in MWIS of the original problem (biggest subproblem).

This file describes the weights of the vertices in a path graph (with the weights listed in the order in which vertices appear in the path). It has the following format:  

[number_of_vertices]  
[weight of first vertex]  
[weight of second vertex]  
...
