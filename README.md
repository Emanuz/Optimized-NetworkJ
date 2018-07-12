# Optimized-NetworkJ- Research project 3
Optimised NetworkJ is a Python package for the creation, manipulation, study of the structure, dynamics, and functionalities of complex networks.

Documentation
Optimized networ is under development will update it has soo as its finished.

Download


Usage
-----

A quick example that finds the shortest path between two nodes in an undirected graph::

   >>> import networkx as nx
   >>> G = nx.Graph()
   >>> G.add_edge('A', 'B', weight=4)
   >>> G.add_edge('B', 'D', weight=2)
   >>> G.add_edge('A', 'C', weight=3)
   >>> G.add_edge('C', 'D', weight=4)
   >>> nx.shortest_path(G, 'A', 'D', weight='weight')
   ['A', 'B', 'D']


Bugs
----



License
-------

Distributed with a BSD license; see LICENSE.txt::

   Copyright (C) 2004-2016 Optimized Network Developers
   Emmanuel M Nimurungi <codemauz at gmail dot com>

