# Linked List

Linked List is a type of Linear Data Structure. It is consist of chain of nodes where each node contains a data field and a referance or address to next node i.e. pointer to the next node as shown in diagram below.
In linked list, elements are not stored in contiguous memory locations like it did in array.
Linked list are linked using pointers and size of linked list is not fixed.

![1](/images/1.jpg)

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

# Singly Linked List
In this type of linked list one can move or traverse the linked list in only one direction. Each node in singly linked list has only one pointer which points to the next node. And the pointer in the last node of singly linked list point to NULL. This linked list starts from the first node and ends at last node. Traversing is more time consuming and reverse traversing is not possible in singly linked lists.


Diagram

# Doubly Linked List
In this type of linked list, linked list can move or traverse in both forward and backward directions. Each node of doubly linked list contains left pointer, a data, and a right pointer. Left pointer points to the previous node of doubly linked list whereas right pointer points to next node of doubly linked list. Right pointer od last node points to null.

DIagram

## Advantages of Doubly Linked List
- Doubly linked list can move in both forward and backward directions.
- In doubly linked list deletion operation is easy if address of the node is given.
- Doubly linked list can quickly insert node before given node.

## Disadvantages of Doubly Linked List
- Doubly linked list requires extra memory space to store left and right pointers in each node.
- Doubly linked list is considered more complex as all the operation of this type of linked list requires extra previous (left) pointer to be maintained.

# Circular Linked List
In Circular linked list, every node is linked and every node has a successor, i.e. every node has pointer to next node. In circular linked list, pointer of the last node points to the first node. Because of this feature, this type of linked lists are circular in nature.

Diagram

## Advantages of Circular Linked List
- In Circular linked list, it is possible to move or traverse from last node to the first node of linked list.
- In Circular linked list, starting node does not matter as in Circular linked list every node can be a starting node.
- In Circular linked list, we can easily identify the previous nodes.
- There is no need for the null function as Circular linked list has no end node.
- Circular linked lists are beneficial for end opernations as start and end of these linked list coincides.
- As an example of circular linked list, algorithms such as Round Robin Setup can effectively complete online queues without having to meet null suspensions on referance referances.

## Disadvantages of Circular Linked List
- If not handled properly, Circular linked list can lead to infinite loop.
- Circular linked list is more complex in nature than other linked lists.
- Because of circular nature, it is very difficult task to reverse a Circular linked list.

# Circular Doubly Linked List
This linked list is a combination of circular linked list and doubly linked list where each node has a left pointer which points to previous node and right pointer which points to next node. Here, right pointer of the first node points to first node as next node and left pointer of the first node points to last node as previous node. Therefore it becomes circular in nature as well as can move or travese in both back and forth directions. 

diagram

## Advantages of Circular Doubly Linked List
- Circular Doubly Linked List is easy for data manipulation.
- In Circular doubly linked list, it is possible to move or traverse from last node to the first node of linked list.
- In Circular doubly linked list, starting node does not matter as in Circular linked list every node can be a starting node.
- There is no need for the null function as Circular doubly linked list has all node connected from left and right pointers in circular nature

## Disadvantages of Circular Doubly Linked List
- Circular doubly linked list requires extra memory space to store left and right pointers in each node.
- If not handled properly, Circular doubly linked list can lead to infinite loop.
- Circular doubly linked list is more complex in nature than other linked lists.
- Because of circular nature, it is very difficult task to reverse a Circular doubly linked list.

# Time Compelxity of Linked List

| Action  | Worst Case | Average Case  | Best Case |
| :--------------------: | :-------------: | :-------------: | :-------------: |
| Accessing Element  | O(n)  | O(n)  | O(1)  |
| Deleting Element (After Search) | O(1)  | O(1)  | O(1)  |
| Inserting Element (After Search) | O(1)  | O(1)  | O(1)  |
| Searching Element  | O(n)  | O(n)  | O(1)  |
| Traversing Element  | O(n)  | O(n)  | O(n)  |
| Accessing Element (Skip list) | O(n)  | O(log n)  | O(log n)  |
| Deleting Element (Skip list) | O(n)  | O(log n)  | O(log n)  |
| Searching Element (Skip list) | O(n)  | O(log n)  | O(log n)  |
| Traversing Element (Skip list) | O(n)  | O(log n)  | O(log n)  |


# Algorithm Compelxity of Linked List

| Action  | Worst Case Time Complexity | Average Case Time Complexity  | Best Case Time Complexity | Space Complexity | 
| :--------------------: | :-------------: | :-------------: | :-------------: | :-------------: |
| Merge Sort  | O(log n)  | O(log n)  | O(log n)  | O(n)  |
| Bubble Sort | O( $n^2$ )  | O( $n^2$ )  | O(n)  |O(1)  |
| Selection Sort | O( $n^2$ )  | O( $n^2$ )  | O( $n^2$ )  |O(1)  |
| Insersion Sort | O( $n^2$ )  | O( $n^2$ )  | O(n)  |O(1)  |
| Linear Search  | O(n)  | O(n)  | O(1)  |O(1)  |


# Programs
    
## Singly Linked List
