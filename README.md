# Algebra Module with Python

For the Spanish version, click [here](#Módulo-de-Álgebra-con-Python)

Linear Algebra is a branch of mathematics that explores concepts such as vectors, matrices, tensors, systems of linear equations, and, in its more formal focus, vector spaces and their linear transformations.

This Python module provides a comprehensive toolkit for algebraic computations. It covers a wide range of fundamental concepts and operations encountered in algebra. Below is a breakdown of the contents:

#### Contents:

 **Sets and Multisets:**
   - Sets represent collections of distinct elements, while multisets allow for repeated elements. Basic set operations such as union, intersection, difference or cartesian product are supported.

 **Vectors and Vector Spaces:**
   - Vectors are quantities characterized by magnitude and direction, commonly used in linear algebra and physics. This module provides functionalities for basic vector operations like addition, subtraction, and scalar multiplication, along with properties associated with vector spaces.

   - A vector of dimension $n$ is defined as a tuple of real numbers (referred to as the vector's components). Thus, a vector $v$ belonging to a space ${R}^{n}$ is represented as:

        $v = (a_{1}, a_{2}, a_{3}, ... a_{n})$ where $v \in {R}^{n}$

        A vector can also be viewed from the perspective of geometry as a __geometric vector__ (often using the three-dimensional space $R^{3}$ or two-dimensional ${R}^{2}$).

 **Matrices and Determinants:**
   - Matrices are arrays of numbers, arranged in rows and columns. Determinants are specific values associated with square matrices that provide essential information about their properties, such as invertibility.

   - The concept of the determinant specifically applies to square matrices. This value is obtained by summing the products of the diagonal elements of the matrix in one direction and subtracting the sum of the diagonal products in the opposite direction. It is commonly denoted by the symbol $|A|$.

        A= $\left(
        \begin{array}{ll}
        a_{11} & a_{12} & a_{13} \\
        a_{21} & a_{22}  & a_{23} \\
        a_{31} & a_{32}  & a_{33} \\
        \end{array}
        \right)$<br><br>

        $|A| = (a_{11}a_{22}a_{33} + a_{12}a_{23}a_{31} + a_{13}a_{21}a_{32}) - (a_{31}a_{22}a_{13} + a_{32}a_{23}a_{11} + a_{33}a_{21}a_{12})$

 **Eigenvalues/Eigenvectors:**
   - Eigenvalues and eigenvectors are crucial concepts in linear algebra, particularly in the study of linear transformations. They represent scalars and vectors, respectively, that are associated with special properties of matrices.

 **Functions, Limits, and Derivatives:**
   - Functions are mathematical constructs that relate an input value to an output value. This section covers the representation of functions, calculation of limits to describe their behavior at certain points, and computation of derivatives to determine rates of change.

 **Systems of Equations:**
   - Systems of equations involve multiple equations with multiple variables. This module offers functionalities to solve such systems, which are commonly encountered in various scientific disciplines.

 **Linear Regression and Gradient Descent:**
   - Linear regression is a statistical method used to model the relationship between two or more variables. Gradient descent is an optimization algorithm used to minimize the error between observed and predicted values in regression models.

 **Tensors:**
   - Tensors are multidimensional arrays that generalize scalars, vectors, and matrices. They are fundamental objects in various branches of mathematics and physics.


## Python Libraries for Linear Algebra

* *math*  
  Provides access to hyperbolic, trigonometric, and logarithmic functions for real numbers.

* *Sympy*  
  Allows us to work with symbolic mathematics.

* *Numpy*  
  Enables us to easily create vectors, matrices, and tensors.

* *Matplotlib*  
  Useful for plotting numbers and creating graphs.

* *Scipy*  
  Adds powerful numerical computing utilities to Python.

* *Random*  
  Sometimes we need to choose a random number within a specific range, select a random element from a list, pick a random card from a deck, flip a coin, etc. We'll rely on this library for such tasks.


---


# Módulo de Álgebra con Python

Para versión en inglés haz clic [aquí](#Algebra-Module-with-Python)

El estudio del Álgebra Lineal se centra en explorar diversos conceptos matemáticos, incluyendo vectores, matrices, tensores, sistemas de ecuaciones lineales y, en su forma más avanzada, espacios vectoriales y las transformaciones lineales que los afectan.

Este módulo de Python proporciona un conjunto completo de herramientas para cálculos algebraicos. Cubre una amplia gama de conceptos y operaciones fundamentales encontradas en álgebra. A continuación, se presenta un desglose de algunos de los contenidos:

#### Contenidos:

 **Conjuntos y Multiconjuntos:**
   - Los conjuntos representan colecciones de elementos distintos, mientras que los multiconjuntos permiten elementos repetidos. Se admiten operaciones básicas de conjuntos como unión, intersección, diferencia o producto cartesiano.

 **Vectores y Espacios Vectoriales:**
   - Los vectores son cantidades caracterizadas por magnitud y dirección, comúnmente utilizados en álgebra lineal y física. Este módulo proporciona funcionalidades para operaciones básicas con vectores como la adición, sustracción y multiplicación escalar, junto con propiedades asociadas con espacios vectoriales.

   - Se denomina __vector de dimensión__ $n$, a una tupla de números reales (que se llaman componentes del vector). Así, un vector $v$ perteneciente a un espacio ${R}^{n}$ se representa como:

        $v = (a_{1}, a_{2}, a_{3}, ... a_{n})$ donde $v \in {R}^{n}$

        Un vector también se puede ver desde el punto de vista de la geometría como __vector geométrico__ (usando frecuentemente el espacio tridimensional $R^{3}$ o bidimensional ${R}^{2}$).

 **Matrices y Determinantes:**
   - Las matrices son matrices de números, dispuestas en filas y columnas. Los determinantes son valores específicos asociados con matrices cuadradas que proporcionan información esencial sobre sus propiedades, como la invertibilidad.

   - El concepto del **determinante** se aplica específicamente a las **matrices cuadradas**. Este valor se obtiene al sumar los productos de los elementos diagonales de la matriz en una dirección y restar la suma de los productos diagonales en la dirección opuesta. Es comúnmente denotado por el símbolo $|A|$.

        A= $\left(
        \begin{array}{ll}
        a_{11} & a_{12} & a_{13} \\
        a_{21} & a_{22}  & a_{23} \\
        a_{31} & a_{32}  & a_{33} \\
        \end{array}
        \right)$<br><br>

        $|A| = (a_{11}a_{22}a_{33} + a_{12}a_{23}a_{31} + a_{13}a_{21}a_{32}) - (a_{31}a_{22}a_{13} + a_{32}a_{23}a_{11} + a_{33}a_{21}a_{12})$

 **Eigenvalores/Eigenvectores:**
   - Los eigenvalores y eigenvectores son conceptos cruciales en álgebra lineal, especialmente en el estudio de transformaciones lineales. Representan escalares y vectores, respectivamente, que están asociados con propiedades especiales de las matrices.

 **Funciones, Límites y Derivadas:**
   - Las funciones son constructos matemáticos que relacionan un valor de entrada con un valor de salida. Esta sección cubre la representación de funciones, el cálculo de límites para describir su comportamiento en ciertos puntos y la computación de derivadas para determinar tasas de cambio.

 **Sistemas de Ecuaciones:**
   - Los sistemas de ecuaciones involucran múltiples ecuaciones con múltiples variables. Este módulo ofrece funcionalidades para resolver dichos sistemas, que son comúnmente encontrados en varias disciplinas científicas.

 **Regresión Lineal y Descenso de Gradiente:**
   - La regresión lineal es un método estadístico utilizado para modelar la relación entre dos o más variables. El descenso de gradiente es un algoritmo de optimización utilizado para minimizar el error entre los valores observados y predichos en modelos de regresión.
 
 **Tensores:**
   - Los tensores son matrices multidimensionales que generalizan escalares, vectores y matrices. Son objetos fundamentales en diversas ramas de las matemáticas y la física.

## Librerías en Python para Álgebra Lineal

* *math*  
  Nos da acceso a funciones hiperbólicas, trigonométricas y logarítmicas para números reales.
* *Sympy*  
    Nos permite trabajar con matemática simbólica.
* *Numpy*  
    Nos va a permitir crear vectores, matrices y tensores con suma facilidad
* *Matplotlib*  
    Útil para trazar números y hacer gráficos
* *Scipy*  
    Añade a Python utilidades de cálculo numérico de gran capacidad
* *Random*  
  A veces queremos elegir un número aleatorio en un rango determinado, elegir un elemento aleatorio de una lista, elegir una carta aleatoria de un mazo, lanzar una moneda, etc. Nos apoyaremos en esta librería
