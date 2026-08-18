# DAA-PRACTICAL-01
Summary:

In this practical, different sorting algorithms—Bubble Sort, Selection Sort, Merge Sort, Quick Sort, and Insertion Sort—were implemented using Python. The algorithms were tested with user-provided input, and the sorted output and execution time were observed. Their time and space complexities were also studied. The practical helped in understanding the working process, efficiency, and differences between simple sorting algorithms and divide-and-conquer sorting algorithms.

Conclusion:

The practical was successfully completed, and all the sorting algorithms produced the correct sorted output. Bubble Sort, Selection Sort, and Insertion Sort are simple and suitable for small datasets, but they generally require more time for large datasets. Merge Sort and Quick Sort are more efficient for larger datasets because they use the divide-and-conquer approach. Thus, the practical provided a clear understanding of sorting techniques and the importance of time and space complexity in selecting an appropriate sorting algorithm.

Summary
The programs implement Linear Search and Binary Search to find a target number in a list. Both programs take numbers and a target value as input, display whether the target is found, return its index, and measure the execution time. The Linear Search program checks each element one by one and has O(1) best-case and O(n) average/worst-case time complexity. � The Binary Search program repeatedly checks the middle element and reduces the search range; it works by comparing the target with the middle value. �
linearsearch.py
binarysearch.py
Conclusion
Linear Search is simple and can be used for any list, but it may take more time for large datasets. Binary Search is generally faster because it reduces the search range in every step, but it requires the list to be sorted. Therefore, Linear Search is suitable for small or unsorted lists, while Binary Search is more efficient for large sorted lists.

Summary
The program implements Heap Sort using a Max Heap. It first builds a max heap from the input array using the heapify() function. The largest element is then repeatedly moved to the end of the array, and the remaining elements are heapified again. The program also measures the execution time and displays the sorted list. �
maxheap.py
Conclusion
The Heap Sort algorithm successfully sorts the given list of integers in ascending order. The program demonstrates the use of a Max Heap and reports O(n log n) time complexity for the best, average, and worst cases. �
