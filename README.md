# Project2Design

#                                                                         Design:


## Goal:

To create a design for a queue data structure, as well as a list data structure that allows the user to insert or remove values from a given location in the list. Also to show what functions we will most likely need for the queue or list to function and what values will be needed to allow the queue to function correctly. 

## Requirements:

 Queue Data Structure - 

- First in first out
- Removes the item that has least recently been added(from Rear)
- Performs all four queue operations 
  - Dequeue 
  - Enqueue 
  - Front 
  - Rear
- Peek
- isfull
- isempty 
- Derived Data

List(Linked) Data Structure- 
-Add new elements
-Remove Elements
-Insert(Element, Index)
-Get(Index)
-Tail
-Head
-Derived Data

## Tools, Targets, Backup Plan:

Tools- 

-VS Code
-C++
-Internet 
-Textbook 
-Github
-Targets-
-Designing alone
-Testing strategy will be to create tests that are common for simple queues or lists.
-Creating simple explanations of how I would implement this structures

Backup:

-Github 
-VS Code “auto” save

## Problem(s) Breakdown:

Queue D.S.(Numbers ex: [5,4,3,2,1,0] Full Queue)-

-Create a class for the queue
-Define Empty and full for the queue 
-Define Rear
-Define Tail
-Define a capacity
-Assign values to Numbers 
-Request/Add Data
  -Ask the user to enter some data(numbers, letters, etc.)
  -Insert Data from a file or other source
  -Input your own data within your code
  -In this case the data is given from Numbers
-Define functions that check if the queue is full or not
-Define a function to get from a queue 
-Check if the queue is full or empty(In this case full since I have already decided to give Numbers) 
-If it is full then print a message to let the user know it is full.
-If it is full remove one element from the queue and add another element if needed.
-Continue until satisfied or end
-Implement pre-made tests


List D.S.:

-Define elements/nodes
-Define the linked list 
-Declare a size
-Head
-Tail
-Add an operation 
-Check to see if it is empty of full(If it is not then attach new node to old element)
-Make sure head is new element if it empty as well as the tail
-Create pointers that track elements two consecutive elements
-If there is space to add a new element, attach the pointer to the old element and old space.
-Remove an element from a specific index
  -Create index counter
  -Two pointers
  -Find desired element
  -Delete the desired element 
  -Break the connection
  -Reduce the size by one
  -Delete second element of two elements
  -Connect the elements
  -Delete current element
  -Reduce size
-To reach desired index use get
-Implement pre-made tests


## Conclusion(Since there is no implementation/code):

Queue: 

The implementation of a queue is a bit faster than a stack as it allows a consumer to download something quicker.

List: 

The implementation of a list is useful when you need to store something but do not know how much space you will need in that given moment. 





