# masters-thesis
This class of games, or problems, involves the interaction between two or more entities. They are pursuers and evaders focused in a strategic competition where the pursuer wants to capture or stop the other while the evader wants to avoid capture. These games have a wide range of useful applications such as military strategy, virus spreading, and autonomous robotics. As our world continues to face various large scale threats, these games are more relevant than ever. Some of the strategies could be applied to viral pandemics or fake news spreading through social media.

This thesis is on the firefighter problem, an algorithmic problem on graphs, modeling the problem of controlling the spread of a fire, a contagion or some information.

In this thesis we present the results of experiments and some theoretical results suggested by analyzing the experimental results. 

The first experiment is about the average number of vertices burned when the greedy algorithms is used. It turns out that on average very few vertices burn. On random trees of 2,000 nodes the average for 500 random trees is only 3.186. This suggests to look at the probabilities of small number of nodes. For this problem we give both experimental and theoretical results for the initial cases when the number of nodes burned is 1 or 2. The probability of a single node burning is asymptotically 0.3383219, and this follows directly from the asymptotic counting result.

The case of two nodes burning is more complicated. Here we first derive a recursive formula which gives an algorithm to compute the number of such trees exactly. Here every tree is included for which some implementation of the greedy algorithm saves two nodes. We consider the performance of two variants of the greedy algorithm, using two different tie resolution rules. We estimate the number of trees where the greedy algorithms save two nodes using random sampling, and compare these with the exact number.
