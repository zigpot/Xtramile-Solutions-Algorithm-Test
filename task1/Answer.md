# Answer

Relational database would be fitting nice to ***B+ Tree*** Algorithm.


The fact that a database deals with a large amount of data with ease, at a reasonable speed is the main reason.
A B+ tree is very shallow and it depth grows logarithmically, to the number of data. And that means that for lookup into a disk, the number of times we access a disk accesses to retrieve is proportional to the 'depth' of the tree, so the shallower the tree, the less we have to access the tree.

The time complexity required for a B+ Tree to retrieve, store, and remove an entry is reasonable sublinear: ***O log(n) for all cases***.




