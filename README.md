# Big O Notation

Algorithm 1: Linear Search
Description
Given an unsorted array of integers and a target value, the linear search algorithm finds the index of the first occurrence of the target value in the array. If the target value is not found, it returns -1.

Time Complexity Analysis
The linear search algorithm iterates through the entire array, checking each element. Therefore, its time complexity is O(n), where n is the size of the array.

Algorithm 2: Bubble Sort
Description
Bubble sort is a simple sorting algorithm that repeatedly steps through the list, compares connecting elements, and swaps them if they are in the wrong order.

Time Complexity Analysis
Bubble sort has a worst-case and average-case time complexity of O(n^2), where n is the size of the array, the time it takes to sort increases squared. This means that for each element that is added to the array, bubble sort makes two comparisons to every other existing element (n * n = n^2).

Optimization
Bubble sort is inefficient for large arrays. More efficient sorting algorithms are quicksort or mergesort (both O(n log n)).
