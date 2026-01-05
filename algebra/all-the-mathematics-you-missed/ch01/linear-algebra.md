1.1 Introduction

~ a math problem can be solved if it can be reduced to a calculation of linear algebra which also reduces ultimately to the solving of a system of linear equations.

1.2 The Basic Vector Space Rn

- Rn is thee 'quintessential' vector space, the set of all n-tuples of real numbers

- it is a vector space because you can add two n-tuples and multiply each n-tuple by a real number lambda.

- the natural map from some Rn to an Rm is given by matrix multiplication: given a vector of size n in Rn we need a matrix A of size mxn such that Ax is the m-tuple.

- for any two vectors x and y in Rn and any two scalars lambda and miu, we have A(lambda x + miu y) = lambda Ax + miu Ay

- if an inverse matrix exists then there are algorithms for its calculations


1.3 Vector Spaces and Linear transformations
A vector space is any collection of objects V where you can:
Def 1.3.1 A set V is a vector space over the real numbers R if there are maps:
1. add two objects in V: v + w is still in V
2. Scale an object in V by a real number a: av is still in V


a. zero vector exists - a do nothing element on addition
b. negative exist - for every v there i's -v so v +(-v) = 0
c. order doesn't matter: v + w = w + v
d. distribute scaling over addition: a(v+w) =av +aw
e. scaling twice is consistent: a(bv) = (ab)v
f. distribute addition of scalars:(a+b)v=av+bv
g. scaling by 1 changes nothing 1*v =v


Definition 1.3.2 A linear transformation T: V -> W is a function from a vector space V to a vector space W such that for any real numbers a1 and a2 and any vectors v1 adn v2 in V we have:
T(a1v1 + a2v2) = a1T(v1) + a2T(v2)
