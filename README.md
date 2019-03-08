# data-types

# Index
## Primitive types
 - [Boolean](#boolean)
 - [Character](#character)
 - [Floating-point numbers](#floating-point-numbers)
 - [Fixed-point numbers](#fixed-point-numbers)
 - [Integers](#integers)
 - [Refrence](#refrence)
 - [Enumerated type](#enumerated-type)

## Composite types
 - [Array](#array)
 - [Record](#record)
 - [Union](#union)

## Abstract data types
 - [Container](#container)
 - [List](#list)
 - [Tuple](#tuple)
 - [Multimap](#multimap)
 - [Set](#set)
 - [Multiset](#multiset)
 - [Stack](#stack)
 - [Queue](#queue)
 - [Double ended Queue](#double-ended-queue)
 - [Graph](#graph)

| Structure         | order | unique |
|-------------------|-------|--------|
| List              | yes   | no     |
| Associative array | no    | yes    |
| Set               | no    | yes    |
| Multiset          | no    | yes    |

## Linear data structures
### Array
 - Array
 - Bit array
 - Bit field
 - Bitboard
 - Bitmap
 - Circular buffer
 - Control table
 - Image
 - Dope vector
 - Dynamic array
 - Gap buffer
 - Hashed array tree
 - Heightmap
 - Lookup table
 - Matrix
 - Parallel array
 - Sorted array
 - Sparse matrix
 - Iliffe vector
 - Variable-length array

### Lists
 - Doubly linked list
 - Array list
 - Linked list
 - Self-organizing list
 - Skip list
 - Unrolled linked list
 - VList
 - Conc-tree list
 - Xor linked list
 - Zipper
 - Doubly connected edge list also known as half-edge
 - Difference list
 - Free list

## Trees
### Binary trees
 - AA tree
 - AVL tree
 - Binary search tree
 - Binary tree
 - Cartesian tree
 - Left-child right-sibling binary tree
 - Order statistic tree
 - Pagoda
 - Randomized binary search tree
 - Red–black tree
 - Rope
 - Scapegoat tree
 - Self-balancing binary search tree
 - Splay tree
 - T-tree
 - Tango tree
 - Threaded binary tree
 - Top tree
 - Treap
 - WAVL tree
 - Weight-balanced tree

### B-trees
 - B-tree
 - B+ tree
 - B*-tree
 - B sharp tree
 - Dancing tree
 - 2-3 tree
 - 2-3-4 tree
 - Queap
 - Fusion tree
 - Bx-tree
 - AList

### Heaps
 - Heap
 - Binary heap
 - B-heap
 - Weak heap
 - Binomial heap
 - Fibonacci heap
 - AF-heap
 - Leonardo Heap
 - 2-3 heap
 - Soft heap
 - Pairing heap
 - Leftist heap
 - Treap
 - Beap
 - Skew heap
 - Ternary heap
 - D-ary heap
 - Brodal queue

### Trees
 - Tree (data structure)
 - Radix tree
 - Suffix tree
 - Suffix array
 - Compressed suffix array
 - FM-index
 - Generalised suffix tree
 - B-tree
 - Judy array
 - X-fast tree
 - Y-fast tree
 - Merkle tree
 - Ctree

### Multiway tree
 - Ternary tree
 - K-ary tree
 - And–or tree
 - (a,b)-tree
 - Link/cut tree
 - SPQR-tree
 - Spaghetti stack
 - Disjoint-set data structure
 - Fusion tree
 - Enfilade
 - Exponential tree
 - Fenwick tree
 - Van Emde Boas tree
 - Rose tree

### Space partitioning trees
 - Segment tree
 - Interval tree
 - Range tree
 - Bin
 - K-d tree
 - Implicit k-d tree
 - Min/max k-d tree
 - Relaxed k-d tree
 - Adaptive k-d tree
 - Quadtree
 - Octree
 - Linear octree
 - Z-order
 - UB-tree
 - R-tree
 - R+ tree
 - R* tree
 - Hilbert R-tree
 - X-tree
 - Metric tree
 - Cover tree
 - M-tree
 - VP-tree
 - BK-tree
 - Bounding interval hierarchy
 - Bounding volume hierarchy
 - BSP tree
 - Rapidly exploring random tree

### Applicatin specific trees
 - Segment tree
 - Interval tree
 - Range tree
 - Bin
 - K-d tree
 - Implicit k-d tree
 - Min/max k-d tree
 - Relaxed k-d tree
 - Adaptive k-d tree
 - Quadtree
 - Octree
 - Linear octree
 - Z-order
 - UB-tree
 - R-tree
 - R+ tree
 - R* tree
 - Hilbert R-tree
 - X-tree
 - Metric tree
 - Cover tree
 - M-tree
 - VP-tree
 - BK-tree
 - Bounding interval hierarchy
 - Bounding volume hierarchy
 - BSP tree
 - Rapidly exploring random tree

## Hashed based structures
 - Bloom filter
 - Count-Min sketch
 - Distributed hash table
 - Double hashing
 - Dynamic perfect hash table
 - Hash array mapped trie
 - Hash list
 - Hash table
 - Hash tree
 - Hash trie
 - Koorde
 - Prefix hash tree
 - Rolling hash
 - MinHash
 - Quotient filter
 - Ctrie

## Graphs
 - Graph
 - Adjacency list
 - Adjacency matrix
 - Graph-structured stack
 - Scene graph
 - Decision tree
  - Binary decision diagram
 - Zero-suppressed decision diagram
 - And-inverter graph
 - Directed graph
 - Directed acyclic graph
 - Propositional directed acyclic graph
 - Multigraph
 - Hypergraph

## Other
 - Lightmap
 - Winged edge
 - Quad-edge
 - Routing table
 - Symbol table

# Examples

# Primitive types

## Boolean

The Boolean data type represents one of two values, typically denoted as "true" and "false", intended to represent the two truth values of logic and boolean algebra. In theory you only need one "bit" to represent a boolean data type in practice this doesn't work quite well since the smallest registers avaliable on modern processors can only carry 8 or 4 bits

Booleans have become explicity represented in most "modern" languages through the use of a keyword, which may or may not be reserved by the language. In Python (since 2.3) the language reserves the words `True` and `False` to represent the two instances of a boolean, and there is `bool` which is the base class for a Boolean, C++ and a majority of other languages use the lowercase alternatives `true` and `false` where `false = 0` and `true = !false`.

## Character

A character data type represents a unit of information that roughly corresponds to a grapheme in natural language. Examples of characters include letters, numerical digits, common punctuation marks, and whitespace. The concept also includes control characters.

*wikipedia*
>The ISO/IEC 10646 (Unicode) International Standard defines character, or abstract character as "a member of a set of elements used for the organisation, control, or representation of data".

### char

A `char` in the C programming language is a data type with exactly one byte, the POSIX standard requirest it to be 8 bits.

Since Unicode requires at least 21 bits to store a single code point, it's impossible to store one inside a regular `char`, due to this Unicode can be stored in "wide characters" the original C type was called `wchar_t`. Due to some platforms defining `wchar_t` as 16 bits and others defining it as 32 bits, recent versions have added `char16_t`, `char32_t`. Even then the objects being stored might not be characters, for instance the variable-length UTF-16 is often stored in arrays of `char16_t`. 

## Floating-point numbers

## Fixed-point numbers

## Integers

## Refrence

## Enumerated type

# Composite type

## Array

## Record

## Union

# Abstract types

## Container

## List

## Tuple

## Multimap

## Set

## Multiset

## Stack

## Queue

## Double ended Queue

## Graph
