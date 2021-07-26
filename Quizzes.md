# Quizzes

## Quiz 2.1

For sets $A$ and $B$, recall that $A\setminus B= \{a\in A: a \notin B\}$. Which of the following always equals $A\setminus (A \setminus B)$?

1. $A$
2. $B$
3. $A \cap B$
4. $A\cup B$

## Quiz 2.2

Let $X=\{1, 2\}$. What is the number of collections of subsets $\Omega\subset X$ that form a topology on $X$?

## Quiz 3.1

Let $X$ be a space with discrete topology and $B$ a collection of subsets of $X$. Which of the following is true.

1. If $B$ is a basis, then every singleton set $\{x\}$ with $x\in X$ is in $B$
2. If every singleton set $\{x\}$ with $x\in X$ is in $B$ then $B$ is a basis.

## Quiz 3.2

Which of the following form a basis for some topology on $\mathbb{R}^2$?

1. All discs centred at the origin.
2. All discs centred at some point $(x, 0)$ on the $x$-axis.
3. All discs centred at some point $(n,m)$ with $n, m\in\mathbb{Z}$.

## Quiz 4.1

For each of the following functions $d: \mathbb{R}\times\mathbb{R}\to\mathbb{R}$, determine whether $d$ is a metric.

1. $d(x, y) = (x - y)^2$.
2. $d(x, y) = \left|x - y\right|^{1/2}$.

## Quiz 4.2

For each of the following functions $d: \mathbb{R^2}\times\mathbb{R^2}\to\mathbb{R}$, determine whether $d$ is a metric.

1. $d((x_1, y_1), (x_2, y_2)) = (x_1 - x_2)^2$.
2. $d((x_1, y_1), (x_2, y_2)) = \min(\left|x_1 - x_2\right|, \left|y_1 - y_2\right|)$.

## Quiz 5.1

Let $X$ be a metric space, $x, y\in X$ points and $A\subset X$ a subset. Determine whether the following statements must be true.

1. $d(A, y) \leq d(A, x) + d(x, y)$.
2. $d(x, y) \leq d(A, x) + d(A, y)$.

## Quiz 5.2

Suppose we consider the Hausdorff distance on all bounded sets (i.e., not necessarily closed). Which of the following properties must be true?

1. $d_H(A, B) = 0$ if and only if $A= B$.
2. $d_H(A, B) = d_H(B, A)$.
3. $d_H(A, C)\leq d_H(A, B) + d_H(B, C)$.

## Quiz 5.3

Let $A$ be the subset of the Cantor set consisting of sequences $\{a_n\}$ such that  $a_n= 0$ for all but finitely many $n$. Determine whether the following are true of $A$.

1. $A$ is open in $X$.
2. $A$ is closed in $X$.
3. $A$ intersects every open set in $X$.

## Quiz 6.1

Determine which of the following are true.

1. A subspace of a space with discrete topology has discrete topology.
2. A subspace of a space with indiscrete topology has indiscrete topology.
3. A subspace of a space with cofinite topology has cofinite topology.


## Quiz 6.2

The interior of the set $\mathbb{Z}\subset\mathbb{R}$ is

1. $\mathbb{Z}$.
2. $\mathbb{R}$.
3. the empty set.

## Quiz 7.1

Let $f: X\to Y$ be a function and $A, B\subset X$. Which of the following is true.

1. $f(A\cup B)\subset f(A)\cup f(B)$.
2. $f(A\cup B)\supset f(A)\cup f(B)$.
3. $f(A\cap B)\subset f(A)\cap f(B)$.
4. $f(A\cap B)\supset f(A)\cap f(B)$.

## Quiz 7.2

Let $(X, d_X)$ and $(Y, d_Y)$ be metric spaces. A map $f: X\to Y$ is said to be Lipschitz if there exists a constant $K> 0$ such that for $$\forall p, q\in X,\ d_Y(f(p), f(q)) \leq K d_X(p, q).$$

Determine whether the following are true?

1. Every Lipschitz map is continuous.
2. Every continuous map is Lipschitz.

## Quiz 8.1

Suppose $f: X\to Y$ is a map between topological spaces and $A\subset X$ is a subspace. Determine whether the following are true.

1. If the restriction $f\vert_A: A \to Y$ is continuous, then for all $x\in A$, $f$ is continuous at $x$.
2. If, for all $x\in A$, $f$ is continuous at $x$, the restriction $f\vert_A: A \to Y$ is continuous.

## Quiz 8.2

Let $X$ be a space with the discrete topology. Determine whether the following statements are true.

1. If $x\in X$, then any neighbourhood basis of $x$ contains the singleton set $\{x\}$.
2. Every point has a neighbourhood basis with just one open set.

## Quiz 8.3

Let $f, g: X\to \mathbb{R}$ be continuous functions from a topological space to the reals. Which of the following must be continuous?

1. $\min(f, g)$
2. $\max(f, g)$
3. $\vert f\vert - \vert g\vert$

## Quiz 9.1

Let $X$ be a set. What is the initial topology on $X$ so that all functions $f: X \to \{0, 1\}$ is continuous?

1. Discrete
2. Indiscrete
3. Cofinite

## Quiz 9.2

Determine which of the following are true.

1. Every isometric embedding is continuous.
2. The composition of isometric embeddings is an isometric embedding.

## Quiz 10.1

Determine whether there is a continuous bijection from $X$ to $Y$ for the following pairs of spaces.

1. $X=\mathbb{R}$ and $Y=S^1$.
2. $X=(0, 1]$ and $Y= S^1$.
3. $X = (0, 1)\cup [2, 3)$ and $Y= (1, 2)$.

## Quiz 10.2

Determine whether the following spaces are homeomorphic to $\mathbb{R^2}$.

1. $\{(x, y)\in \mathbb{R^2}: x^2 + 2y^2 < 1 \}$
2. $\{(x, y)\in \mathbb{R^2}: x^2 - 2y^2 < 1 \}$

## Quiz 11.1

Given spaces $X$ and associated covers $\Gamma$, determine in each case whether $\Gamma$ is a fundamental cover of $X$.

1. $X = [0, 2]$ and $\Gamma = \{[0, 1], [1, 2]\}$
2. $X = [0, 2]$ and $\Gamma = \{[0, 1], (1, 2]\}$
3. $X =\mathbb{R}$ and $\Gamma=\{\mathbb{Q}, \mathbb{R}\setminus \mathbb{Q}\}$

## Quiz 12.1

Determine for which of the following topologies on $\mathbb{R}$ are the corresponding spaces connected.

1. The indiscrete topology.
2. The discrete topology.
3. The standard topology.
4. The cofinite topology.

## Quiz 12.2

Determine whether the following are true if $X$ is a connected topological space.

1. If the interior of a set $A\subset X$ is connected then $A$ is connected.
2. If $A\subset X$ is a proper subset (i.e., $A\neq X$) then the frontier of $A$ is non-empty.

## Quiz 13.1

Let $f: X \to Y$ be a continuous surjective map. Determine whether the following statements are true.

1. If $X$ is connected then so is $Y$.
2. If $Y$ is connected then so is $X$.
3. The number of connected components of $Y$ is greater than or equal to the number of connected components of $X$.
4. The number of connected components of $X$ is greater than or equal to the number of connected components of $Y$.

## Quiz 13.2

Let $X= \{(x, y)\in\mathbb{R}^2: xy = 0\}$. Then which of the following is the number of components of $X\setminus \{P\}$ for _some_ point $P\in X$.

1. $1$
2. $2$
3. $3$
4. $4$

## Quiz 14.1

For which of the following spaces $X$ is every path in $X$ a constant path.

1. $X = \mathbb{Q}$ with the metric topology from $d(x, y) = |x - y|$.
2. $X =\mathbb{N}$ with the cofinite topology.
3. $X = \mathbb{N}$ with the indiscrete topology.

## Quiz 15.1

Let $X$ be a finite set. Determine which of the following is true.

1. If $X$ is Hausdorff then the topology on $X$ is the discrete topology.
2. If $X$ is $T_1$, then the topology on $X$ is the discrete topology.

## Quiz 15.2

Let $X$ be a countably infinite set with the indiscrete topology. Determine whether the following are true.

1. $X$ is $T_1$.
2. $X$ is Hausdorff.
3. $X$ satisfies the third separation axiom.
4. $X$ satisfies the fourth separation axiom.

## Quiz 15.3

Let $X$ be a topological space and $f: X \to \mathbb{R}$ a continuous map. For $c\in \mathbb{R}$ define $X_c = \{x\in X: f(x) < c\}$. Determine whether the following are always.

1. $X_c$ is closed.
2. $X_c$ is open.
3. If $a \leq b$, then $X_a\subset X_b$.
4. If $a < b$, then $\overline{X}_a\subset X_b$.

## Quiz 15.4

For which of the following spaces $X$ can we conclude that if $Y$ is a metric space and a sequence of continuous functions $f_n: X\to Y$ converges pointwise to a function $f: X\to Y$, then $f_n$ converges uniformly to $f$?

1. $X$ is finite.
2. $X$ is indiscrete.
3. $X = [0, 1]$.

## Quiz 15.5

For which of the following subsets $A \subset\mathbb{R}$ is it true that every continuous map $f: A \to [0, 1]$ extends to a continuous map from $\mathbb{R}$ to $[0, 1]$.

1. $A = (0, 1)$
2. $A = [0, 1]\cup [2, 3]$
3. $A = \{x\in \mathbb{R}: x \leq 2\}$

