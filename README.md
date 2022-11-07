TITLE:  
    Implement merge sort and multithreaded merge sort. Compare time required by both the algorithms. Also analyze the performance of each algorithm for the best case and the worst case.
        
        1. Implement merge sort and multithreaded merge sort.
        2. Compare time required by merge sort and multithreaded merge sort. Also analyze the performance of each algorithm for the best case and the worst case.

MULTITHREADED MERGE SORT:
    Merge Sort is a popular sorting technique which divides an array or list into two halves and then start merging them when sufficient depth is reached. Time complexity of merge sort is O(nlogn).                                   
  	Threads are lightweight processes and threads shares with other threads their code section, data section and OS resources like open files and signals. But, like process, a thread has its own program counter (PC), a register set, and a stack space.
multi-threading is way to improve parallelism by running the threads simultaneously in different cores of your processor. 

TIME COMPLEXITY COMPARISON: 
    The time complexity of merge sort is O(n*log n).  The time complexity of Multithreaded Merge sort is O(n*log n).O(n log2 n)
Running the algorithm in parallel does not become efficient until the size of the data sets reach 2 ^16.

