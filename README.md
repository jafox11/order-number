# Acyclic Orderings in Directed Acyclic Graphs

A _directed graph_ is a graph in which each edge points in an indicated direction.  A directed graph is _acyclic_ when there is no directed edge path that begins and ends at the same vertex.  An example is the network of U.S. Supreme Court decisions, where an edge points from Decision A to Decision B when A is used as a precedent for B.  Another example is the network of theorems in a mathematics paper, where an edge points from Theorem A to Theorem B when the proof for B cites A.

An _acyclic ordering_ of a directed acyclic graph (DAG) $G$ is an ordering of the vertices in which a vertex $w$ cannot precede a vertex $v$ if there is a directed path from $v$ to $w$.  A given DAG has many possible acyclic orderings, and the problem of counting them all is, in general, #P-complete.  This project deals with counting acyclic orderings for certain special types of DAGs, including trees.

## Files Included

The pdf file included in this repository contains our results and was published in _Journal of Combinatorial Mathematics and Combinatorial Computing_, volume 115 (2020), pages 271-286.

The Jupyter Notebook contains a series of Python scripts that automate some of the formulas in the paper.  It culminates with the main result in the paper, the formula in Theorem 5.2.
