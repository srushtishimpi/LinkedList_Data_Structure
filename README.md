# Linked List

Linked List is a type of Linear Data Structure. It is consist of chain of nodes where each node contains a data field and a referance or address to next node i.e. pointer to the next node as shown in diagram below.
In linked list, elements are not stored in contiguous memory locations like it did in array.
Linked list are linked using pointers and size of linked list is not fixed.

Diagram 

In linked list, there is head pointers which points to the first element in first node.
If the linked list is empty, pointer simply points to the NULL.

# Advantages of Linked List:

## Dynamic Data Structure
The size of memory can be allocated and deallocated (expanded or shrink) at the run time using insertion and deletion operations.

## Efficient Memory Utillization
As memory is allocated or deallocated according to the memory requirement during the run time, there is no wastage of memory.

## Ease of Insertion and Deletion
Insertion and deletion operations on linked list is simpler than insertion and deletion operations on an array, since there is no need to shift the elements after insertion and deletion operations. Just address of the node is needed to be updated.

## Implementation
Various advance data structures can be implemented using linked list like stack, queue and graph.

# Disadvantages of Linked List:

## Cache
Linked list is not a cache friendly data structure.

## Extra Memory
Every node in a linked list takes extra memory to store the pointers to next node, which is why it requires more memory than array to store same number of elements.

## Random Access
The randome access to the nodes of the linked list is not allowed due to dynamic memory allocation. We have to start access from the first head node.


# Applications of Linked List

- Linked List is used in memory management.
- Linked List is used in linked allocation of files.
- Linked List is used in implementing stack, queue and graphs.
- Linked List is used to store history of visited pages.
- Linked List is used to perform undo operations.
- Linked List is used in operation of playing music playlist.

# Types of Linked List
- Singly Linked List
- Doubly Linked List
- Circular Linked List
- Circular Doubly Linked List

## Singly Linked List
In this type of linked list one can move or traverse the linked list in only one direction. Each node in singly linked list has only one pointer which points to the next node. And the pointer in the last node of singly linked list point to NULL. This linked list starts from the first node and ends at last node. Traversing is more time consuming and reverse traversing is not possible in singly linked lists.


Diagram

## Doubly Linked List
In this type of linked list, linked list can move or traverse in both forward and backward directions. Each node of doubly linked list contains left pointer, a data, and a right pointer. Left pointer points to the previous node of doubly linked list whereas right pointer points to next node of doubly linked list. Right pointer od last node points to null.

DIagram

## Advantages of Doubly Linked List
- Doubly linked list can move in both forward and backward directions.
- In doubly linked list deletion operation is easy if address of the node is given.
- Doubly linked list can quickly insert node before given node.

## Disadvantages of Doubly Linked List
