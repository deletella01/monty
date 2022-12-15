## C - Stacks, Queues - LIFO, FIFO

## The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

### Monty byte code files.

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument.


### Stack
A stack in C is nothing but a linear data structure that follows the LIFO rule (Last In First Out). In a stack, both insertion and deletion take place from just one end, that is, from the top.

We can implement a stack in C in 2 ways:

Statically: Array implementation of stacks allows the static memory allocation of its data elements. It is important to note that in this method, the stack acquires all the features of an array.

Dynamically: Linked list implementation of stacks follow the dynamic memory allocation of its data elements. It is important to note that in this method, the stack inherits all the characteristics of a linked list in C.


The C stack functions basically include:

Insertion
In a stack, the operation of inserting an element into the stack is referred to as pushing an element in the stack. The elements are inserted into the stack from the top and hence would compel the elements to shift.

Deletion
In a stack, the operation of deleting an element into the stack is referred to as popping an element in the stack. The deletion of a data element from the stack is done from the top.


Display
The stack data elements are displayed in the stack according to the LIFO rule.


### Queue 
In contrast to a stack, a queue in C is nothing but a linear data structure that follows the FIFO rule (First In First Out). Insertion is done from the back (the rear end) and deletion is done from the front.

We can implement a queue in 2 ways:

Statically: Array implementation of queues allows the static memory allocation of its data elements. It is important to note that in this method, the queue acquires all the features of an array.

Dynamically: Linked list implementation of queues follow the dynamic memory allocation of its data elements. It is important to note that in this method, the queue inherits all the characteristics of a linked list.

The queue functions basically include:

Insertion
Insertion of elements into the queue takes place from the rear end and hence would force the elements to shift forward. Inserting an element into the queue is also called enqueue.

Deletion
In a queue, the deletion of data elements is done from the front. Deleting the element from the queue is also called dequeue.

Display
The stack data elements are displayed in the queue according to the FIFO rule.

