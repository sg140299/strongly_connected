# strongly_connected components
1- This happens to take place only in directed graphs the word strongly.
2- The acyclic directed graph can never be strongly connected.
3- A component or graph is said to be strongly connected if and only if there exists a path from any vertex of graph or component to each
  and every vertex in that component or graph.
4- We use KOSARAJU'S ALGORITHM for this to find no of components:
   a) DO DFS on the given graph and make an ordering array in which x comes before y then there is a path from y to x in graph.
   b) Start from end of ordering array and now apply DFS on reverse edges graph of orginal one and check which edges can be visited.
   c) Make same components for the same path vertices.
5- Time complexity :
   O(n) + O(n) //for the dfs calls on both graphs. ~O(n)
   
