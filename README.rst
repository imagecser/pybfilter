pybfilter
=========
`pybfilter` is a module that include a Bloom Filter data structure.

A Bloom filter is a space-efficient probabilistic data structure that is used to test whether an element is a member of a set.

usage
-----

>>> import pybfilter
>>> bf = pybfilter.BloomFilter(n=1000, error=0.01)
>>> bf.add(1)
True
>>> bf.add(1)
False
>>> 1 in bf
True
>>> 2 in bf
False

