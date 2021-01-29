In a timesharing system, several processes may be present in central memory waiting to be executed. If several processes are ready or blocked, the operating system must manage the allocation of a resource to the different processes to be executed. It is the Scheduler that performs this task using a scheduling algorithm.
Scheduling algorithms therefore help the Scheduler to select among the active processes the one that will get the use of a resource, whether it is the processor or an input/output device. 
That's why I created this process management application called ORDO-3P1B. 

ORDO-3P1B is a computer application written in Language C, easy to use and which allows to manage the processes of any program.

This program can be used by programmers, students or computer science enthusiasts, to find out how the processes of a program will be managed using a well-presented grid with explanatory comments.
Very easy to master, ORDO-3P1B makes it possible to instantly follow the evolution of a program by responding very easily to the needs of users.

It is by using the CodeBlocks programming software that I was able to program ORDO-3P1B. Establishing such an application took a lot of time because of the multitude of risks of errors that can occur as well as the great difficulty of finding the approach that the program will follow to do the work required because there are several that need to be taken into consideration. Fortunately I was able to fix almost all of the risks and scheduling algorithms.

The instructions of the project :
This project talks about creating a process management application using three types of scheduling algorithms for ready processes and only one type of scheduling algorithm for blocked processes.  
The system we are studying has a single processor and the aim is to implement three types of scheduling algorithms for ready processes, which are :

1.FIFO (First In First Out): this is one of the simplest algorithms there is. The idea is to add each process in a queue and run each process in order of arrival.

2.The Round-Robin with a TC=1: the processes access the processor, each in turn, for a predetermined time (the quantum), that is to say that when the process has access to the processor, it can only use it for a certain Quantum of time qt, and at the expiration of this quantum of time, or if it has finished its execution time it automatically leaves its place for the next process. A switching time of 1ms is required before each start and after each end of processor use. Similarly, it is assumed that processes finishing an I/O at the same time as another process finishing its quantum is given higher priority to access the CPU.

3.Priority with requisition: In a queue, the next process selected is the one with the highest priority.  When a process is taken out of the CPU at any time, it is put back into the queue at the top.
The only type of scheduling for blocked processes is called : 
- SJF (Short Job First): The SJF (shorter job first) algorithm is similar to the FIFO but instead of executing in order of arrival, one chooses to execute the one with the shortest execution time.
It should also be noted that each process is periodic, and is characterized by information loaded by the program from a TXT type file. Each line of the latter is composed of the following data separated by a semicolon : 
- The code that uniquely identifies the process
- The arrival date of the process
- The priority of the process
- Process execution time
- The time of entry and exit of the process

When the program is running, the user loads the TXT file containing the BCP of each process then he chooses the type of scheduling algorithm for the first case (without locked state) or second case (with locked state), he specifies the downtime (N) and then he receives the grid that summarizes how the processes will share the processor with or without I/O device during the first N units depending on the case used and on the type of algorithm chosen.  

<p align="center">
  <img src="/0.png">
</p>
<p align="center">
  <img src="/1.png">
</p>
<p align="center">
  <img src="/2.png">
</p>
<p align="center">
  <img src="/3.png">
</p>
<p align="center">
  <img src="/4.png">
</p>
<p align="center">
  <img src="/5.png">
</p>
<p align="center">
  <img src="/6.png">
</p>

Here the link of th video simulation : https://youtu.be/Rv5gSD1nf38

Here is my email if anyone would like to contact me : abouabdelmajidkhalil@gmail.com
 

 
 
 
 
 
 
