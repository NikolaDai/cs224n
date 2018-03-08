#notes on PPT
1. AI-complete is a term, please refer to https://en.wikipedia.org/wiki/AI-complete for more details. In a word, AI-complete is used to define the most difficult problems in AI field.
2. questions to answer?
* What is Natural Language Processing?
* how many and what parts do NLP Levels cover?
* What is special about human language?
* What is Deep Learning?
* Why is NLP hard?

#notes on linear algebra
we strongly recomment two online videos, one from MIT and the other from https://www.bilibili.com/video/av9406644/ and the other is https://www.bilibili.com/video/av6081149 .
1. always have equations in mind, linear algebra in nature is a compact of linear equations $Ax = B$.
2. the usage of outer product to compact A whose columns are all equal to some vector $x \in R^n$
3. amazing! any matrix could be composed of a symetric and a anti-symetric matrices.
4. A norm of a vector ||x|| is informally a measure of the "length" of the vector.
5. the definition of the projection of one vector.one more words on this last equation, it is closely related to principle components analysis (PCA). we should put more attention to understand.
\[
Proj(y;{x_1,...,x_n}) = argmin_{v\in span(\{x_1,...,x_n\})}||y-v||_2
\]
6. The span of a $set$ of vectors ${x_1,x_2,...,x_n}$ is the set of vectors that can be expressed as a linear combination of ${x_1,x_2,...,x_n}$.

#notes on probability
1. multiple random variables' probability is a must to know, for example, the chain rule and independence.

#notes on convex opitimization
1. $\it convex\ set:$ A set C is convex if, for any x,y $\in$ C and $\theta \in R$ with $0\leq \theta \leq 1$, $\theta x + (1-\theta)y \in C$.
2. $\bf Affine\ subspaces\ and\ polyhedra.$
3. A central element in convex optimization is the notion of convex function.
4. to prove $x \in C$ is equal to {$g_i(x) \le 0, i=1,...,m;   h_i(x) = 0, i = 1, ..., p$}

#notes on lec 01
1. to do the gradient of $J(\theta)$
