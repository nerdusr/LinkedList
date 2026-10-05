Linked List in C

A generic singly linked list implementation written in C.

Features

- Push front / back
- Insert / remove by index
- Search
- Iterator
- Reverse
- Generic data with "void *"
- Ownership-aware memory management

Build

make

Test

make test

Example

List *list = list_create();

list_push_back(list, data);
list_push_front(list, data);

list_destroy(list);

Memory Management

The list can optionally take ownership of stored data through a user-provided destructor.

Project Structure

include/
src/
tests/
examples/
Makefile