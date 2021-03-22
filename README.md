# ai-classical-planning

In thiss project, we will implement a planning graph, which is a special
data structure that is optimized to search for the solutions for a PDDL.

A planning graph is a directed graph organized into levels: the first  
level S0 is the initial state, consisting of nodes representing each  
fluent; then the first level A0 consisting of nodes for each possible  
action from the states in S0; followed by the alternating levels of Si  
and Ai until we reach a termination condition. A planning graph  
terminates when two consecutive levels are identical. At this point, we  
say that the graph has leveled off.

The planning graph is a robust data structure to solve a planning problem.  
If a solution is not found by the end of the planning graph layer, the  
problem is considered unsolvable.

This project is split between implementation and analysis. First it will  
combine symbolic logic and classical search to implement an agent that  
performs progression search to solve planning problems. Then it will  
experiment with different search algorithms and heuristics, and use the  
results to answer questions about designing planning systems.

