# Blossom Algorithm for maximum matching

This project implements the Blossom Algorithm to compute maximum matchings in general graphs, including both bipartite and non-bipartite cases. It was developed as part of a university Graph Theory course. By my professor's request, the solution incorporates a version of the Hungarian Algorithm (used for bipartite graph matching), written by a class colleague.

## Objective – efficiently solve maximum matching problems in both bipartite and general graphs using a combination of blossom contraction and the Hungarian algorithm.

## Features:
- Full implementation of Edmonds' Blossom Algorithm for general graph matching
- Integration with the Hungarian Algorith for solving bipartite matching as a special case
- Alternating tree construction with blossom detection and contraction
- Test cases including:
  - Small bipartite graph (solved with Hungarian)
  - General graph with odd-length cycles
  - Larger graph involving nested blossoms and complex augmenting paths
    
## Notes:
While the core Hungarian component was developed by a classmate, I:
- Designed and implemented the blossom contraction, augmenting path logic, and alternating forest traversal
- Integrated both algorithms under a single interface with a bipartite=True/False switch
- Added lowest common ancestor (LCA) detection and handling for blossom structures
- Structured and tested the solution on various graph configurations to ensure correctness

This project enhanced my understanding of matching theory, particularly how augmenting paths and cycle contraction enable efficient solutions to complex matching problems beyond the bipartite case.
