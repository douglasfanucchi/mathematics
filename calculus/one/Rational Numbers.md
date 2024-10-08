<h1>Rational Numbers</h1>

A rational number is a number in a form $\frac{p}{q}$ where $p,q \in \mathbb{Z}$ and $GCD(p, d) = 1$. The symbol used to represet rational set is $\mathbb{Q}$.

Let $r,s \in \mathbb{Q}$, $r \le s$ or $s \leq r$. We read  as $r$ is less (or less equal) than $s$ and $s$ is less (or less equal) than $r$, respectively. The relation $r \leq s$ is equivalent to $s \geq r$, the latter we read as $s$ is greater (or greater equal) than $r$.

Given a rational number $r$, where  $r = \frac{p}{q}, p$ and $q \in \mathbb{Z}$. We say that $r$ is positive if $p \cdot q \in \mathbb{N}$. If $p \neq 0$, $r$ is strictly positive. Note that if $r$ is positive, then $0 \leq r$. If it is negative, then $r \leq 0$.

Let $r$ and $s \in \mathbb{Q}$, $r \leq s$ if there is a positive $t \in \mathbb{Q}$ where $s = r + t$. If there is a strictly positive $t$ where $s = r + t$ than we say that $r < s$. We read as $r$ is strictly less than $s$. This expresion is equivalent to $s >r$, that we read as $s$ is strictly greater than $r$.

For each pair of rational element, we call its sum as addition and its product as multiplication.

Given any rational $\frac{a}{b}$ and $\frac{c}{d}$, the addition is $\frac{ad + cb}{bd}$ and the multiplication is $\frac{ac}{bd}$.

The quadruple $(\mathbb{Q}, +, \cdot, \leq)$ satisfy the following properties ($x, y, z$ are rational numbers):

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

$\exists|\ y \in \mathbb{Q} \mid x + y = 0$, we denote $y$ as $-x$.

(M4) Multiplication inverse:

$\forall x \in \mathbb{Q}$ and $x \neq 0$, $x \cdot y = 1$. We denote $y$ as $x^{-1}$ or $\frac{1}{x}$

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

Ps.: Let a set $\mathbb{K}$ with at least two elements and being the opperations sum and product defined in $\mathbb{K}$. If the triplet ($\mathbb{K}, +, \cdot$) satisfies the properties A1 - A4, M1 - M4 and D, then ($\mathbb{K},+, \cdot$) is a field. Besides that, if it is defined a relation ($\leq$) in $\mathbb{K}$ and the quadriple ($\mathbb{K}, +, \cdot, \leq$) satisfies all 15 listed properties, then $(\mathbb{K}, +, \cdot, \leq)$ is an ordered field. Note that ($\mathbb{Q}, +, \cdot, \leq$) is an ordered field while ($\mathbb{Z}, +, \cdot, \leq$) is not even a field since it does not satisfy (M4).

A rational number can be geometric represented as a point in a line. This is done by randomly choosing two points, one for 0 and other for 1. The line which extremities are 0 and 1 will be the base size in order to get any other point.

If a point $P$ represents a rational number $r$, then $r$ is the abscissa of $P$. Note that every rational number has a point representing it on the line but not every point in the line represents a rational number.

Before talking about points that does not represent rational number, let's se some demonstrations.

$i)$ Given an odd number, its square is odd.

$p = 2k + 1, k \in \mathbb{Z} \Rightarrow p^2 = 2q + 1, q \in \mathbb{Z}$

$p = 2k + 1, k \in \mathbb{Z}$

$\Rightarrow p^2 = 4k^2 + 4k + 1$

$\Rightarrow p^2 = 2k(2k + 2) + 1$

We can define $2k + 2 = q$, then $p^2 = 2q + 1, q \in \mathbb{Z}$ qed.

$ii)$ Given a square number which is even, its square root is also even.

$a^2 = 2k, k \in \mathbb{Z} \Rightarrow a = 2p, p \in \mathbb{Z}$

Let's suppose that $p$ is odd then by $(i)$, $p^2$ also is odd which contradicts our assumption. Therefore $p$ can only be even qed.

$iii)$ The equation $x^2 = 2$ has no solutions in $\mathbb{Q}$

Suppose that $x \in \mathbb{Q}$, then $x = \frac{p}{q}, GDC(p, q) = 1$

$x = \frac{p}{q} \Rightarrow x^2=\frac{p^2}{q^2} = 2$

$\frac{p^2}{q^2} = 2 \Rightarrow p^2 = 2q^2$

By $(ii)$, we can conclude that $p$ is even ($p = 2k, k \in \mathbb{Z}$).

$p = 2k \Rightarrow \frac{(2k)^2}{q^2} = 2$

$\Rightarrow \frac{4k^2}{2} = q^2$

$\Rightarrow 2k^2 = q^2$

By $(ii)$, we can conclude that $q$ also is even.

$p$ and $q$ being even contradicts or assumption, since their greatest common divisor is $1$. Therefore there is no $x \in \mathbb{Q}$ that satisfies $x²=2$.

Now we can go back to the geometric representation of numbers.

If we draw a square and its diagonal, the square having its base supported by the line we are using to represent numbers, starting on point which has abscissa $0$ and the size of the square's side being one unit. We can conclude by pythagora's theorem that the size of the its diagonal ($d$) is the number which squared equals to $2$. Using a circunference centered on the point which abscissa is $0$ and radius equals to $d$, we can determine the point on the line that represents the number $d$, which as we demonstrated, is not rational.

Our assumption will be that every point in the line has an abscissa  x, if $x$ is not rational we will call it $irrational$.

The set that has both of them, rationals and irrationals, is called Real numbers represented by $\mathbb{R}$.

---
A1 proof:

$x \in \mathbb{Q} \Rightarrow x = \frac{a_1}{b_1}$ where $a_1,b_1 \in \mathbb{Z}$

$y \in \mathbb{Q} \Rightarrow y = \frac{a_2}{b_2}$ where $a_2,b_2 \in \mathbb{Z}$

$z \in \mathbb{Q} \Rightarrow z = \frac{a_3}{b_3}$ where $a_3,b_3 \in \mathbb{Z}$

$(x + y) + z = \frac{a_1 b_2 b_3 + a_2b_1 b_3 + a_3 b_1 b_2}{b_1 b_2 b_3}$

$x + (y + z) = \frac{a_1}{b_1} + \frac{a_2 b_3 + a_3 b_2}{b_2 b_3} = \frac{a_1 b_2 b_3 + b_1(a_2 b_3 + a_3 b_2)}{b_1 b_2 b_3}$

$= \frac{a_1 b_2 b_3 + a_2 b_1 b_3 + a_3 b_1 b_2}{b_1 b_2 b_3} = (x + y) + z$

$\Rightarrow (x + y) + z = x + (y + z)$

---
M1 proof:

$x \in \mathbb{Q} \Rightarrow x = \frac{a_1}{b_1}$ where $a_1,b_1 \in \mathbb{Z}$

$y \in \mathbb{Q} \Rightarrow y = \frac{a_2}{b_2}$ where $a_2,b_2 \in \mathbb{Z}$

$z \in \mathbb{Q} \Rightarrow z = \frac{a_3}{b_3}$ where $a_3,b_3 \in \mathbb{Z}$

$(xy)z = \frac{a_1 a_2 a_3}{b_1 b_2 b_3}$

$x(yx) = \frac{a_1}{b_1} \cdot \frac{a_2 a_3}{b_2 b_3} = \frac{a_1 a_2 a_3}{b_1 b_2 b_3} = (xy)z$

---
A3 proof:

$0, 1 \in \mathbb{Z}\ \land\ GCD(0,1) = 1 \Rightarrow \frac{0}{1} \in \mathbb{Q}$

Let a $x \in \mathbb{Q}$, being $x = \frac{p}{q}$ where $p, q \in \mathbb{Z}$

Therefore:

$x + \frac{0}{1} = \frac{p}{q} + \frac{0}{1} = \frac{1p + q0}{1q} = \frac{p + 0}{q} = \frac{p}{q}= x$

Since $\frac{0}{1} = 0$, we conclude that $x + 0 = x$

---
O2 proof: 

$x \leq y\ \Rightarrow \exists|\ t_1 \in \mathbb{Q},\ t_1 \geq 0\ |\ y = x+ t_1$

$y \le x\ \Rightarrow \exists|\ t_2 \in \mathbb{Q},\ t_2 \geq 0\ |\ x = y + t_2$

$x \leq y\ \land\ y \leq x\ \Rightarrow y = y + t_2 + t_1$

$\Rightarrow 0 = t_2 + t_1$

$0 = t_2 + t_1\ \land\ t_1, t_2 \geq 0 \Longrightarrow t_1 = t_2 = 0$

$t_1 = t_2 = 0\ \land\ y = x + t_1 \Longrightarrow y = x$ 
