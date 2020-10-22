# Uninformed_Search

1. Depth First Search(heavy time usage)
2. Breadth First Search (heavy memory usage)
3. Iterative Deepening (a balanced approache between DFS and BFS, where we get space advantage of DFS built into BFS) Run DFS with depth limit 1, if no solution.. run DFS with depth limit 2. rinse and repeat
4. Uniform Cost Search: Search based on a cost parameter associated with distance between each node, the path with least cumulative distance will be selected
