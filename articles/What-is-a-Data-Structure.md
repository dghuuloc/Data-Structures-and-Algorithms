# <p align="center">What is a Data Structure?</p>
---

## Introduction to Data Structure?
The data structure is a way to store and organize data in a computer system so that we can use the data easily.

Its main operations are given below:
1. `Searching` – The process of finding an element is called searching. There are two algorithms to complete the search, the first binary search and the second linear search.
2. `Sorting` – The process of arranging the data structure in a particular order is called sorting. There are many algorithms to perform sorting, such as – insertion sort, selection sort, bubble sort, radix sort, etc.
3. `Insertion` – The process of adding elements to a location is called insertion. If the size of a data structure is n, then we can insert only n-1 elements in it.
4. `Deletion` – The process of removing an element is called deletion. We can delete data from any location we want.
5. `Traversing` – Traversing means traversing each data structure element to perform a particular task.
6. `Merging` – Joining two such lists which have the same type of data elements together is called merging. From this, we get a third list.

## Characteristics of Data Structure
1. `Linear or Nonlinear` – This is the order characteristic of the data structure. It arranges the data in a sequential form.
2. `Static or Dynamic` – This characteristic defines whether the data's format, size, and memory location remain the same or change over time.
3. `Time complexity` – By this characteristic, we can understand if any algorithm is operated on the data structure, then how much time will be required in any case? (Because the less time the system takes, the more perfect it will be identified)
4. `Correctness` – By this characteristic, we can understand how precisely the data structure is implemented in the interface.
5. `Space complexity` – This characteristic defines how carefully memory usage is maintained for a data structure.

## Two Types of Data Structures
### 1. Primitive Data Structure
Primitive data structure is a data structure that can be operated directly from machine instructions. That is, it is defined by the system and the compiler.

__Example:__ Integer, Character, Float, Boolean

### 2. Non-primitive Data Structure
A non-primitive data structure is a data structure that cannot be operated by direct machine instructions. These data structures are derived from primitive data structures.

__Example:__ Array, Linked list, Stack, Queue, etc.

There are two types of non-primitive data structures:
#### a) Linear Data Structure
The linear data structure is a data structure in which data items are stored and arranged in a linear form, with one data item connected to another as a line.

__Example:__ Array, Linked list, Stack, Queue, etc.

__Application:__ Linear data structures are mainly in application software development.

#### b) Non-linear Data Structure
The non-linear data structure is a data structure in which data items are not arranged sequentially. A data item can be associated with any number of other data items.

__Example:__ Tree, Graph.

__Application:__ Non-linear data structures are in Artificial Intelligence and image processing.

## Classification Of Data Structure at a Glance
### Array
An array is a static data structure i.e. We can allocate memory only at compile time and cannot change it at run-time.

#### 1. One-dimensional (1-D) arrays:
Arrays that contain only one subscript are called one-dimensional arrays. It is used to store data in linear form.

#### 2. Two-dimensional (2-D) arrays:
The arrays in which there are two subscripts are called two-dimensional arrays. Two-dimensional arrays are also called matrices and tables.

#### 3. Multi-dimensional (m-D) arrays:
The arrays which contain more than two subscripts are called Muti-dimensional arrays.

<p align="center"><img src="https://github.com/dghuuloc/Data-Structures-and-Algorithms/blob/main/images/array.PNG"/></p>

### Linked List

### Queue

### Stack

### Hashing

### Graph

### Tree
A tree is a hierarchical data structure that stores information or data in a hierarchical manner.

#### Structure of a Tree
- A tree is a set of nodes that generally have a hierarchical relationship.
- The tree is a non-linear data structure.
- The tree has a parent-child relationship.
- We call each data item in the tree a node.
- The topmost node in the tree is called the root node.
- A node can have at most one parent. But only the root node has no parent.
- Each node in a tree can have zero or more child nodes.
- Such nodes that do not have child nodes are called leaf nodes or terminal nodes.
- Although the tree always grows upwards, the tree of the data structure always grows downwards.

<p align="center"><img src="https://github.com/dghuuloc/Data-Structures-and-Algorithms/blob/main/images/tree.PNG"/></p>

In the data structure, there are the following types of Tree:
- __General Tree__ – A tree in which a node can have either zero child nodes or can have many child nodes. This type of tree is called a general tree.
  
  In this, there is no restriction on child nodes. The topmost node of this tree is called the root node, and it can have many sub-trees.
  
- __Binary Tree__ – Binary means two numbers:- 0 and 1. A binary tree is a tree in which each node can have a maximum of two child nodes. In this, there is a restriction on child nodes because each node in a binary tree can have only two child nodes.
  
  The topmost node in a binary tree is called the root node and has only two sub-trees: the right and left.

- __Binary Search Tree__ – Binary search tree is a non-linear data structure in which a node is associated with many nodes. It is a binary tree based on a node.

- __AVL Tree__ – This is a type of binary tree. It is also called a self-balancing binary search tree. It has extra information, which is called the balance factor.

- __B-Tree__ – A B-tree is an M-Way (multi-way) tree specially designed for use in disks. A ‘B-tree’ is called a balanced tree.


## Applications of Data Structures
Data Structures are used in various fields, such as:
- Operating System
- Graphics
- Computer Design
- Blockchain
- Genetics
- Image Processing
- Simulation


