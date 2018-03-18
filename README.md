# map-reduce

## Requirements
1: Modify the main part of the program to assign the Map or Reduce functions (in Approach Three) to a Thread Pool with a configurable number of threads. 
Lookup the Java concurrency utilities for examples of using Thread Pools. The actual number of threads can be passed to the program as a command line parameter. 
Run the program and implement some method within the program to measure as accurately as possible how long it takes to process the full set of large input text files used for testing.
Does the number of threads in the Thread Pool affect the results?

2: Create another version of the program that also implements parallel processing for the Group phase. 
As in the previous case, you should use a Thread Pool with a configurable number of threads to handle the parallel processing requirements. 
Compare the two versions of the program you have implemented by testing and measuring the total time taken to index the same set of large text files. 
Which version provides the better performance? How would your modifications to the Group Phase scale if you had a huge dataset to process?


