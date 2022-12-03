### concepts

Process - process is the instance of a running program.

is instruction set as data and states

A process goes through different states from its inception to its conclusion.

Types of states:
- Creating;
- Ready;
- Running;
- Waiting for external event;
- Waiting;
- Closing;

Threds - is a way in which a process of a computer program is divided into two or more tasks that can be executed concurrently,
is the smallest processing unit

A process contains at least one thread.

ex: A program that takes two numbers, multiplies one by the other, and returns.
> contains only one execution flow.


![alt](https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/images/Chapter4/4_01_ThreadDiagram.jpg)

- A process can have several threads.
- Threads share the same address space.
- Threads execute one independent of the other.
- Thread can run concurrently or parallel.


## Goroutines

A goroutine is a lightweight thread managed by the Go runtime.

Goroutines are functions or methods that run concurrently with other functions or methods.

![alt](https://miro.medium.com/max/1400/1*mWUzwICKzj6a2lvyRYV3rg.jpeg)

