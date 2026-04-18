### ⬜ What is Linear algebra?
$\large{\color{purple}\textrm{Answer}:}$ **Linear Algebra** is a mathematical discipline that deals with **vectors** and **matrices** and more generally, with **vector spaces** and **linear transformations**. 
### ⬜ What is a Scaler?
$\large{\color{purple}\textrm{Answer}:}$ A **Scalar** is a number. It is a physical quantity that is completely described by its _magnitude(size)_; examples of scalars are **volume**, **density**, **speed**, **energy**, **mass**, and **time**. 

* Other quantities, such as **force** and **velocity**, have both _magnitude(size)_ and _direction_ and are called **_vectors_**.
* **Scalars** are described by _real numbers_ that are _usually but not necessarily positive_. **Scalars** can be manipulated by the ordinary laws of algebra.

#### Example:
* Let $\large{\color{Purple}\mathbf{\alpha \in ℝ}}$ , be the _learning rate_.
* Let $\large{\color{Purple}\mathbf{\eta \in ℕ}}$ , be the _number of hyperparameters_.

_Scalar quantities_ change when their _magnitude_ changes.

### ⬜ What is a Vector?
$\large{\color{Purple}\textrm{Answer}:}$ A **vector** in machine learning is simply an **array of numbers**. 

In **physics**, a Vector is a quantity that has both **magnitude** and **direction**. 

In **Computer Science Vector** is a data in _tabular form_ having _rows_ and _columns_. 
   *  A vector is just an **array of numbers**.
   *  Every vector has a length. 
   *  In mathematics notation- If we want to say that a vector  $\large{\color{Purple} x}$ consists of $\large{\color{Purple} n \}$ real-valued scalars, we can express this as   $\Large{\color{Purple}x \in ℝ^{n}}$
   *  The <ins><i>length</i></ins> of a vector is commonly called the <ins><i>dimension</i></ins> of the vector.
   *  When a tensor represents a vector (with precisely one axis), we can also access its length via the .shape attribute. The shape is a tuple that lists the length (dimensionality) along each axis of the tensor. For tensors with just one axis, the shape has just one element.

#### Example #1
* Let say  $\large{\color{Purple} \overrightarrow{x} \in  ℝ^{n} }$, be the input vector. 

$$\large{\color{Purple}x=\begin{bmatrix} 
x_1\\
x_2\\
x_3\\
\vdots\\
x_n\\
\end{bmatrix}}$$

* ${\color{Purple}\mathrm{11m} \ east}$ and ${\color{Purple}\mathrm{15ms^{-1}} \ at \ \mathrm{30^{\circ}}}$ to the horizontal, are both vector quantities.

#### Vector qualities include - 
* displacement
* velocity
* acceleration
* force
* weight
* momentum

#### Vector quantities change when:
* their magnitude changes
* their direction changes
* their magnitude and direction both change

#### Example #2
* A geostationary satellite is in orbit above Earth. It moves at constant speed but its velocity is constantly changing (since its direction is always changing).

### ⬜ What is the difference between Scalar and Vector quantities?
$\large{\color{Purple}\textrm{Answer}:}$
* **Speed** is a scalar quantity – **it is the rate of change in the distance travelled by an object.**
* While **velocity** is a **vector quantity** – **it is the speed of an object in a particular direction.**


 ### ⬜  What is a Matrix?
 $\large{\color{Purple}\textrm{Answer}:}$  In **Machine Learning**, a matrix is a **2-D array** of numbers. In **Computer Science**, a **matrix** is a **_multidimensional array_**. 

#### What is the weight of a Matrix in Data Science?
$\large{\color{Purple}\textrm{Answer}:}$ If there is a matrix $\large{\color{Purple}A_{m \times n}}$ then the weight of the matrix would be-

$$\Large{\color{Purple} W= ℝ^{m \times n}}$$

### ⬜ What is the difference between a Vector and a Matrix?
$\large{\color{Purple}\textrm{Answer}:}$
*  A **matrix** is a rectangular array of numbers, while a **vector** is a list of numbers. 
*  A vector has one index, a matrix has two indices.

### ⬜ What is a Tensor?
$\large{\color{Purple}\textrm{Answer}:}$  In Machine Learning, **Tensors** are an array of numbers with **dimensions greater than two(2)**.

* _The general term of **Scalars**, **Vectors** and **Matrix** is **Tensors**._
* The use of **Tensors** or **multi-dimensional matrices** Google named the package "**Tensorflow**".

#### Example #1
<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" />

> ### Just as **vectors** generalize **scalars**, and **matrices** generalize **vectors**. **Tensors** ("tensors" in this subsection refer to algebraic objects) give us a generic way of describing  **n-dimensional arrays** with an arbitrary number of axes.

**Vectors** are **first-order tensors** and **Matrix** are **second-order tensors**. Tensors are denoted with capital letters of a special font face (e.g.,  **X** ,  **Y** , and  **Z** ) and their **indexing mechanism** (e.g. <img src="https://latex.codecogs.com/svg.image?\large&space;{\color{Purple}\&space;\&space;x_{ijk}\&space;\&space;and\&space;\&space;[X]_{1,2i-1,3}}" title="https://latex.codecogs.com/svg.image?\large {\color{Purple}\ \ x_{ijk}\ \ and\ \ [X]_{1,2i-1,3}}" />) is similar to that of **matrices**.


### Tensors Orders
 
#### Scalar(**0<sup>th</sup>** order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha=3}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha=3} }" align="center"/>

#### Vector (**1<sup>st</sup>** order **Tensor**)  <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}}&space;=&space;\begin{bmatrix}&space;1\\&space;2\\&space;3\\4\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}} = \begin{bmatrix} 1\\ 2\\ 3\\4\end{bmatrix}}" align="center"/>, The dimension of this Vector is 4, (<img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\textbf{Dimension&space;of&space;a&space;Vector&space;=&space;the&space;number&space;of&space;elements}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \textbf{Dimension of a Vector = the number of elements} }" align="center"/>)

#### Matrix (**2<sup>nd</sup>** order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A_{i,j}}=&space;\begin{bmatrix}1&space;&&space;2&space;&space;&&space;3&space;\\4&space;&&space;5&space;&&space;5&space;\\\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A_{i,j}}= \begin{bmatrix}1 & 2 & 3 \\4 & 5 & 5 \\\end{bmatrix}}" align="center"/>

#### Tensor (**3<sup>rd</sup>** and higher order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" />

#### Example
* Colour images, Video data( **4<sup>th</sup>** order tensors coz series of images)
 


### ⬛ <ins>Vectors and Matrices:</ins>
### ⬛ Numbers
#### 🔲 Number sets

<div align="center">
  
  |Symbol|<div align="center"> Description</div>|
  |:-----:|:----|
  |$\Large{\color{Purple} ℕ}$  | The set of natural numbers,<br> $\large{\color{Purple} ℕ = \\{1,2,3, \dots \ \\}}$ <br> infinite and countable,<br> $\large{\color{Purple} ℕ_{+} = \\{1,2,3, \dots \ \\}}$ |
  |$\Large{\color{Purple} ℤ}$ |The set of integers  is infinite and countable <br> $\large{\color{Purple} ℤ = \\{0,+1, +2, +3, \dots \ \\}}$ |
  |$\Large{\color{Purple} ℚ}$  |The set of rational numbers <br> $\large{\color{Purple} ℚ = \\{p/q, p \in ℤ,  q \in ℕ_{+} \\}}$ |
  |$\Large{\color{Purple} ℝ}$ | The set of real numbers is infinite, not countable, can be ordered|
  |$\Large{\color{Purple} ℂ}$  |The set of complex numbers, <br> $\large{\color{Purple} ℂ = \\{x + iy; x,y \in ℝ \\}}$ <br> infinite, not countable, cannot be ordered|
  
</div>


 These sets of numbers form a hierarchy, with $\Large{\color{Purple} ℕ \subset ℤ \subset ℚ \subset ℝ \subset ℂ \subset }$.   The size of a set of numbers is  an important aspect of its utility in describing natural phenomena. The set $\large{\color{Purple}S= \\{Mary, Jane, Tom \\}}$ has three elements, and its size is defined by the **cardinal number** $\large{\color{Purple}\textbar S \textbar =3 }$
 
### ⬛ Vectors
### 🔲 Vector Spaces
