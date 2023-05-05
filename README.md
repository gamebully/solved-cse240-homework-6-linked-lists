Download Link: https://assignmentchef.com/product/solved-cse240-homework-6-linked-lists
<br>
Introduction

The aim of this assignment is to make sure that you understand and are familiar with the concepts covered in the lectures, including enumeration type, linked list, pointer operations, memory leak, parameter passing mechanisms, and recursion. By the end of the assignment, you should have understood and exercised

<ul>

 <li>Enumeration type and its operations</li>

 <li>Pointer operations accessing structured data</li>

 <li>Linked list of structures, with complex manipulations of pointer and structure</li>

 <li>Memory management and leak prevention</li>

 <li>Parameter passing and return values of different types.</li>

 <li>Recursive program.</li>

</ul>




<strong>Reading</strong>: Chapter 2, Textbook Section 2.5.4 on linked list and Section 2.6 on parameter passing; Section 2.10 a case study on linked list operations; and sample code in lecture slides.

<strong>Preparation</strong>: Complete the multiple choice questions in the textbook exercise section. The answer keys can be found in the course Web site. These exercises can help you prepare for your weekly quiz and the exam. You are encouraged to read the other exercise questions and make sure you understand these questions in the textbook exercise section, which can help you better understand what materials are expected to understand after the lectures and homework on each chapter.

You are expected to do the majority of the assignment outside the class meetings.   Should you need assistance, or have questions about the assignment, please contact the instructor or the TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board.  However, <strong>do not share your answers and code</strong> in the course discussion board.

Programming Assignment

<ol>

 <li>You are given a partially completed program hw06q1.c. The structure of this homework is similar to previous homework. In this homework, you should use linked list to do the same work in the previous homework.</li>

</ol>

You should follow the instructions given in the program to complete the functions so that the program executes properly. You will be completing a program that creates a linked list of books.

It is a menu-driven program where the user is given the following options:

<ol>

 <li>Add a new book to the linked list. When adding a new book to the list, the user is prompted for book name, publication year, library name and number of copies of the book. The book should be added at the end of the linked list. If the name of the book to add already exists in the list, then you should not add the book to the list.</li>

</ol>

The library name is enum type.

<ol>

 <li>Display the list of books.</li>

 <li>Remove the book from the linked list. After removing the book, the linked list should not be broken.</li>

 <li>Sort the linked list of books alphabetically by book name. The sorting should happen within the list. You should not create a new linked list of books having sorted books. You also need to implement a swap function which is to be used in the sort function.</li>

</ol>