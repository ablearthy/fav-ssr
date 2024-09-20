# Functional Data Structures and Algorithms in SSReflect

A port of https://functional-algorithms-verified.org/ to Coq/SSReflect.

The book was previously called "Functional Algorithms Verified", hence the FAV acronym.

## Dependencies

- [MathComp ssreflect 1.17](https://math-comp.github.io)
- [MathComp algebra](https://math-comp.github.io)
- [Equations 1.3](https://mattam82.github.io/Coq-Equations/)

## Contents

1. [Basics](src/basics.v)
### Part I: Sorting and Selection
2. [Sorting](src/sorting.v)
3. [Selection](src/selection.v)
### Part II: Search Trees
4. [Binary Trees](src/bintree.v)
5. [Binary Search Trees](src/bst.v)
6. [Abstract Data Types](src/adt.v)
7. [2-3 Trees](src/twothree.v)
8. [Red-Black Trees](src/redblack.v)
9. [AVL Trees](src/avl.v)
10. [Beyond Insert and Delete: \cup, \cap and -](src/beyond.v)
11. [Arrays via Braun Trees](src/braun.v)
12. [Tries](src/trie.v)
13. [Region Quadtrees](src/quadtree.v)
### Part III: Priority Queues
14. [Priority Queues](src/priority.v)
15. [Leftist Heaps](src/leftist.v)
16. [Priority Queues via Braun Trees](src/braun_queue.v)
17. [Binomial Heaps](src/binom_heap.v)
### Part IV: Advanced Design and Analysis Techniques
18. Dynamic Programming
19. Amortized Analysis
20. Queues
21. Splay Trees
22. Skew Heaps
23. Pairing Heaps
### Part V: Selected Topics
24. Knuth–Morris–Pratt String Search
25. [Huffman’s Algorithm](src/huffman.v)
26. Alpha-Beta Pruning
