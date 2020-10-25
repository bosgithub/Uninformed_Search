# Uninformed_Search

1. Depth First Search(heavy time usage)
2. Breadth First Search (heavy memory usage)
3. Iterative Deepening (a balanced approache between DFS and BFS, where we get space advantage of DFS built into BFS) Run DFS with depth limit 1, if no solution.. run DFS with depth limit 2. rinse and repeat
4. Uniform Cost Search: Search based on a cost parameter associated with a cost measure(distance) between each node, the path with the least cumulative distance will be selected. This is relatively more time consuming as we expand "radially" in all directions, but this guarantees the optiaml solution.
5. Heuristic Search: Search based on a heuristic measure, for example, a search problem to find the path with least distance from home to school, the euclidean or mahhantan disntance could be used as a heuristic measure, where along the path, intermediate stops with the least heuristic measure is expanded for further exploration(example: greedy search) this doesn't garantee optimal solution, one can easily end up in a rabbit hole(local optimum).
6. A Star search: A balanced approach that combines the heuristic measure at each node relative to goal state, as well as the cost measure to traverse between nodes. 
