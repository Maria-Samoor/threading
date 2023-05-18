What is the concept of thread?
A thread is a lightweight of process and is a basic unit of CPU utilization which consists of a program counter, a stack, and a set of registers.
Given below is the structure of thread in a process.
A process has a single thread of control where one program can counter and one sequence of instructions is carried out at any given time. Dividing an application or a program into multiple sequential threads that run in quasi-parallel, the programming model becomes simpler.
Thread has the ability to share an address space and all of its data among themselves. This ability is essential for some specific applications.
Threads are lighter weight than processes, but they are faster to create and destroy than processes.
The idea of threads is to allow multiple threads of control to execute within one process. This is often called multithreading and threads are also known as lightweight processes.
Since threads in the same process share state and stack, switching between them is less expensive than switching between separate processes.
Individual threads within the same process are not completely independent but they are cooperating and all are from the same process.
The shared resources make it easier between threads to use each other’s resources. A new thread in the same process is created by a library routine like thread_create. Similarly, thread_exit terminates a thread.

