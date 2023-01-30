# Activities

## Task 1

Watch this video (~2min):
https://youtu.be/ohSzM7WtwOk

Discuss the difference between:

- Queue vs Stack
- LIFO vs FIFO

LIFO = last in first out (plate stack example)
FIFO = First in first out, (shopping line)
## Task 2

- Use the following link to push/pop data from the stack:
  https://www.cs.usfca.edu/~galles/visualization/StackArray.html
- Use the following tool to enqueue / dequeue data from the queue:
  https://www.cs.usfca.edu/~galles/visualization/QueueArray.html

## Task 3

- What is the difference between Array Implementation and the Linked List Implementation of Stacks. Refer to the following link:
  https://www.cs.usfca.edu/~galles/visualization/StackLL.html
Array Implementation and Linked List Implementation are two different ways of implementing a Stack data structure.

Array Implementation:

    The stack is implemented using an array.
    The top of the stack is represented by the last element of the array.
    Insertion and deletion operations are performed by incrementing or decrementing the top pointer, respectively.
    The size of the stack is fixed, so if the stack overflows, a new array must be created and all the elements must be copied over.

Linked List Implementation:

    The stack is implemented using a linked list.
    The top of the stack is represented by the head of the linked list.
    Insertion and deletion operations are performed by adding or removing a node from the head of the linked list, respectively.
    The size of the stack is dynamic and can be increased or decreased as required.

In terms of space and time efficiency, the Linked List Implementation generally uses more memory than the Array Implementation because it requires extra memory for the pointers, but it has the advantage of being able to dynamically change the size of the stack without having to reallocate memory. On the other hand, the Array Implementation is faster for accessing elements as all elements are stored in contiguous memory, but has the disadvantage of having a fixed size.

- What is the difference between Array Implementation and the Linked List Implementation of Queues. Refer to the following link:
  https://www.cs.usfca.edu/~galles/visualization/QueueLL.html

  Array Implementation and Linked List Implementation are two different ways of implementing a Queue data structure.

Array Implementation:

    The queue is implemented using an array.
    The front of the queue is represented by the first element of the array, and the rear of the queue is represented by the last element of the array.
    Insertion operations are performed by incrementing the rear pointer, and deletion operations are performed by incrementing the front pointer.
    The size of the queue is fixed, so if the queue overflows, a new array must be created and all the elements must be copied over.

Linked List Implementation:

    The queue is implemented using a linked list.
    The front of the queue is represented by the head of the linked list, and the rear of the queue is represented by the tail of the linked list.
    Insertion operations are performed by adding a node to the tail of the linked list, and deletion operations are performed by removing a node from the head of the linked list.
    The size of the queue is dynamic and can be increased or decreased as required.

In terms of space and time efficiency, the Linked List Implementation generally uses more memory than the Array Implementation because it requires extra memory for the pointers, but it has the advantage of being able to dynamically change the size of the queue without having to reallocate memory. On the other hand, the Array Implementation is faster for accessing elements as all elements are stored in contiguous memory, but has the disadvantage of having a fixed size.

## Links

- https://www.educative.io/blog/data-structures-stack-queue-java-tutorial
