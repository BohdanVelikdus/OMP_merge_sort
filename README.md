# OMP_merge_sort
This is an implementation of merge sort, using OpenMP library to parallelize computation.
Here I used task granularity and cut-off principle, which means I create a new only if I do not reach the ```DEPTH```
You can modify the ```DEPTH``` to see how much time does it take to execute sorting. 
Also, here used recursive type of merge sorting.

### To Start(For Unix systems)

1. Copy the code directly from file, or copy repository 
2. Check if on your PC is installed OpenMP
3. Build a project(example for g++): ```g++ -fopenmp ompMergeSort.cpp -o ompMergeSort```
4. Execute: ```./ompMergeSort```

In the output you see the time(microSeconds) ellapsed from start of the computation.
