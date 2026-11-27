Orthogonality generalizes geometric perpendicularity (a ${\color{Purple}90^{\circ }}$ or ${\color{Purple}\frac{\pi }{2}}$ radian angle) to vectors, subspaces, and general inner product spaces where two elements have a zero inner product.

### Core Definitions
- Geometric Perpendicularity: Two Euclidean vectors or intersecting curves (via their tangent lines) are orthogonal when they meet at a right angle.
- Dot / Inner Product: In ${\color{Purple}ℝ^{n}}$, vectors ${\color{Purple}𝐮}$ and ${\color{Purple}𝐯}$ are orthogonal ($𝐮 \perp 𝐯$) if ${\color{Purple}𝐮 \cdot 𝐯 = 0}$. In general inner product spaces, they are orthogonal if ${\color{Purple}\langle 𝐮, 𝐯 \rangle = 0}$ .
- Orthonormality: An orthogonal set of unit vectors (each having length ${\color{Purple}\Vert{}𝐮\Vert{} = 1}$) forms an orthonormal set.
- Orthogonal Complement ($W^{\perp }$): For a subspace ${\color{Purple}W}$, ${\color{Purple}W^{\perp }}$ is the subspace of all vectors orthogonal to every vector in ${\color{Purple}W}$. As detailed in [Lecture 17: Orthogonality](https://people.math.harvard.edu/~knill/teaching/math19b_2011/handouts/lecture17.pdf), any vector ${\color{Purple}𝐲}$ decomposes uniquely into a component in ${\color{Purple}W}$ and a component in ${\color{Purple}W^{\perp }}$. 

### Key Theorems & Tools
- Pythagorean Theorem: If ${\color{Purple}𝐱 \perp 𝐲}$, then ${\color{Purple}\Vert{}𝐱 + 𝐲\Vert{}^2 = \Vert{}𝐱\Vert{}^2 + \Vert{}𝐲\Vert{}^2}$.
- Orthogonal Projection: The projection of ${\color{Purple}𝐲}$ onto a non-zero vector ${\color{Purple}𝐮}$ is ${\color{Purple}\text{proj}\_{𝐮}𝐲 = \frac{𝐲 \cdot 𝐮}{𝐮 \cdot 𝐮}𝐮}$, leaving a perpendicular residual ${\color{Purple}𝐲 - \text{proj}\_{𝐮}𝐲}$.
- Orthogonal Matrices: A square matrix ${\color{Purple}Q}$ with orthonormal columns satisfies ${\color{Purple}Q^T Q = I}$ and ${\color{Purple}Q^{-1} = Q^T}$. Multiplying by ${\color{Purple}Q}$ preserves vector lengths and angles (rotations and reflections).
- Gram-Schmidt & QR Decomposition: As covered in Linear Algebra 18 Orthogonality, the Gram-Schmidt process builds orthogonal/orthonormal bases from linearly independent sets, leading to ${\color{Purple}A = QR}$ factorization and least-squares approximations ($A^T A \hat{𝐱} = A^T \mathbf{b}$). Further proofs and decomposition theorems appear in Understanding Orthogonality in Linear Algebra. 
For example, ${\color{Purple}𝐮 = (3, 1)}$ and ${\color{Purple}𝐯 = (-1, 3)}$ have dot product ${\color{Purple}3(-1) + 1(3) = 0}$. Projecting ${\color{Purple}𝐲 = (2, 4)}$ onto ${\color{Purple}𝐮}$ yields ${\color{Purple}\text{proj}\_{𝐮}𝐲 = (3, 1)}$, and the orthogonal component is ${\color{Purple}𝐲 - \text{proj}\_{𝐮}𝐲 = (-1, 3)}$, which is perpendicular to ${\color{Purple}𝐮}$.
If you tell me what context you are studying or applying this in, I can tailor deeper examples or practice problems to your goals:
- Linear algebra coursework (Gram-Schmidt, QR decomposition, least squares)
- Geometry or computer graphics (rotations, normals, projections)
- Data science or signal processing (PCA, Fourier series, inner product spaces)
