---
title: "Tree Recognition and Graph Edge Minimization from Anchored Distance Comparisons"
collection: publications
category: manuscripts
status: "Preprint"
year: 2026
order: 2
authors: "Chongkun Deng"
permalink: /publication/ordinal-recognition-positive-tree-metrics
paperurl: "/files/Tree-Recognition-and-Graph-Edge-Minimization.pdf"
pdfurl: "/files/Tree-Recognition-and-Graph-Edge-Minimization.pdf"
# codeurl: "https://github.com/..."
citation: 'Chongkun Deng. (2026). &quot;Tree Recognition and Graph Edge Minimization from Anchored Distance Comparisons.&quot; Preprint.'
excerpt: >-
  A study of realizing anchored comparisons of the form d(o,x) &lt; d(o,y)
  with positively weighted trees and general graphs, including quadratic-time
  tree recognition, a sparse linear-programming test for edge weights, and
  sharp extremal results for graph realizations.
---

**Status:** Preprint  
**Author:** Chongkun Deng  
**Date:** September 2026

[Download the preprint]({{ '/files/Tree-Recognition-and-Graph-Edge-Minimization.pdf' | relative_url }})

This paper asks when a collection of **anchored distance comparisons** of the form \(d(o,x)<d(o,y)\) can be represented by shortest-path distances in a positively weighted tree whose vertex set is exactly the set of observed objects. It gives two quadratic-time ways to construct the candidate tree edge set: the half-space proximity (HSP) graph and a minimum spanning tree of any compatible metric. Whenever a tree realization exists, both constructions recover its edges.

After the topology is recovered, a separate sparse linear program decides whether positive edge weights can realize every comparison. In root-distance variables, each comparison uses at most four nonzero coefficients; feasible instances admit bounded integer weights, while infeasible instances have small certificates. The paper also identifies an additive-triple property that every compatible metric must obey when a tree realization exists.

The general-graph problem behaves differently: edges that can each be omitted separately need not be omissible together. The paper gives the smallest such example on five vertices, proves a linear gap between individually forced edges and the minimum number needed jointly, establishes the sharp worst-case minimum of \(\binom{n}{2}-1\) edges, and gives a seven-vertex example showing that maximizing additive triples can require more edges than minimizing edge count. Determining the complexity of minimum-edge realization for general graphs remains open.
