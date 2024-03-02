# quick-sort

Example of quick sort.

Quick sort is a popular sorting algorithm that follows the "divide and conquer"
strategy to efficiently sort elements in an array or a list. Here's how it works:

1. Choose a Pivot: Pick an element from the array to serve as the pivot. The
   choice of pivot can significantly affect the algorithm's performance. Common
   strategies include selecting the first element, the last element, the median
   element, or a randomly chosen element.
2. Partitioning: Rearrange the elements in the array so that all elements less
   than the pivot are placed before it, and all elements greater than the pivot
   are placed after it. After this partitioning step, the pivot is in its final
   sorted position.
3. Recursion: Recursively apply the above steps to the sub-arrays formed by the
   partitioning step. That is, apply quick sort to the sub-array of elements
   less than the pivot and the sub-array of elements greater than the pivot.
4. Base Case: The recursion terminates when the sub-arrays become empty or
   contain only one element, as they are inherently sorted.
5. Combine: No combining step is needed in quick sort, as the sorting is done
   in-place by partitioning the array.

Quick sort is efficient on average and in the best case, with an average time
complexity of O(n log n). However, its worst-case time complexity is O(n^2),
which occurs when the pivot selection consistently results in highly unbalanced
partitions. Nevertheless, with good pivot selection strategies and
implementations that handle edge cases effectively, quick sort is widely used in
practice.
