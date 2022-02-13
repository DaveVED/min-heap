# Min Heap
A Min-Heap is a binary tree such that:
- The value in each internal node is smaller than or equal to the values in the children of that node
- The binary tree is complete 

Example of Min Heap :  

            5                      13
         /      \               /       \  
       10        15           16         31 
      /                      /  \        /  \
    30                     41    51    100   41

## Operations Implemented:
- buildHeap()
    - Build the Min Heap
- heapify()
    - Process to convert the binary tree into the Min Heap
- extrachMin()
    - Removes the minimum element from the Min Heap
- heapInsert()
    - Inserts a new key into the Min Heap
- heapSort()
    - Sorts the Min Heap
    
## Folder Structure
### ./src
Contains source code implementation for min-heap
### ./tests
Contains test cases to verify all the implemetned operatsions and ensure they run in a sufficent time complexity

#### Tree Structure
```
├── README.md
├── setup.py
├── src
│   ├── __init__.py
│   └── min_heap.py
└── tests
    ├── __init__.py
    └── min_heap_tests.py
```
## How to Run
To execute and test the min-heap program simply run the ```tests/heap_tests.py``` file which will test and verify all the implemetned operatsions and ensure they run in a sufficent time complexity

```
$ python3 setup.py install --user
$ python3 tests/min_heap_tests.py
#test_heapify
Heapify length 1: True
Heapify two out of order: True
Heapify two in order: True
Heapify five needing swap: True
Heapify five needing recursive swap: True
Heapify five with limit number: True
#test_build_heap
buildHeap(shuffled_list(5, 5)) is a min heap:  True
buildHeap(shuffled_list(10, 10)) is a min heap:  True
buildHeap(shuffled_list(15, 15)) is a min heap:  True
buildHeap(shuffled_list(20, 20)) is a min heap:  True
buildHeap(shuffled_list(25, 25)) is a min heap:  True
buildHeap(shuffled_list(30, 30)) is a min heap:  True
buildHeap(shuffled_list(35, 35)) is a min heap:  True
buildHeap(shuffled_list(40, 40)) is a min heap:  True

#test_insert_extract
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True
Correctly extracted min: True, maintained heap property: True

#test_heap_sort:
Correctly sorted 1000 shuffled: True

#test_counts:
Counts for list of len: 400
buildHeap heapify calls within 20% of expected number of calls: True
heapExtractMin heapify calls within 20% of expected number of calls: True
heapInsert swap calls within 20% of expected number of calls: True
Counts for list of len: 10000
buildHeap heapify calls within 20% of expected number of calls: True
heapExtractMin heapify calls within 20% of expected number of calls: True
heapInsert swap calls within 20% of expected number of calls: True
Counts for list of len: 100000
buildHeap heapify calls within 20% of expected number of calls: True
heapExtractMin heapify calls within 20% of expected number of calls: True
heapInsert swap calls within 20% of expected number of calls: True
```


