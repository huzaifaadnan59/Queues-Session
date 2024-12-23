# Lab Tasks: Linked List and Queue Implementations

## Overview
This repository contains Python scripts implementing fundamental data structures such as linked lists and queues using arrays and deque collections. These implementations are designed to help students understand the core concepts of data structure operations such as insertion, deletion, and traversal.

---

## Lab Task 1: Linked List Implementation (`linkedlist.py`)
### Description
This script implements a singly linked list with the following operations:
- `push_back`: Adds a new element to the end of the list.
- `push_at`: Inserts a new element at a specific position in the list.
- `PrintList`: Displays all the elements of the linked list.

### How to Run
1. Clone the repository or download the `linkedlist.py` file.
2. Run the script in a Python environment:
   ```bash
   python linkedlist.py
   ```
3. The script contains example usage of the linked list methods and will display the results of these operations.

### Sample Output
```
The list contains: 10 20 30
The list contains: 10 100 20 30
The list contains: 200 10 100 20 30
```

---

## Lab Task 2: Queue Using Arrays (`queuesusingarray.py`)
### Description
This script implements a queue using NumPy arrays with the following operations:
- `enqueue`: Adds a new element to the rear of the queue.
- `dequeue`: Removes an element from the front of the queue.
- `front`: Retrieves the front element of the queue.
- `rear`: Retrieves the rear element of the queue.
- `length`: Returns the number of elements in the queue.
- `isEmpty`: Checks if the queue is empty.

### Note
The `queuesusingarray.py` script currently has some bugs (e.g., incorrect array operations). These issues need to be fixed for the script to function as intended.

### How to Run
1. Clone the repository or download the `queuesusingarray.py` file.
2. Run the script in a Python environment.
3. Modify and fix the code to explore its functionality.

---

## Lab Task 3: Queue Using Deque (`queuesusingdeque.py`)
### Description
This script implements a queue using Python's built-in `deque` class with the following operations:
- `enqueue`: Adds an element to the rear of the queue.
- `dequeue`: Removes an element from the front of the queue.
- `front`: Retrieves the front element of the queue.
- `rear`: Retrieves the rear element of the queue.
- `enqueueleft`: Adds an element to the front of the queue.
- `dequeueright`: Removes an element from the rear of the queue.

### Note
The `queuesusingdeque.py` script also contains some bugs (e.g., incorrect usage of deque methods). These issues need to be resolved for proper functionality.

### How to Run
1. Clone the repository or download the `queuesusingdeque.py` file.
2. Run the script in a Python environment.
3. Modify and fix the code to explore its functionality.

---

## Requirements
- Python 3.6 or higher
- NumPy library (for `queuesusingarray.py`)

## Repository Structure
```
.
├── linkedlist.py          # Linked List Implementation
├── queuesusingarray.py    # Queue Using Arrays
├── queuesusingdeque.py    # Queue Using Deque
└── README.md              # Project Documentation
```
