# Paper-I 
## Section-A 
---
### Data Structures and Algorithms

- **Source**:`Data Structures and Algorithms.pdf`
#### Main Notes
- a finite sequence of instructions, each of which has a clear meaning and can be performed with a finite amount of effort in a finitelength of time
- The idea that the implementational details are hidden from the user
and protected from outside access is known as **encapsulation**
- In computer science, the obvious way to store an ordered collection of items is as an array.
Array items are typically stored in a sequence of computer memory locations, but to discuss
them. [1, 4, 17, 3, 90, 79, 4, 6, 81]
is an example of an array of integers.
- The standard approach in most programming languages for repeating a process a certain
number of times, such as moving sequentially through an array to perform the same operations
on each item, involves a loop.
```
for( INITIALIZATION ; CONDITION ; UPDATE ) {
REPEATED PROCESS
}

for( i = 0, sum = 0 ; i < 20 ; i++ ) {
sum += a[i];
}
```

- An **invariant**, as the name suggests, is a condition that does not change during execution of
a given program or algorithm. Invariants are also called **inductive assertions**
- loop-invariant is a condition that is true at the beginning and end of every
iteration of the given loop. Invariants are important for data
structures and algorithms because they enable correctness proofs and verification
- A list can involve virtually anything
- In order to communicate data structures between different computers and possibly different
programming languages, **XML (eXtensible Markup Language)** has become a quasi-standard.
```
<ol>
<li>3</li>
</ol>
```
- **Array vs List:** Arrays are specially optimised for arithmetic computations so if you’re going to perform similar operations you should consider using an array instead of a list.Also lists are containers for elements having differing data types but arrays are used as containers for elements of the same data type
- In context of c++: An array is a contiguous chunk of memory with a fixed size whereas a list is typically implemented as individual elements linked to each other via pointers and does not have a fixed size. Once an array is initialized, it cannot be resized, and it uses a fixed amount of memory regardless of how much stuff you put in it
- **Stacks** are, on an abstract level, equivalent to linked lists. They are the ideal data structure
to model a First-In-Last-Out (FILO), or Last-In-First-Out (LIFO), strategy in search.
- A **queue** is a data structure used to model a First-In-First-Out (FIFO) strategy. Conceptually,
we add to the end of a queue and take away elements from its front `18`
```
Imperative Programming means any style of programming where your program is structured out of instructions describing how the operations performed by a computer will happen.

Declarative Programming means any style of programming where your program is a description either of the problem or the solution - but doesn't explicitly state how the work will be done.

Functional Programming is programming by evaluating functions and functions of functions... As (strictly defined) functional programming means programming by defining side-effect free mathematical functions so it is a form of declarative programming but it isn't the only kind of declarative programming.

Logic Programming (for example in Prolog) is another form of declarative programming. It involves computing by deciding whether a logical statement is true (or whether it can be satisfied). The program is typically a series of facts and rules - i.e. a description rather than a series of instructions.

Term Rewriting (for example CASL) is another form of declarative programming. It involves symbolic transformation of algebraic terms. It's completely distinct from logic programming and functional programming.

```
- A **linked list** is a linear data structure, in which the elements are not stored at contiguous memory locations.  A linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.
- **Recusion**  `https://www.tutorialspoint.com/data_structures_algorithms/recursion_basics.html`
  Time Complexity: A call made to a function is Ο(1), hence the (n) number of times a recursive call is made makes the recursive function Ο(n).
  Space Complexity: In case of recursion, the system needs to store activation record each time a recursive call is made. Hence, it is considered that space complexity of recursive function may go higher than that of a function with iteration.

**Searching and Sorting Algorithms**
- https://www.studytonight.com/data-structures/search-algorithms
- Converting the binary search to linked list form is problematic, because there
is no efficient way to split a linked list into two segments
-  for time-critical problems, such as keeping track of aeroplanes in certain sectors of air space, it
may be totally unacceptable for the software to take too long if the worst case arises.
- https://www.geeksforgeeks.org/ for all sorting algos
**Big-O notation:**
  - 
- Bubble Sort:
  - Worst and Average Case Time Complexity: O(n*n). Worst case occurs when array is reverse sorted.
  - Best Case Time Complexity: O(n). Best case occurs when array is already sorted.
  - Auxiliary Space: O(1)
  - Boundary Cases: Bubble sort takes minimum time (Order of n) when elements are already sorted.
- Merge Sort:
  - Time Complexity: Sorting arrays on different machines. Merge Sort is a recursive algorithm and time complexity can be expressed as following recurrence relation. 
    T(n) = 2T(n/2) + θ(n)
    The above recurrence can be solved either using the Recurrence Tree method or the Master method. It falls in case II of Master Method and the solution of the recurrence is θ(nLogn). Time complexity of Merge Sort is  θ(nLogn) in all 3 cases (worst, average and best) as merge sort always divides the array into two halves and takes linear time to merge two halves.
  - Auxiliary Space: O(n)
  - Algorithmic Paradigm: Divide and Conquer
- Quick Sort:
- Heap Sort:
  - Time Complexity: Time complexity of heapify is O(Logn). Time complexity of createAndBuildHeap() is O(n) and the overall time complexity of Heap Sort is O(nLogn).

    Efficiency –  The time required to perform Heap sort increases logarithmically while other algorithms may grow exponentially slower as the number of items to sort increases. This sorting algorithm is very efficient.
    Memory Usage – Memory usage is minimal because apart from what is necessary to hold the initial list of items to be sorted, it needs no additional memory space to work
    Simplicity –  It is simpler to understand than other equally efficient sorting algorithms because it does not use advanced computer science concepts such as recursion
- Selection Sort:
    - Time Complexity: O(n2) as there are two nested loops.
    - Auxiliary Space: O(1) 
    - The good thing about selection sort is it never makes more than O(n) swaps and can be useful when memory write is a costly operation.
- Insertions Sort:
  - Time Complexity: O(n^2) 
  - Auxiliary Space: O(1)
  - Boundary Cases: Insertion sort takes maximum time to sort if elements are sorted in reverse order. And it takes minimum time (Order of n) when elements are already sorted.
  - Algorithmic Paradigm: Incremental Approach
  
  
---
#### Keywords
- correctness proofs
- invariants
- specification,verification, Performance analysis
- data structure
- abstract data types
- encapsulation
- design patterns
- loops
- arrays
- constructors, selectors and conditions
- Linked List, Doubly Linked List, Circular Linked List
- Seach Problems ,Their specification `23`
---
#### Questions
1. WHat is algorithm ?
2. What are programming paradigms ?
3. What is declarative programming and imperative programming ?
4. What is a pseudo-code ?
5. What are the questions regarding Algorithms ?
6. What is specification,verification, Performance analysis ? How to perform these ?
7. difference between list and array
8. What are invariants ?Thier other name ? What are they importent for ?
9. What is XML and what is it used for ?
10. What is a Queue, stack and Linked List ?
11. What is Abstract Data Type ADT ?
12. Difference between abstract class vs ADT
13. What is recursion ? Time and space complexity ?
14. Recursion vs iteration ?
15. What are Linked List ? Why are ADTs used even through they are less efficient ?
16.  Pictures of Array, Queue, Linked List ? Their selectors and constructors, Conditions ?
17.  Advantages of Abstract Data types ?
18.  What are the 2 searching algorithms ? Their time complexity ? Their step by step implementation ? Advantages ?
19.  Which search algo works on ordered or unordered list/array ?
20.  Do at implementation of these in c++. Once .
21.  Algorithmic Paradigm
22.  Why array based representation for Binary Heap? https://www.geeksforgeeks.org/heap-sort/
23.  What is Binary Heap? https://www.geeksforgeeks.org/heap-sort/
24.  What is Complete Binary Tree? https://www.geeksforgeeks.org/heap-sort/