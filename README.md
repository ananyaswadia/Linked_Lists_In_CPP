# Linked_Lists_In_CPP
## Aim
To tudy and implment linked lists in C++.
## Theory
In C++, a linked list is a linear data structure that allows the users to store data in non-contiguous memory locations. A linked list is defined as a collection of nodes where each node consists of two members which represents its value and a next/previous pointer which stores the address for the next/previous node.

<img width="812" height="221" alt="image" src="https://github.com/user-attachments/assets/9debc8c3-4524-44e5-8da5-f5df5acf2951" />

### Key Components of a Linked List
Node:The fundamental building block of a linked list.

Each node typically consists of:

--Data: The actual value or information stored in the node.

--Next Pointer: A pointer that stores the memory address of the next node in the sequence. In a singly linked list, this is the only pointer. In a doubly linked list, there's also a "previous" pointer.

--Head:A pointer that points to the first node of the linked list. If the list is empty, the head pointer is typically nullptr. 
### Types of Linked Lists
Based on the structure of linked lists, they can be classified into several types

-Singly Linked List

-Doubly Linked List

-Circular Linked List

<img width="801" height="230" alt="image" src="https://github.com/user-attachments/assets/55e6c5c4-60e4-4feb-99b8-88190001f694" />

<img width="801" height="196" alt="image" src="https://github.com/user-attachments/assets/3f626260-2117-4bdc-9c13-307d00f7470b" />

<img width="801" height="230" alt="image" src="https://github.com/user-attachments/assets/9236626f-a596-48ec-987f-a9b2376b6336" />

### Advantages of Linked List over arrays :
1. Efficient insertion and deletion
   
2. Implementation of Queue and Deque
   
53. Space Efficient in Some Cases
   
4. Circular List with Deletion/Addition
## Algorithms
### 1
1. Define a class Node with:

2. An integer val to store data.

3. A pointer next initialized to NULL.

4. In main():Create a new node n with value 10.

5. Print the value of the node and its next pointer.
### 2
1. Define a class Link with: An integer data an a pointer next initialized to NULL.

2. Define a function insert_head(head, data):Create a new node with the given data then Set its next to point to the current head and Update head to point to the new node.

3. Define a function disp(head):Traverse the list from head to NULL. Print each node's data.

4. In main():Initialize head as NULL then Insert nodes with values 30, 32, and 35 at the head.

5. Display the list after each insertion.

### 3
1. Define a class Node with:

    An integer val.

    A pointer next initialized to NULL.

2. In main():

    Create three nodes with values 10, 20, and 30.

    Link them manually: n1 → n2 → n3 → NULL.

    Traverse the list starting from n1.

3. Print each node's value until reaching NULL.
## Conclusion
We learnt about basic operations in linked lists.
