## 0x1B. C - Sorting algorithms & Big O
### 0. Bubble sort
Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm
* Prototype: void bubble_sort(int *array, size_t size);
* You're expected to print the array after each time you swap two elements.

Write in the file 0-O, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:
* in the best case.
* in the middle case.
* in the worst case.

### 1. Insertion sort
Write a function that sorts a doubly linked list of integers in ascending order using the insertion sort algorithm.
* Prototype: void insertion_sort_list(int *array, size_t size);
* You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
* You're expected to print the list after each time you swap two elements.

Write in the file 1-O, the big O notation of the time complexity of the insertion sort algorithm, with 1 notaton per line:
* in the best case.
* in the middle case.
* in the worst case.

### 2. Selection
Write a function that sorts an array of integers in ascending order using the Selection sort algorithm.
* Prototype: void selection_sort(int *array, size_t size);
* You're expected to print the list after each time you swap two elements.

Write in the file 2-O, the big O notation of the time complexity of the insertion sort algorithm, with 1 notaton per line:
* in the best case.
* in the middle case.
* in the worst case.


### 3. Quick sort
Write a function that sorts an array of integers in ascending order using the Quick sort algorithn.
* Prototype: void quick_sort(int *array, size_t size);
* You must implement the Lumoto partition scheme.
* The pivot should always be the last element of the partition being sorted.
* You're expected to print the array every time you swap two elements.

Write in the file 3-O, the big O notation of the time complexity of the Quick sort algorithm, with 1 notaton per line:
* in the best case.
* in the middle case.
* in the worst case.

### 4. Shell sort - Knuth Sequence
Write a function that sorts an array of integers in ascending order using the Shell sort algorithm, using the Knuth sequence.
* Prototype: void shell_sort(int *array, size_t size);
* You must use the following sequence of intervals (a.k.a the Knuth sequence)
* You're expected to print the array each time you decrease the interval.

**No big 0 notation of the time complexity of the Shell sort (Knuth sequence) algorithm needed-as the complexity is dependent on the size of the array and gap**
