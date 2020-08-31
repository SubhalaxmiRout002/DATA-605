# DATA-605
Week 1 assignment.
1. Problem set 1
You can think of vectors representing many dimensions of related information. For
instance, Net
ix might store all the ratings a user gives to movies in a vector. This is
clearly a vector of very large dimensions (in the millions) and very sparse as the user might
have rated only a few movies. Similarly, Amazon might store the items purchased by a user
in a vector, with each slot or dimension representing a unique product and the value of the
slot, the number of such items the user bought. One task that is frequently done in these
settings is to nd similarities between users. And, we can use dot-product between vectors
to do just that. As you know, the dot-product is proportional to the length of two vectors
and to the angle between them. In fact, the dot-product between two vectors, normalized
by their lengths is called as the cosine distance and is frequently used in recommendation
engines.
(1) Calculate the dot product u:v where u = [0:5; 0:5] and v = [3;-4]
(2) What are the lengths of u and v? Please note that the mathematical notion of the
length of a vector is not the same as a computer science denition.
(3) What is the linear combination: 3u - 2v?
(4) What is the angle between u and v

2. Problem set 2
Set up a system of equations with 3 variables and 3 constraints and solve for x. Please
write a function in R that will take two variables (matrix A & constraint vector b) and
solve using elimination. Your function should produce the right answer for the system of
equations for any 3-variable, 3-equation system. You don't have to worry about degenerate
cases and can safely assume that the function will only be tested with a system of equations
that has a solution. Please note that you do have to worry about zero pivots, though. Please
note that you should not use the built-in function solve to solve this system or use matrix
inverses. The approach that you should employ is to construct an Upper Triangular Matrix
and then back-substitute to get the solution. Alternatively, you can augment the matrix
A with vector b and jointly apply the Gauss Jordan elimination procedure.

Please test it with the system below and it should produce a solution x = [-1:55;-0:32; 0:95]
