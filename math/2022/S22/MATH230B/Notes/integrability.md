__Lemma:__ *Let $f:[a, b]\to\mathbb{R}$ be a bounded function. Then the following statements hold:* 

1. *If $P_1, P_2$ are partitions of $[a, b]$, $P_1\subset P_2$, then*
   
   $$
   L(f, P_1)\leq L(f, P_2)\;\;\;\text{and}\;\;\;U(f, P_1)\geq U(f, P_2).
   $$

2. *If $P$ and $Q$ are any two partitions of $[a, b]$, then*
   
   $$
   L(f, P)\leq U(f, Q).
   $$

3.  
   
   $$
   \underline{S}(f)\leq\overline{S}(f).
   $$
   
   

4. $\underline{S}(f)=\overline{S}(f)$ *if and only if for all $\varepsilon>0$ there exists a partition $P_{\varepsilon}$ such that* 
   
   $$
   U(f, P_{\varepsilon})-L(f, P_{\varepsilon})<\varepsilon.
   $$

---

*__Proof:__* 

1. Since $P_1\subset P_2$, let us begin by assuming that there is only one more element in $P_2$ than in $P_1$, call it $t$. So we have that $P_1=\{x_0, \dots, x_n\}$ and $P_2=\{x_0, \dots, t,\dots, x_n\}$. With this we have that for some $i\in\{1,\dots, n\}$, $x_{i-1}<t<x_i$. Now define $m^1_i=\inf f(x)$ for $x_{i-1}\leq x\leq t$ and $m^2_i=\inf f(x)$ on $t\leq x\leq x_i$. We want to compare $m^1_i, m^2_i$ with $m_i=\inf f(x)$ on $x_{i-1}\leq x\leq x_i$. If $t$ happens to be the value at which $f$ attains its minimum, then clearly $m_i=m^1_i=m^2_i=f(t)$. Otherwise, if $f$ attains its minimum at some value $x^*$, then we have either $x_{i-1}\leq x^*< t$ or $t<x^*\leq x_i$. WLOG, if we assume the former, then we have that $m_i<m^2_i$. So in general, $m_i\leq m^1_i, m^2_i$. With this we can see that $L(P_1, f)$ and $L(P_2, f)$ are identitical save for $m^1_i$ and $m^2_i$ which are each greater than or equal to $m_i$ and so $L(P_1, f)\leq L(P_2, f)$.  
   
       We use the same logic to prove the other direction. So with the addition of one extra point, it will be a point that exists between two points in the partition and if it is the point at which $f$ attains its max, then the $\sup$s are equal, otherwise the interval will be split for $P_2$ and one of the pieces it is split into will have a $\sup$ less than the $\sup$ over the whole interval and so $U(P_1, f)\geq U(P_2, f)$.
   
       If $P_1$ and $P_2$ had more than one point different, then we would simply repeat this argument for every point they did not have in common. 

2. 




















