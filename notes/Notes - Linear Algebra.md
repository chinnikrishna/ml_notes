---
title: Notes - Linear Algebra
created: '2019-08-23T03:07:31.693Z'
modified: '2019-08-26T02:14:25.824Z'
---

# Notes - Linear Algebra

## Vector Spaces
1. Linear Algebra is the study of linear maps on finite-dimensional vector spaces. 
2. If n is a non-negative number then a __list__ is an __ordered__ collection of n elements. These elements can be scalars, lists or other abstract objects. 
E.g.,
(1, 2, 1) and (1, 2, 1, 1) are two different lists unlike sets which results in {1, 2}
3. F^n^ is a set of all possible lists of length n in which elements belong to F.
4. __Vector Space__ is a set where addition and scalar multiplication are defined and statisfies 
  a. Commutative and associative properties, has an additive identity and additive inverse.
  b. Scalar multiplication is associative and multiplicative identity exists
  c. Addition and scalar multiplication are related by dstributive property
5. Elements of vector space are called vectors. In general, a vectors space is an abstract entity whose elements might be lists, functions or weird objects.
6. Subset of a vector space is a __subspace__ provided the results of addition or scalar multiplication also belongs to subspace

## Finite Dimensional Vector Spaces

1. Adding scalar multiples of vectors in a list is called linear combination 
Eg a~1~ v~1~ + a~2~ v~2~ + ..... a~n~ v~n~ for a list of length n in a vector space V where $v \in V$ and a~1~ ..... a~n~ are scalars.
2. Set of all linear combinations of a list is called __span__ This is the smallest subspace which contains all vectors in a list.
3. If the span of list of vectors is equal to vector space then we say that list spans the vector space, i.e., every vector in this
vector space can be written as a linear combination of vectors in the list.
E.g  Span [(1, 0), (0, 1)] spans F^2^

