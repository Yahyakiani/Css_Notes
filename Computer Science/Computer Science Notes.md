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
Declarative programming is a programming paradigm … that expresses the logic of a computation without describing its control flow.
Imperative programming is a programming paradigm that uses statements that change a program’s state.

Declarative Programming is like asking your friend to fix your car. You don’t care how to fix it, that’s up to her.

Imperative Programming is like your friend calling your father that tells her how to fix your car step by step. 
```
- 
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