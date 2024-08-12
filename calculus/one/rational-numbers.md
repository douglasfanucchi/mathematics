<h1>Rational Numbers</h1>

$\newcommand{\Q}{\mathbb Q}$

A rational number is a number in a form $\frac{p}{q}$ where $p,q \in \Z$ and $GCD(p, d) = 1$. The symbol used to represet rational set is $\Q$.

Let $r,s \in \Q$, $r \le s$ or $s \leq r$. We read  as $r$ is less (or less equal) than $s$ and $s$ is less (or less equal) than $r$, respectively. The relation $r \leq s$ is equivalent to $s \geq r$, the latter we read as $s$ is greater (or greater equal) than $r$.

Given a rational number $r$, where  $r = \frac{p}{q}, p$ and $q \in \Z$. We say that $r$ is positive if $p \cdot q \in \N$. If $p \neq 0$, $r$ is strictly positive. Note that if $r$ is positive, then $0 \leq r$. If it is negative, then $r \leq 0$.

Let $r$ and $s \in \Q$, $r \leq s$ if there is a positive $t \in \Q$ where $s = r + t$. If there is a strictly positive $t$ where $s = r + t$ than we say that $r < s$. We read as $r$ is strictly less than $s$. This expresion is equivalent to $s >r$, that we read as $s$ is strictly greater than $r$.

For each pair of rational element, we call its sum as addition and its product as multiplication.

Given any rational $\frac{a}{b}$ and $\frac{c}{d}$, the addition is $\frac{ad + cb}{bd}$ and the multiplication is $\frac{ac}{bd}$.

The quadruple $(\Q, +, \cdot, \leq)$ satisfy the following properties ($x, y, z$ are rational numbers):

Associative:
- (A1) $(x + y) + z = x + (y + z)$
- (M1) $(xy)z = x(yz)$

Commutative:
- (A2) $x + y = y + x$
- (M2) $xy = yx$

Identity: There is one and only one element that:
- (A3) $x + 0 = x$
- (M3) $x \cdot 1 = x$

$$ 0 \neq 1$$

(A4) Addition inverse:

$\exists|\ y \in \Q \mid x + y = 0$, we denote $y$ as $-x$.

(M4) Multiplication inverse:

$\forall x \in \Q $ and $x \neq 0$, $x \cdot y = 1$. We denote $y$ as $x^{-1}$ or $\frac{1}{x}$

(D) Distributive:

$x(y + z) = xy + xz$

(O1) Reflexive:

$x \le x $

(O2) Antisymmetric:

$x \le y\ \land\ y \le x \Longrightarrow x = y$

(O3) Transitive:

$x \leq y \ \land\ y\leq z \Longrightarrow x \leq z$

(O4) Given any rational $x$ and $y$

$x \leq y\ \lor\ y \leq x$

(OA) Order compatible with addition

$x \leq y \Longrightarrow x +z \leq y + z$

(OM) Order compatible with multiplication

$z \ge 0$

$x \leq y \Longrightarrow xz \leq yz$

$\newcommand{\K}{\mathbb{K}}$

Ps.: Let a set $\K$ with at least two elements and being the opperations sum and product defined in $\K$. If the triplet ($\K, +, \cdot$) satisfies the properties A1 - A4, M1 - M4 and D, then ($\K,+, \cdot$) is a field. Besides that, if it is defined a relation ($\leq$) in $\K$ and the quadriple ($\K, +, \cdot, \leq$) satisfies all 15 listed properties, then $(\K, +, \cdot, \leq)$ is an ordered field. Note that ($\Q, +, \cdot, \leq$) is an ordered field while ($\Z, +, \cdot, \leq$) is not even a field since it does not satisfy (M4).