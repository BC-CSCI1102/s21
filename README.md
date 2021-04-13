# CSCI 1102 Computer Science 2

Sections 04 and 05

### Spring 2021

---

[About](resources/about.md) —  [Textbooks](resources/textbooks.md) —  [Grading](resources/grading.md) —  [Canvas](https://bostoncollege.instructure.com/courses/1619778)  —  [Piazza](https://piazza.com/class/kkaaqjvvwfl2zp)  —  [Java](https://docs.oracle.com/javase/8/docs/api/index.html?overview-summary.html) — [algs4](https://algs4.cs.princeton.edu/)  — [algs4 GH](https://github.com/kevin-wayne/algs4)  —  [cuvids](https://cuvids.io/app/course/2/)  —  [Meeting](https://bccte.zoom.us/j/3306891980)  —  [Sorting](https://www.toptal.com/developers/sorting-algorithms)

---
<details>
  <summary>Administration</summary>

+ [Meets On Line](https://bccte.zoom.us/j/3306891980): Tuesdays and Thursdays 1:30PM - 2:45PM and again 3PM - 4:15PM.

> Items in `code font` below can be attached to the suffix `@bc.edu` for mail contact.

#### Instructor:

 [Robert Muller](http://www.cs.bc.edu/~muller/) **Office Hours**: Wednesdays **9AM - 11AM**, Thursdays **8:00PM - 9:30PM** [Zoom](https://bccte.zoom.us/j/3306891980), `robert.muller`

#### Teaching Assistants:

<details open> <summary>Callie Sardina, Head Teaching Assistant</summary> 

+ **Office Hours**: Thursdays, 9AM - 11AM [Zoom](https://bccte.zoom.us/j/2175950858?pwd=QkpyTkVkR0IremQ5eWFGeStIOHdXUT09), `sardinac`

</details>

<details open><summary>Kristen Bayreuther</summary>

+ **Office Hours**: Mondays 5PM - 6PM, Fridays 3:30PM - 4:30PM [Zoom](https://bccte.zoom.us/j/3535839037), `bayreutk`

</details>

<details open> <summary>Weber Meng</summary>

+ **Office Hours**: Sundays 2PM - 4PM [Zoom](https://bccte.zoom.us/j/4058045025), `mengqf`

</details>

<details open> <summary>Liam Murphy</summary>

+ **Office Hours**: Tuesdays 10:30AM - 11:30AM, Fridays 2PM - 3PM [Zoom](https://bccte.zoom.us/j/3085424208), `murpaue`

</details>

</details>

---
## Schedule

<details>
  <summary>At a Glance</summary> 
   1. Getting Started
   2. ADTs, Stacks
   3. Understanding Java
   4. Generics
   5. Queues
   6. Deques
   7. Priority Queues; Binary Heaps
   8. Order and Equality
   9. Sorting
   10. Huffman Coding
   11. Maps; Binary Search Trees
   12. Balanced Binary Search Trees
   13. Hash Tables
   14. Graphs; Shortest Paths
</details>



|                    Week                     | Mtng |            | Topic                                                        |
| :-----------------------------------------: | :--: | :--------: | :----------------------------------------------------------- |
| [1](https://github.com/BC-CSCI1102/Week01)  |  1   | R 01/16/28 | Overview, Administration, Java Setup and Introduction.       |
| [2](https://github.com/BC-CSCI1102/Week02)  |  2   | T 02/2/21  | Introduction to Java; libraries, compilation & execution     |
|                                             |  3   | R 02/4/21  | Introduction to Java                                         |
| [3](https://github.com/BC-CSCI1102/Week03)  |  4   | T 02/9/21  | ADTs — specifications & implementations                      |
|                                             |  5   | R 02/11/21 | The StringStack ADT; Postfix Expression Evaluation           |
| [4](https://github.com/BC-CSCI1102/Week04)  |  6   | T 02/16/21 | A Sequential Representation of the Stack ADT with Resizing; Understanding Java: The Class Hierarchy & Inheritance; Pros and Cons of using the `Object` class to introduce polymorphism |
|                                             |  7   | R 02/18/21 | A Linked Representation of the Generic Stack ADT; Memory     |
| [5](https://github.com/BC-CSCI1102/Week05)  |  8   | T 02/23/21 | The Queue and Deque ADTs: Singly & Doubly Linked Lists       |
|                                             |  9   | R 02/25/21 | A Sequential Implementation of Queues using Circular Arrays  |
|                      6                      |  10  | T 03/2/21  | **First Quiz**                                               |
|                                             |      | R 03/4/21  | **No Meeting**                                               |
| [7](https://github.com/BC-CSCI1102/Week07)  |  11  | T 03/9/21  | Order-sensitive data structures — the Priority Queue ADT; Binary Heaps. |
|                                             |  12  | R 03/11/21 | Quiz Review; Iteration & Recursion; Mutability               |
| [8](https://github.com/BC-CSCI1102/Week08)  |  13  | T 03/16/21 | Heapsort & Mergesort                                         |
|                                             |  14  | R 03/18/21 | Quicksort & Insertion Sort                                   |
| [9](https://github.com/BC-CSCI1102/Week09)  |  15  | T 03/23/21 | Orders & Equality; Maps                                      |
|                                             |  16  | R 03/25/21 | Working with Equality and Order in Java                      |
| [10](https://github.com/BC-CSCI1102/Week10) |  17  | T 03/30/21 | Huffman Coding                                               |
|                                             |  18  | R 04/1/21  | **Second Quiz**                                              |
| [11](https://github.com/BC-CSCI1102/Week11) |  19  | T 04/6/21  | The Map ADT: Binary Search Trees                             |
|                                             |  20  | R 04/8/21  | Binary Search Trees                                          |
|                     12                      |  21  | T 04/13/21 | Balanced Binary Search Trees; 2-3 Trees & Red/Black Trees    |
|                                             |  22  | R 04/15/21 | More on Red/Black Trees                                      |
|                     13                      |  23  | T 04/20/21 | Hashing & Hash Tables                                        |
|                                             |  24  | R 04/22/21 | More on Hashing                                              |
|                     14                      |  25  | T 04/27/21 | Skip Lists                                                   |
|                                             |  26  | R 04/29/21 | Working with Graphs                                          |
|                     15                      |  27  | T 05/4/21  | Dijkstra's Shortest Path Algorithm                           |
|                                             |  28  | R 05/6/21  | **Last Meeting** Review and wrap-up                          |



