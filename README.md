# Memory Management Simulator
An online simulation of operating system memory management to help computer science students understand the algorithm in a visual way.

* Users can input processes of a given size and length of time.
* Each process is automatically allocated to a ‘chunk’ in memory (as would be
done by an operating system).
* Memory chunks are partitioned for efficient process allocation (using the
‘Best-Fit’ strategy to reduce fragmentation).
* As the program runs, a clock ticks in the background, decrementing the time
remaining for each process.
* When a process terminates, chunks are automatically deallocated (freeing
memory).
* Memory is simulated using a doubly linked list data structure.

### Demo
A live version can be found here:
[Memory Management Simulator](http://jamiegoodson.uk/memory-management-simulator/)
