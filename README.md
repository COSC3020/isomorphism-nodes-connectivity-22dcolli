# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Plagarism Statement

All exercises must contain the following statement:
“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”

## Note
I did not complete this excersise last semester, so I am attempting this completely from scratch.

## Answer

When a graph is completely conected, that means that every node has a connection to every other node in the graph. This is the key to two graphs with the same number of nodes that are completely always being isomorphic. To elaborate, if there are the same number of nodes in each graph, and in both graphs each node has a connection to every other node, then that means in both graphs the number of connections will always be the same in both graphs as long as the number of nodes are the same. But that is only a part of it, for example, if we had two graphs, A and B, that each had 4 nodes and were completely connected, then no matter where we started mapping the two graphs onto each other,that is to say, that no matter which arbitrary node you decide to map to any of the other graph's arbitrary nodes as a start, as long as they are both completely connected and have the same number of nodes each. Then the adjacencies for the chosen nodes will match the other graphs chosen nodes, showing that for any chosen node in one graph when compared to the chosen node in the other, will have the same number of connections to the same number of nodes. This is not saying that all nodes in one graph will be mapped to a single node in the other graph, but rather that the choice of nodes to start with(one node in the first graph and one in the second) when checking for isomorphism does not matter in this instance.
 

