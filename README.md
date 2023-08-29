# Graph Colouring problem
 ## Automaton-Based approach for solving optimization problem such as graph colouring

 In the case of graph coloring, the goal is to assign a color to each node in a graph such that no adjacent nodes share the same color. This is an NP-hard problem, meaning that finding an exact solution is computationally intractable for large graphs. 
 An automaton-based approach can be used to find an approximate solution to this problem by iteratively modifying a candidate coloring and accepting or rejecting the new coloring based on a probability determined by the Metropolis-Hastings algorithm.