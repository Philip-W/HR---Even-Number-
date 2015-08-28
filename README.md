# HR---Even-Number-
A solution to the Hacker Rank problem Even Number under Algorithms/Graph Theory.
Mainly making this as a test for GitHub, might add more interesting problems if I find them on HackerRank.

Problem: An even connected tree is given, highest possible number of edges are to be removed in order to create 
         the greatest number of EVEN trees.

Solution works by working back to from on the list of nodes 1 - N, it counts the number of children each vertex has, if the number of children is even, you can remove the edge from the vertex to the parent of that vertex.
I believe there is an issue with the way it process though, it assumes a child vertex will always have a parent of lower value label, since the algorithm didn't work iterating through 2 - N, however it works running N - 2.
