When we look at input sizes large enough to make only the order of growth of the running time relevant, we are studying the **asymptotic efficiency og algorithms**: we are concerned with how the running time of an algorithm increases with the size of the input in the limit, as the size of the input increases without bound. **Usually an algorithm that is asymptotically more efficient will be the best choice for all but very small inputs**.
# 3.1 Asymptotic notation
## $\mathcal{\theta}$-Notation
For a given functions $g(n)$, we denote by $\theta(g(n))$ the set of functions $\theta(g(n))=\{f(n): \text{There exists positive contents } c_{1}, c_{2} \text{ and } n_{0} \text{ such that } 0 \leq c_{1}g(n) \leq f(n) \leq c_{2}g(n) \text{ for all } n \geq n_0\}$
**sanwiched** between $c_{1}g(n)$ and $c_{2}g(n)$ for sufficiently large $n$ 

![[Pasted image 20240710020739.png]]
For Figure (a), $f(n) = \theta(g(n))$: for all values of $n$ at and to the right of $n_0$, the value of $f(n)$ lies at or above $c_{1}g(n)$ and at or below $c_{2}g(n)$. **We say that $g(n)$ is an asymptotically tight bound for $f(n)$**
In general, for any polynomial $p(n)=\sum_{i=0}^{d} a_{i}n^{i}$, where the $a_i$ are constants and $a_{d} \gt 0$, $p(n)=\theta(n^d)$


