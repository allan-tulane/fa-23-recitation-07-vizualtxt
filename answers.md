# CMPS 2200 Recitation 10## Answers

**Name:** Ali Sulehria 


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**

  W(n) = O(n+m)

- **4)**

  The worst case number of times 'reachable' would need to be    called is O(n^2), where every node has reachable called.
  For the actual value, given that a graph has n nodes, and the graph is undirected, there are (n x n)/2 connections between pairs to be checked. 

- **5)**

  W(n) = O(n+m), just like reachable

- **7)**

  As we would need to check over each value by row, even if they are not connected, redundant or superfluous work is done. The work would be closer to the order O(n^2)