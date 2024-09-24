# OS-Project
OS Course work on pthreads

This project was part of my Operating Systems course work. 
It was required to design a PID manager that allocated a unique process identifier to each process. 
By writing a program that created a number of threads that requested and released process identifiers, I was to ensure that the data structure used to represent the availability of process identifiers is safe from race conditions. 
I have implemented the use of Pthreads mutex locks

The second part of the project was as follows:
Two separate threads (which we will term sorting threads) sort each sublist using a sorting algorithm of your choice. 
The two sublists are then merged by a third thread—a merging thread —which merges the two sublists into a single sorted list. 
Because global data are shared cross all threads, perhaps the easiest way to set up the data is to create a global array. 
Each sorting thread will work on one half of this array. 
A second global array of the same size as the unsorted integer array will also be established. 
The merging thread will then merge the two sublists into this second array. 

This programming project will require passing parameters to each of the sorting threads. 
In particular, it will be necessary to identify the starting index from which each thread is to begin sorting. 
The parent thread will output the sorted array once all sorting threads have exited.
