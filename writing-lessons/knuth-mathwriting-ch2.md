# 2. An Exercise on Technical Writing

In the following excerpt from a term paper, $N$ denotes the nonnegative integers, $N^n$ denotes the set of $n$-tuples of nonnegative integers, and $An = \{(a1,\dots,an)\in N^n \relv a1  \cdots  an\}$. If
$C, P \subset N^n$, then $L(C,P)$ is defined to be $\{c+p1+\cdots +pm \relv c\in C$, $m  0$, and $pj \in P$ for ${1 j m}\}$. We want to prove that $L(C,P) \subseteq An$ implies $C,P \subseteq An$.

The following proof, directly quoted from a sophomore term paper, is mathematically correct (except for a minor slip) but stylistically atrocious:

: $L(C,P) \subset An$ $C \subset L \ C \subset An$ Spse
$ p\in P, \;p\notin An \ pi < pj$ for $i<j$ $c+p \in L \subset An$
$\therefore  ci+pi  cj+pj$ but $ci cj0, pjpi \therefore
  (ci-cj)  (pj-pi)$ but $$ a constant
$k \suchthat  c+kp \notin An$ let
$k = (ci-cj)+1 \qquad c+kp \in L \subset An$
$\therefore  ci+kpi  cj+kpj \ (ci-cj)  k(pj-pi)$
$\ k-1  k \cdot m \qquad k,m  1$ Contradiction
$\therefore  p \in An$
$\therefore  L(C,P) \subset An \ C,P \subset An$ and the lemma is
true.

Let $N$ denote the set of nonnegative integers, and let $$N^n = \{\,(b1,\dots,bn) \relv bi \in N \hbox{ for }1in\,\}$$ be the set of $n$-dimensional vectors with nonnegative integer components. We shall be especially interested in the subset of “nonincreasing” vectors,

$$
An = \leftset(a1,\dots,an) \in N^n \relv a1  \cdots  an\rightset.
    \eqno(1)
    $$

If $C$ and $P$ are subsets of $N^n$, let

$$
L(C,P) = \leftset c+p1+ \cdots +pm \relv c \in C, m0,\,\,
    \hbox{and}\,\, pj \in P \,\, \hbox{for}\,\, 1jm\rightset \eqno(2)
$$

be the smallest subset of $N^n$ that contains $C$ and is closed under the addition of elements of $P$. Since $An$ is closed under addition, $L(C,P)$ will be a subset of $An$ whenever $C$ and $P$ are both contained in $An$. We can also prove the converse of this statement.

Lemma 1. If $L(C,P) \subseteq An$ and $C\emptyset$, then $C \subseteq An$ and $P \subseteq An$.

Proof. (Now it’s your turn to write it up beautifully.)
