# StructuralCausalModels
A Python package implementing Structural Causal Models (SCMs). 

The package makes it possible to go from Structural Causal Models to 
Graphs. It is also possible to generate a Linear Structural Causal 
Model directly from a coefficient matrix (i.e. the weighted adjacency
matrix of the graph).

'Graph' objects are defined by giving an adjacency matrix (and a name,
optionally). They contain and maintain different representations of a
graph which can be useful depending on the circumstances, and tools to
go from any one representation to any other. 

The representations implemented at present are:

- via an adjacency matrix,
- via adjacency lists,
- via edges ("typed" edges : no edge, forward, backward or undirected 
  edge).
