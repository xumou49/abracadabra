---
title: Learn Math
summary: Easily learn Python in 10 minutes!
date: 2023-10-24
type: docs
math: true
tags:
  - Python
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

## Polynomial and Rational Functions
### Polynomial Functions

A **polynomial function** is a function that can be expressed in the form:
- $f(x) = a_{n}x^n + a_{n-1}x^n-1 + \dots + a_{2}x^2 + a_{1}x + a_{0}$
- where:
	- $a_{n}, a_{n-1}, \dots, a_{2}, a_{1}, a_{0}$ are constants (called coefficients)
	- $n$ is a non-negative integer (called the degree of the polynomial)
	- $x$ is the variable
- Examples of polynomial functions:
	- $f(x) = 3x^4 - 2x^3 + 5x - 1$
	- $g(x) = x^2 + 4x +7$
	- $h(x) = 6$ (This is a constant polynomial, which is a polynomial of degree 0)
### Rational Functions

A **rational function** is a function that can be expressed as the ratio of two polynomial functions. The general form of a rational function is:
- $f(x) = \frac{P(x)}{Q(x)}$
- where:
	- $P(x)$ and $Q(x)$ are polynomial functions 
	- $Q(x) \neq 0$ to ensure the function is defined
- Example of rational functions:
	- $f(x) = \frac{2x^2 + 4x + 2}{5x^2 - 6x - 2}$
	- $g(x) = \frac{x^3 - 1}{x-1}$
	- $h(x) = \frac{1}{x}$ (This is a simple rational function)

### Key Differences
- **Polynomial Functions**: Defined for all real numbers. They are continuous everywhere
- **Rational Functions**: Defined for all real numbers except where denominator $Q(x)$ is 0. They are continuous everywhere except at the points where the denominator is 0.
- Continuity:
	- **Polynomial Functions**: Continuous everywhere. There are no breaks, jumps, or holes in their graphs.
	- **Rational Functions**: Continuous everywhere except where the denominator $Q(x)$ is zero. At these points, the function has vertical asymptotes or holes.

## Derivative and slope(gradient) of the tangent line to a graph
### The tangent line and its slope
1. **Tangent Line**: A tangent line to a curve at a given point is a straight line that just touches the curve at that point. It doesn't cross the curve at that point and represents the "instantaneous direction" of the curve 
2. **Slope(Gradient) of the Tangent Line**: The slope of the tangent line at a given point on the curve measures how steep the curve is at that point. It tells us the rate at which the function's value is changing with respect to changes in the input value(x)

### Derivative and slope 
The derivative of a function at a specific point gives us the slope of the tangent line to the graph of the function at that point. Here's how:
- **Derivative Definition**: The derivative of a function $f(x)$ at a point $x=a$ is defined as: $f\prime(a) = \lim_{ h\to 0 } \frac{f(a+h) - f(a)}{h}$  
- This formula essentially calculates the slope of the secant line between two points $(a, f(a))$ and $(a+h, f(a+h))$ as h (the horizontal distance between the points) gets smaller and smaller, approaching zero.
- As $h$ approaches zero, the secant line becomes closer to the tangent line at the point $(a, f(a))$
- The limit of the slopes of these secant lines is the slope of the tangent line at x$x=a$, which is the derivative $f\prime(a)$

### Visualizing the concept
Imagine you have a curve representing a function $f(X)$. At a specific point $x=a$:
1. Draw a very small interval around $x=a$
2. Calculate the slope of the line connecting the points just before and just after $x=a$. This is the slope of the secant line.
3. As you make this interval smaller and smaller, the secant line becomes closer to the tangent line.
4. When the interval is infinitesimally small, the slope of the secant line approaches the slope of the tangent line.
5. This slope of the tangent line at $x=a$ is the derivative $f\prime(a)$

### Summary
- The derivative $f\prime(a)$ of a function $f(x)$ at a point $x=a$ is the slope of the tangent line to the graph of $f(x)$ at that point 
- This slope tells you how steep the graph is at $x=a$ and represents the rate of change of the function's value with respect to changes $x$

