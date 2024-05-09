[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Assume that A and B are isomporphic and have differing numbers of nodes.

Per our definition of isomorphism, $f: V_A \rightarrow V_B$ is a bijection between A and B.

Since f is a bijection, each node of A must map to a unique node in B


For purposes of explanation, let's say that A has more nodes than B.

There must be a node in A that is not mapped to B


Therefore, we have a contradiction, proving the initial claim to be false.

This proves that two graphs $A$ and $B$ cannot be isomporphic if they have a different number of nodes.