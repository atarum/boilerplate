---
title: test2
date: 2019-06-20
tags: ["sample", "test2"]
excerpt: test2
---
```python
a = [10, 20, 30, 40, 50]
for i in range(5):
   print(a[-i], " ")
print(" Hello")
import networkx as nx
G = nx.Graph()
G.add_nodes_from(["A","B","C","D","E","F"])
G.add_edges_from([("A","B"),("B","C"),("B","D"),("C","D"),("A","E"),("C","E"),("C","F")])
nx.draw(G, node_size=400, node_color='red', with_labels=True, font_weight='bold')
```
