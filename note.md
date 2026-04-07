# Links
1. homepage https://web.mit.edu/18.06/www/
2. problem sets https://web.mit.edu/18.06/www/old.shtml

# 1 Vectors and Matrices
## 1.1 Vectors and linear combinations
1. Linear combination $cv + dw$
2. If $v$ and $w$ are **linearly independent**, then the linear combinations of $v$ and $w$ **fill the $xy$ plane**
3. If v and w are linearly dependent, combinations of v and w **fill a line** instead of the xy plane
## 1.2 Dot products
1. **Dot product** $v \cdot w = v_1w_1 + v_2w_2 + \cdots + v_nw_n$
2. Dot product $v \cdot v$ is the square of the length of v, so $v \cdot v = ||v||^2$
3. A **unit vector** $u$ has length 1, so $||u|| = 1$. If $v \neq 0$, then $\frac{v}{||v||}$ is a unit vector in the same direction as $v$
4. **Perpendicular vectors** $v$ and $w$ have a dot product of 0, so $v \cdot w = 0$
5. Angle between two vectors: if $v$ and $w$ are nonzero, then $\cos \theta = \frac{v \cdot w}{||v|| ||w||}$
6. Schwarz inequality: $|v \cdot w| \le ||v|| ||w||$
7. The vectors $w$ with $w \cdot n = 0$ fill a 2-dimensional in $R^3$
## 1.3 Matrices and column spaces
1. **Row picture** of $Ax$: **dot products** of rows of A with x
2. **Column picture** of $Ax$: **linear combinations** of columns of A
3. **Column space** of A: the set of all linear combinations of the columns of A
4. When A has m rows, the column space of A is a subspace of $R^m$
5. When the **column space** is a single line in m-dimensional space, the **row space** is a single line in n-dimensional space
## Matrix multiplication