# Algorithms_illustration
 
The First Algorithm we shall be looking at is called the binary search algorithm. The binary search algorithm is used to find an element in a sorted list and return the elements index in the list if present. Otherwise it will return null.
The binary algorithm works like this: in the sorted list of elements the algorithm picks the mid element and checks if it is smaller or larger then the element we are looking for. if a match occurs, then the index of the item is returned. if it is smaller all the elements that are on the left subarray are also smaller so we  dont search that subarray, we search the right sub-array. This proccess continues on the sub-array as well untill the size of the subarray reduces to zero. 
The running time for binary search is O(log n) which is way faster than simple search where the run time of simple search is O(n).

The Second Algorithm is Selection Sort algorithm. This is a simple sorting alorithm. This sorting algorithm is an in-place comparison based algorithm in which the list is divided into two parts, the sorted part at the left end and the unsorted part at the right end. Initially, the sorted part is empy and the unsorted part is the entire list.
The smallest element is selected from the unsorted array and swapped with the leftmost elements, and that element becomes a part of the sorted array. This process continues moving unsorted array boundary by one element to the right.
The running time for Selection sort algorithm is O(n^2). This is because you have to touch each element in the list twice in the worst case complexity.

The Third Algorithm is Quick Sort algorithm. Quick sort is a highly efficient sorting algorithm and is based on partitioning of array of a 
data into smaller arrays. A large array is partitioned into two arrays one of which holds values smaller than the specified value, Pivot, based on which the partition is made and another array holds values greater than the pivot value.
Quicksort partitions an array and then calls itself recusively twice to sort the two resulting subarrays. Quicksort is unique because its speed depends on the pivot you choose. In the worst case quicksort takes O(n^2) time and in the average case, quicksort takes O(nlogn) time.