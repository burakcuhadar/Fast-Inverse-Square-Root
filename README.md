# Fast Inverse Square Root
In this project I have implemented my own floating point number logic and [fast inverse square root algorithm](https://en.wikipedia.org/wiki/Fast_inverse_square_root).
This project was my homework for the [Numerical Programming course in Technical University of Munich](https://www5.in.tum.de/wiki/index.php/Numerisches_Programmieren_-_Summer_18).

The floating point number logic is implemented in the class Gleitpunktzahl and fast inverse square root algorithm is implemented in the FastMath class. 
The Plotter class provides a graphical plot of the real value of the inverse square with a green line.
It also shows the abolute error of my algorithm with red dots.

**How to test the code:** There are two example classes called Test_FastInverse for testing the algorithm and Test_Gleitpunktzahl
for testing floating point numbers. In these classes there are example test cases.

**NOTE:** The magic number is chosen for the floating point numbers with 4 exponent bits and 8 mantissa bits. You can replace the number with an appropriate one for other cases.

# Example output
The following plot shows the real value of the inverse square with the absolute error of my implementation for numbers with
4 exponent bits and 8 mantissa bits: ![alt text](https://github.com/burakcuhadar/Fast-Inverse-Square-Root/blob/master/example_invSqrt.png)



The following methods are implemented by myself:
* **normalisiere** and **denormalisiere** methods in **Gleitpunktzahl** class
* **add** and **sub** methods in **Gleitpunktzahl** class
* **invSqrt** method in **FastMath** class
