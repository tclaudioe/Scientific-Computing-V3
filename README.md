# Scientific Computing

Lots of fun stuffs about Scientific Computing!

## Mini-Bio

Claudio Torres is a faculty member at [Department of Informatics](http://www.inf.utfsm.cl),
[UTFSM](http://www.usm.cl).

## What does this repo contains?

All the jupyter notebooks of ``INF-285 Computación Científica``.

If you have any questions or suggestions, please send the to _claudio.torres_ at (@) _usm.cl_ .

---

# What is the purpose of this repo?

1. Share the code
2. Share the opportunity to **play** with what we are learning in the lectures
3. Get into the analysis of detailed examples
4. Learn to analyze how different algorithms and methods handle particular problems

Below, we show the list of main files related to each chapter on the classnotes and below that we have a list of **Bonus** files that complements the mains files.
All of them are interesting and **even easier to use** now with the CoLab link!

## List of main files


| Chapter | Topic                          | Link                                                                                                                                                                                                    |
| :-------- | :------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1       | Introduction                   | See classnotes                                                                                                                                                                                          |
| 2       | Floating point arithmetic      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/02_floating_point_arithmetic.ipynb)   |
| 3       | Roots of 1D functions          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/03_roots_of_1D_functions.ipynb)       |
| 4       | System of linear equations     | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/04_system_of_linear_equations.ipynb)  |
| 5       | Polynomial interpolation in 1D | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/05_Polynomial_Interpolation_1D.ipynb) |
| 6       | Least squares                  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/06_Least_Squares.ipynb)               |
| 7       | GMRes                          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/07_GMRes.ipynb)                       |
| 8       | Numerical integration          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/08_Numerical_Integration.ipynb)       |
| 9       | ODEs                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/09_ODE.ipynb)                         |

## List of bonus files

- _Preliminary_
  -------------


  - _**A sneak peek at Scientific Computing**_: This jupyter notebook provides a overview of what the course by show the how the trigonometric function $\sin(x)$ and $\cos(x)$ can be approximated and their consequences. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%20000%20-%20A%20sneak%20peek%20at%20Scientific%20Computing.ipynb) Additionally, I have recorded a video showing the jupyter notebook and how the different numerical experiments can be analyzed. [![Watch on YouTube](https://github.com/tclaudioe/Scientific-Computing-V3/blob/main/images/WatchonYouTube-black-1xPNG.png?raw=true)](https://youtu.be/8o07msNmqbk)
  - _**The Beginning**_: This jupyter notebook gives an **important** introduction to key libraries for the class, such as NumPy, Matplotlib, among other. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2000%20-%20The%20beginning.ipynb)
  - _**List Comprehension vs NumPy**_: Here we analyze the effects of writing code taking and not taking advantage of NumPy, and how slower the code gets when we don't take advantage of NumPy. This is **very very very important** in the class. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2000%20-%20List%20Comprehension%20vs%20NumPy.ipynb)
  - _**Solving a system of linear equations**_: A traditional first approach to solve a system of linear equations one thinks of is by computing the **forbidden** inverse of a matrix, i.e. $A^{-1}$. Here we show that this approach is an slow alternative, there are other issues but for now it is enough to know it is just slow. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2000%20-%20Solving%20a%20system%20of%20linear%20equations.ipynb)
  - Interesting examples to play with during the beginning of the semester:
    - _**First lecture - linear transformation of an image**_: Here we can observe how a linear transformation applied to an image works. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2000%20-%20First%20lecture%20-%20linear%20transformation%20of%20an%20image.ipynb)
    - _**Playing with Julia**_: Here we analyze two alternative implementations for the computation of a series. The number of terms requiered to see the difference is huge, so we implemented in the Julia language because if this was done in Python (in the way we needed) it would have needed too much time. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2000%20-%20Playing%20with%20Julia.ipynb)
    - _**Class zero - a mix of some Jupyter Notebooks and more**_: This was used in a first lecture in the past. It contains a brief overview of key points of NumPy and Matplotlib. The interesting part is that it has some interesting questions in it. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2000%20-%20Class%20zero.ipynb)
- _Introduction_

  - _**Linear Transformation**_: In this file we play with linear transformation, from its graphical interpretation to solving a system of linear equations. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2001%20-%20Linear%20Transformation.ipynb)
- _Floating point arithmetic_

  - _**Quadratic Formula**_: Here we explore what happens when there **loss of significance** when implementing the _classical_ quadratic formula to find the roots of a parabola. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2002%20-%20Quadratic%20formula.ipynb) [![Watch on YouTube](https://github.com/tclaudioe/Scientific-Computing-V3/blob/main/images/WatchonYouTube-black-1xPNG.png?raw=true)](https://youtu.be/Igj3PRc_e5A)
- _Roots of 1D functions_

  - _**An slow root finder**_: In this file we explore what we called **ABSRF** (A Bad and Slow Root Finder), which divides the interval in $N$ equalspaced segments and then it finds in which interval there is a change of sign, it then subdivides that interval and continues the procedure, and comparate it to the **Bisection**. The analysis is interesting! [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2003%20-%20An%20slow%20root%20finder.ipynb)
- _System of linear equations_

  - _**GE, LU and PALU**_: This file analyzes the **Gaussian Elimination** (GE) algorithm in a symbolic way, then it connects GE to the LU factorization, to finish then with the PALU factorization. It is strongly **recommended** to review it. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2004%20-%20GE%2C%20LU%20and%20PALU.ipynb)
  - _**Ill conditioned matrices**_: Here we analyze the effect of ill contidioned matrices when solving a system of linear equations and how it is related to its condition number $\kappa(A)$. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2004%20-%20Ill%20conditioned%20matrices.ipynb)
  - _**Newton's Method in $\mathbb{R}^n$**_: Here is a simple but explicit example of the use of Newton's method in higher dimension. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2004%20-%20Newton%20Rn.ipynb)
- _Polynomial interpolation in 1D_

  - _**Finding 2 Chebyshev points graphically**_: This is a visual exploration of what Chebyshev points minimizes. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2005%20-%20Finding%202%20Chebyshev%20PointsGraphically.ipynb)
- _Least squares_

  - _**Weighted Linear Least Squares Problems**_: A first possible extension to the classical least square problem is analyzed, i.e. we add a weight to each equation. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2006%20-%20Weighted%20Least%20Squares.ipynb)
  - _**Gradient Descent and Nonlinear Least-Square**_: This is a possible second extension to the classical least square problem, making in nonlinear! The **Gradient Descent** algorithm is presented as well! [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2006%20-%20Gradient%20Descent%20and%20Nonlinear%20Least-Square.ipynb)
- _GMRes_

  - _**An small but detailed example of GMRes**_: The title says it all. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2007%20-%20An%20small%20but%20detailed%20example%20of%20GMRes.ipynb)
  - _**Sylvester Equation with GMRes**_: Here is an example where GMRes show its power over using GE, LU or PALU! [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2007%20-%20Sylvester%20Equation%20with%20GMRes.ipynb)
- _Numerical integration_

  - No bonus notebooks available for this chapter.
- _ODEs_

  - **Initial Values Problems**
    - _**My first IVP**_: This file contains a detailed comparison between an algebraic solution and a numerical computation for an **Initial Value Problem**. It is recommended as a first step to undertand what a numerical algorithm approximates. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2009%20-%20My%20first%20IVP.ipynb)
    - _**Pendulum, double pendulum and chaos**_: Here a simple and a double pendulum is simulated numerically. It show how higher order ODEs can be translated to a IVP. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2009%20-%20Pendulum%2C%20double%20pendulum%20and%20chaos.ipynb)
  - **Boundary Value Problems**
    - _**My first BVP**_: Similarly to _My First IVP_, here we build a detailed comparison between an algebraic and a numerical solution for a **Boundary Value Problem**. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2009%20-%20My%20first%20BVP.ipynb)
  - _**Several IVP and BVP examples**_:
    - File 1: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2009%20-%20BVP%20and%20IVP.ipynb)
    - File 2: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tclaudioe/Scientific-Computing-V3/blob/main/Bonus%20-%20current/Bonus%20-%2009%20-%20linear%20and%20nonlinear%20BVP%20with%20Finite%20Difference%20and%20the%20Shooting%20Method.ipynb)
