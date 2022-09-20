# HelloLsner
## HelloLsner
#### Exercise 2.1.  Proof of Lemma 1.8

Since A is at most countable, it is either finite or countable. 

When A is finite, it can be enumerated as {$x_{1}, x_{2}, x_{3}...x_{m}$}, then A* = {$\epsilon, x_{1}, x_{2}...x_{m},x_{1}x_{1},x_{1}x_{2}...$}. Obviously, before duplicate removal, there exists an injective function $\alpha$ from N onto A*: 

$\alpha: N \rightarrow A* $

​       n $\rightarrow x_{i_{1}}x_{i_{2}}...x_{i_{j}}$, $\sum_{k=1}^{j-1}m^{k}\le n\le\sum_{k=1}^{j}m^{k}$
$$
\epsilon
\\x_{1}, x_{2}, x_{3}...x_{m}
\\x_{1}x_{1},x_{1}x_{2}...x_{1}x_{m},x_{2}x_{1}...x_{m}x_{m}
\\x_{1}x_{1}x_{1}......
\\......
$$
Finally, A* is proved to be countable.

When A is infinite but countable, there exists an injective function $\alpha$ from N to A:

$\alpha: N \rightarrow A $

​       n $\rightarrow\alpha(n)$ 

Then we assume that $\epsilon = x_{0}$. Next, let the sum of subscripts of $x_{i_{1}}x_{i_{2}}...x_{i_{j}}$ Increase from zero. Just as follows.
$$
x_{0}
\\x_{1}
\\x_{1}x_{1}, x_{2}
\\x_{1}x_{1}x_{1}, x_{1}x_{2}, x_{2}x_{1}, x_{3}
\\......
$$
In summary, A* is proved to be countable.



#### Exercise 2.2. 

Obviously, there exists a bijective function from M to some elements of pow(M). 

$\alpha: M\rightarrow A = \begin{Bmatrix}B\in pow(M)|x\in M, x\notin B, B\bigcup\begin{Bmatrix}x\end{Bmatrix}=M\end{Bmatrix}$

$\quad \quad x\rightarrow M$\\{x}

Then we find that the left elements in pow(M) wil not be corresponded, which means there is no surjective function from M to Pow(M). Actually, the cardinality of M is less than the cardinality of pow(M).
