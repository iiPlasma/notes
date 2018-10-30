# Topic: Sorting Algorithms
## Merge Sort
### Merge Sort
- Split the array into two halves. Recursively sort each half.

- To merge 2 sorted arrays, create an empty array to hold the combined. Put a finger
at the beginning of both. Copy the lesser of the two keys into the next empty cell and advance one position.
Continue doing this till one array runs out. Move the rest of the array.

### Quick Sort
- Partition the array so that everything in the left part is less than everything in the right part.

- Recusively sort each half. >All the work is done in the partition algorithm

### Selection Sort
- Find the smallest element in the array and swap into the first cell. The first cell is now 
correct so don't touch it. Repeat the process until each cell is correct.

### Insertion Sort
- Divided the array into sorted(left) and unsorted(right) sections. Start the size of the section
sorted at 1. Take the first element following the sorted secioin and march it down into it's correct position
in the sorted section, increasing the size of the sorted section by 1 for each element.

### Bubble Sort
- From beginning to end, compare each element to it's neighbor, swapping if they are out of place. After each
run, one more element is in its correct position at the end of the array, so repeat n *(really n-1)* times.

