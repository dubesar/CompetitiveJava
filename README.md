## CompetitiveJava

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/for-you.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-java.svg)](https://forthebadge.com) 

### Introduction
This repository aims at helping new Java developers. It contains examples of simple programs and algorithms. 

#### Hello
Create your first Java program! 
> A "Hello, World!" program generally is a computer program that outputs or displays the message "Hello, World!". Such a program is very simple in most programming languages, and is often used to illustrate the basic syntax of a programming language. It is often the first program written by people learning to code.



### Lists
A list is one of the most popular data structures, learn to master its concept and mysteries. Mastering lists is one of many requirements to be a good developer.
#### ArrayList
>In computer science, a dynamic array, growable array, resizable array, dynamic table, mutable array, or array list is a random access, variable-size list data structure that allows elements to be added or removed. It is supplied with standard libraries in many modern mainstream programming languages. Dynamic arrays overcome a limit of static arrays, which have a fixed capacity that needs to be specified at allocation.

A dynamic array is not the same thing as a dynamically allocated array, which is an array whose size is fixed when the array is allocated, although a dynamic array may use such a fixed-size array as a back end.

[_Wikipedia_](https://en.wikipedia.org/wiki/Dynamic_array)
#### LinkedList
>In computer science, a linked list is a linear collection of data elements, whose order is not given by their physical placement in memory. Instead, each element points to the next. It is a data structure consisting of a collection of nodes which together represent a sequence. In its most basic form, each node contains: data, and a reference (in other words, a link) to the next node in the sequence. This structure allows for efficient insertion or removal of elements from any position in the sequence during iteration. More complex variants add additional links, allowing more efficient insertion or removal of nodes at arbitrary positions. A drawback of linked lists is that access time is linear (and difficult to pipeline). Faster access, such as random access, is not feasible. Arrays have better cache locality compared to linked lists. 

[_Wikipedia_](https://en.wikipedia.org/wiki/Linked_list)

#### HashMaps
> HashMap is a part of Java’s collection since Java 1.2. It provides the basic implementation of the Map interface of Java. It stores the data in (Key, Value) pairs. To access a value one must know its key. HashMap is known as HashMap because it uses a technique called Hashing. Hashing is a technique of converting a large String to small String that represents the same String. A shorter value helps in indexing and faster searches. HashSet also uses HashMap internally. It internally uses a link list to store key-value pairs already explained in HashSet in detail and further articles.

[_Wikipedia_](https://en.wikipedia.org/wiki/Hash_table)

#### HashSets
> HashSet is a part of Java’s collection since Java 1.2. It provides the basic implementation of the Set interface of Java, backed by a hash table. A set is a collection that contains no duplicate elements. More formally, sets contain no pair of elements e1 and e2 such that e1.equals(e2), and at most one null element. The HashSet implementation makes no guarantees as to the iteration order of the set; in particular, it does not guarantee that the order will remain constant over time.

[_Wikipedia_](https://en.wikipedia.org/wiki/Set_(abstract_data_type))


### Loops
Your best tools as a programmer: control flow. Looping is the quintenscence of your work, not duplicating X times your code but factorising it and leaving a small footprint.
>In computer science, control flow (or flow of control) is the order in which individual statements, instructions or function calls of an imperative program are executed or evaluated. The emphasis on explicit control flow distinguishes an imperative programming language from a declarative programming language. 
[_Wikipedia_](https://en.wikipedia.org/wiki/Control_flow)





### Search
#### Binary search
>In computer science, binary search, also known as half-interval search,[1] logarithmic search,[2] or binary chop,[3] is a search algorithm that finds the position of a target value within a sorted array.[4][5] Binary search compares the target value to the middle element of the array. If they are not equal, the half in which the target cannot lie is eliminated and the search continues on the remaining half, again taking the middle element to compare to the target value, and repeating this until the target value is found. If the search ends with the remaining half being empty, the target is not in the array.

[_Wikipedia_](https://en.wikipedia.org/wiki/Binary_search_algorithm)

#### Breadth First Search
>Breadth First Traversal (or Search) for a graph is similar to Breadth First Traversal of a tree. The only catch here is, unlike trees, graphs may contain cycles, so we may come to the same node again. To avoid processing a node more than once, we use a boolean visited array. For simplicity, it is assumed that all vertices are reachable from the starting vertex.
[_geeksforgeeks_](https://www.geeksforgeeks.org/breadth-first-search-or-bfs-for-a-graph/)

#### Depth First Search
>Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.
[_wikipedia_](https://en.wikipedia.org/wiki/Depth-first_search)

### Sorting
#### Heap Sort
>In computer science, heapsort is a comparison-based sorting algorithm. Heapsort can be thought of as an improved selection sort: like that algorithm, it divides its input into a sorted and an unsorted region, and it iteratively shrinks the unsorted region by extracting the largest element and moving that to the sorted region. The improvement consists of the use of a heap data structure rather than a linear-time search to find the maximum.

[_Wikipedia_](https://en.wikipedia.org/wiki/Heapsort)

#### Merge Sort
>In computer science, merge sort (also commonly spelled mergesort) is an efficient, general-purpose, comparison-based sorting algorithm. Most implementations produce a stable sort, which means that the order of equal elements is the same in the input and output. Merge sort is a divide and conquer algorithm that was invented by John von Neumann in 1945.[2] A detailed description and analysis of bottom-up mergesort appeared in a report by Goldstine and von Neumann as early as 1948.
[_Wikipedia_](https://en.wikipedia.org/wiki/Merge_sort)

#### Segment Tree
>In computer science, a segment tree also known as a statistic tree is a tree data structure used for storing information about intervals, or segments. It allows querying which of the stored segments contain a given point. It is, in principle, a static structure; that is, it's a structure that cannot be modified once it's built. A similar data structure is the interval tree.

[_Wikipedia_](https://en.wikipedia.org/wiki/Segment_tree)
#### Stack
> In computer science, a stack is an abstract data type that serves as a collection of elements, with two principal operations:
>* **push**, which adds an element to the collection, and
>* **pop**, which removes the most recently added element that was not yet removed.

[_Wikipedia_](https://en.wikipedia.org/wiki/Stack_(abstract_data_type))
#### Queue
>In computer science, a queue is a collection in which the entities in the collection are kept in order and the principal (or only) operations on the collection are the addition of entities to the rear terminal position, known as enqueue, and removal of entities from the front terminal position, known as dequeue. This makes the queue a First-In-First-Out (FIFO) data structure. In a FIFO data structure, the first element added to the queue will be the first one to be removed.

[_Wikipedia_](https://en.wikipedia.org/wiki/Queue_(abstract_data_type))

#### OOP
>Object-oriented programming (OOP) is a programming paradigm based on the concept of "objects", which can contain data, in the form of fields (often known as attributes or properties), and code, in the form of procedures (often known as methods). A feature of objects is an object's procedures that can access and often modify the data fields of the object with which they are associated (objects have a notion of "this" or "self"). In OOP, computer programs are designed by making them out of objects that interact with one another. There are 4 major principles:
>* **Encapsulation** is the mechanism of hiding of data implementation by restricting access to public methods. Instance variables are kept private and accessor methods are made public to achieve this.
>* **Data Abstraction** means a concept or an Idea which is not associated with any particular instance. Using abstract class/Interface we express the intent of the class rather than the actual implementation. In a way, one class should not know the inner details of another in order to use it, just knowing the interfaces should be good enough.
>* **Inheritance** expresses “is-a” and/or “has-a” relationship between two objects. Using Inheritance, In derived classes we can reuse the code of existing super classes.
>* **Polymorphism** means one name many forms. It is further of two types — static and dynamic. Static polymorphism is achieved using method overloading and dynamic polymorphism using method overriding. It is closely related to inheritance. We can write a code that works on the superclass, and it will work with any subclass type as well.

[_Wikipedia_](https://en.wikipedia.org/wiki/Object-oriented_programming), [_Medium_](https://medium.com/@cancerian0684/what-are-four-basic-principles-of-object-oriented-programming-645af8b43727)
[Harsha](https://github.com/sriharshakatakam)

