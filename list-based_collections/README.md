# List-Based Collections

## Lists

Has all properties of collections

## Arrays

Arrays have an index for entries, zero-based

Language specific:
  * Inserts (in middle of array) are linear in time
  * Deletion is linear in time

[Python lists](https://developers.google.com/edu/python/lists)
[Time complexity](https://wiki.python.org/moin/TimeComplexity)

## Linked Lists

Adding and removing is easier than arrays

Array, each element stores,
  * value 
  * index

Linked list, each element stores,
  * value
  * next, memory address to next element

Having next reference makes insertion easier, O(1), similary with deletion. Must 
update references on insertion/deletion

Doubly linked-list: can traverse linked list in two directions

## Stacks

Push and pop operations, O(1) as only interact with top element

Can implement stack with linked list: [using lists as stacks](https://docs.python.org/2/tutorial/datastructures.html#using-lists-as-stacks)

LIFO: Last in, first out
