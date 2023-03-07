# Principle Component Analysis and Proper Orthogonal Decomposition

*Author: Chunyan Li*
*Date: March 2022*

## Introduction



## Motivation

### Slide 1

- PCA is a dimensional reduction method/feature extraction method.
- Shows figure 1

### Slide 2

- Explains PCA with example (a) and (b)
- Notes that PCA rotates the coordinate system to represent data in a lower-dimensional subspace without losing too much information
- Notes that the goal is to preserve as much of the variance in the original data as possible in the new coordinate system
- States that given data of d variables, the hope is that the data points will lie mainly in a linear subspace of dimension lower than d

### Slide 3

- Explains the first and second principle components
- Provides various ways to understand PCA

## Definition and Optimization problem

### Slide 4

- Defines the principal axes as those orthonormal axes onto which the variance retained under projection is maximal
- Formulates PCA as an optimization problem
- Shows equation 1
- Notes that this is not a well-defined problem and a constraint is needed

### Slide 5

- Explains the constraint needed to make the optimization problem well-defined
- Shows the updated optimization problem with the constraint