# FIFORule
Basic Operations of Queue
A queue is an object (an abstract data structure - ADT) that allows the following operations:

Enqueue: Add an element to the end of the queue
Dequeue: Remove an element from the front of the queue
IsEmpty: Check if the queue is empty
IsFull: Check if the queue is full
Peek: Get the value of the front of the queue without removing it

![download](https://user-images.githubusercontent.com/101993714/210170097-542f4568-4d36-47ec-a4e0-223089bcbeca.jpg)

Enqueue Operation
check if the queue is full
for the first element, set the value of FRONT to 0
increase the REAR index by 1
add the new element inthe position pointed to by REAR!

 
![download](https://user-images.githubusercontent.com/101993714/210170128-3ca9f015-335f-4d25-8f73-65a0c7327972.jpg)

Dequeue Operation
check if the queue is empty
return the value pointed by FRONT
increase the FRONT index by 1
for the last element, reset the values of FRONT and REAR to -1

![download](https://user-images.githubusercontent.com/101993714/210170172-7b533939-bae5-41da-8867-41c1e84f2be9.png)
  

 
