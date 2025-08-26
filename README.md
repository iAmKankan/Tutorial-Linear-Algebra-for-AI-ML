
### Index
1. [Linear Combinations](https://github.com/iAmKankan/Tutorial-Linear-Algebra-for-AI-ML/blob/main/1-Linear%20Combinations/README.md)
   * Vectors and Matrices
      * Numbers
         * Number set
### ⬜ What is Linear algebra?
$\large{\color{purple}\textrm{Answer}:}$ **Linear Algebra** is a mathematical discipline that deals with **vectors** and **matrices** and more generally, with **vector spaces** and **linear transformations**. 
### ⬜ What is a Scaler?
$\large{\color{purple}\textrm{Answer}:}$ A **Scalar** is a number. It is a physical quantity that is completely described by its _magnitude(size)_; examples of scalars are **volume**, **density**, **speed**, **energy**, **mass**, and **time**. 

* Other quantities, such as **force** and **velocity**, have both _magnitude(size)_ and _direction_ and are called **_vectors_**.
* **Scalars** are described by _real numbers_ that are _usually but not necessarily positive_. **Scalars** can be manipulated by the ordinary laws of algebra.

#### Example:
* Let $\large{\color{Purple}\mathbf{\alpha \in \mathbb{R}}}$ , be the _learning rate_.
* Let $\large{\color{Purple}\mathbf{\eta \in \mathbb{N}}}$ , be the _number of hyperparameters_.

_Scalar quantities_ change when their _magnitude_ changes.

### ⬜ What is a Vector?
$\large{\color{purple}\textrm{Answer}:}$ A **vector** in machine learning is simply an **array of numbers**. 

In **physics**, a Vector is a quantity that has both **magnitude** and **direction**. 

In **Computer Science Vector** is a data in _tabuler form_ having _rows_ and _columns_. 
   *  A vector is just an **array of numbers**.
   *  Every vector has a length. 
   *  In mathematics notation- If we want to say that a vector  $\large{\color{Purple} x}$ consists of $\large{\color{Purple} n \}$ real-valued scalars, we can express this as $\large{\color{Purple} x\in \mathbb{R}^n}$..
   *  The <ins><i>length</i></ins> of a vector is commonly called the <ins><i>dimension</i></ins> of the vector.
   *  When a tensor represents a vector (with precisely one axis), we can also access its length via the .shape attribute. The shape is a tuple that lists the length (dimensionality) along each axis of the tensor. For tensors with just one axis, the shape has just one element.

#### Example #1
* Let say <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{x}&space;\in&space;\mathbb{R}^n}&space;}" title="{\color{Purple}\mathbf{\overrightarrow{x} \in \mathbb{R}^n} }" />, be the input vector. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}x=\begin{bmatrix}&space;{\color{Purple}x_1}\\&space;{\color{Purple}x_2}\\{\color{Purple}\vdots&space;}\\{\color{Purple}x_n}\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}x=\begin{bmatrix} {\color{Purple}x_1}\\ {\color{Purple}x_2}\\{\color{Purple}\vdots }\\{\color{Purple}x_n}\end{bmatrix}}" align="center"/>
 
* <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{11m\&space;east\&space;and\&space;15ms^{-1}\&space;at\&space;30^{\circ}&space;}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{11m\ east\ and\ 15ms^{-1}\ at\ 30^{\circ} }}" /> to the horizontal are both vector quantities.

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

### Difference between Scalar and Vector quantities
* **Speed** is a scalar quantity – **it is the rate of change in the distance travelled by an object.**
* While **velocity** is a **vector quantity** – **it is the speed of an object in a particular direction.**
