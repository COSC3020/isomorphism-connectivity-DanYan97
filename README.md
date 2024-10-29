# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

A complete graph is a graph with n vertices and every pair of vertices is connected by an edge.

Suppose there are two non-complete graphs $G_1$ contains vertices $V_1=[v_1,v_2,v_3]$ and edges $E_1=[(v_1,v_2),(v_2,v_3)]$ and $G_2$ contains vertices $V_2=[w_1,w_2,w_3]$ and edges $E_2=[(w_1,w_2),(w_2,w_3)]$. 

The bijection function $f: V_1 \rightarrow V_2$ can be defined as: $f(v_1)=w_1$, $f(v_2)=w_2$, $f(v_2)=w_2$

Therefore:

$(v_1,v_2)\in E_1$ maps to $(w_1,w_2)\in E_2$

$(v_2,v_3)\in E_1$ maps to $(w_2,w_3)\in E_2$

This indicated that $G_1$ and $G_2$ are isomorphic, but neither $G_1$ and $G_2$ are complete graphs becuase in $G_1$, $v_1$ and $v_3$ are not connected by an edge, and in  $G_2$, $w_1$ and $w_3$ are not connected by an edge as well.

Therefore, this counter example proved that two graphs can be isomorphic without being an complete graph.

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.” --Doris Yan
