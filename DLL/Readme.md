# Doubly Linked Lists
## Introduction
Doubly linked lists are similar to linked lists, but with the added feature of each node having a reference to both the next and the previous node in the list.

## How Doubly Linked Lists Work
Each node in a doubly linked list contains three fields:
- The data stored in the node
- A reference to the next node in the list
- A reference to the previous node in the list

The first and last nodes in the list are known as the head and tail nodes, respectively. The head node is the first node in the list, and the tail node is the last node in the list. Both of these nodes have a reference to NULL in their "previous" or "next" field, depending on which end of the list they are.

When we want to insert a new node into a doubly linked list, we need to update the "next" and "previous" references of the surrounding nodes. For example, to insert a new node between node A and node B, we need to set the "next" field of node A to point to the new node, and the "previous" field of node B to point to the new node.

## Advantages of Doubly Linked Lists
Doubly linked lists have several advantages over other types of data structures, including:

- Bidirectional traversal: Since each node has a reference to the previous node in the list, we can easily traverse the list in both directions.
Insertion and deletion: Adding or removing a node from a doubly linked list is relatively easy, as we only need to update the "next" and "previous" references of a few nodes.
- Dynamic size: Doubly linked lists can grow or shrink dynamically as needed, which can be very useful in certain applications.