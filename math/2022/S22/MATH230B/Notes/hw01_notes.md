### Fundamentals

__Definition:__ Let $X$ be a metric space. All points and sets mentioned below are understood to be elements and subsets of $X$.

* __*A neighborhood*__ of a point $p$ is a set $N_r(p)$ consisting of all points $q$ such that $d(p, q)<r$. 

* A point $p$ is called a __*limit point*__ of the set $E$ if *every* neighborhood of $p$ contains a point $q\neq p$ such that $q\in E$. 

* If $p\in E$ and $p$ is not a limit point of $E$, then $p$ is called an __*isolated point*__ of $E$.

* A set $E$ is __*closed*__ if every limit point of $E$ is a point of $E$. In other words, if $E$ contains all of its limit points. 

* A point $p$ is an __*interior*__ point of $E$ if there is a neighborhood $N$ of $p$ such that $N\subset E$. 

* $E$ is __*perfect*__ if $E$ is closed and if every point of $E$ is a limit point of $E$.

* $E$ is __*bounded*__ if there is a real number $M$ and a point $q\in X$ such that $d(p, q)<M$ for all $p\in E$. 

* $E$ is __*dense*__ in $X$ if every point of $X$ is a limit point of $E$, or a point of $E$ (or both).

---

### Limits

__Definition:__ Let $X$ and $Y$ be metric spaces; suppose $E\subset X$, $f$ maps $E$ into $Y$, and $p$ is a limit point of $E$. We write $f(x)\to q$ as $x\to p$, or 

$$
\lim_{x\to p}f(x)=q.
$$

if there is a point $q\in Y$ with the following property: For every $\varepsilon>0$ there exists a $\delta>0$ such that

$$
d_Y(f(x), q)<\varepsilon
$$

for all points $x\in E$ for which 

$$
0<d_X(x, p)<\delta.
$$

__Theorem:__ *Let $X$, $Y$, $E$, $f$, and $p$ be as in the previous definition. Then*

$$
\lim_{x\to p}f(x)=q
$$

*if and only if*

$$
\lim_{n\to\infty}f(p_n)=q
$$

*for every sequence $\{p_n\}$ in $E$ such that* 

$$
p_n\neq p,\;\;\;\;\lim_{n\to\infty}p_n=p.
$$

---

### Continuity

__Definition:__ Suppose $X$ and $Y$ are metric spaces, $E\subset X$, $p\in E$, and $f$ maps $E$ into $Y$. Then $f$ is said to be __*continuous at*__ $p$ if for every $\varepsilon>0$ there exists a $\delta>0$ such that 

$$
d_Y(f(x), f(p))<\varepsilon
$$

for all points $x\in E$ for which $d_X(x, p)<\delta$. 

---

### Derivatives

__Definition:__ Let $f$ be defined (and real-valued) on $[a, b]$. For any $x\in[a, b]$ form the quotient 

$$
\phi(t)=\frac{f(t)-f(x)}{t-x}\;\;\;\;(a<t<b,\;t\neq x),
$$

and define

$$
f'(x)=\lim_{t\to x}\phi(t)
$$

provided this limit exists. We thus associate with the funtion $f$ a function $f'$ whose domain is the set of points $x$ at which the limit exists; $f'$ is called the __*derivative*__ of $f$.

---


