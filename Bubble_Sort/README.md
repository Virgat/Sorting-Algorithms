# 1. Bubble Sort

Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order. This algorithm is not suitable for large data sets as its average and worst-case time complexity is quite high.



Follow the below steps to solve the problem:

1. Run a nested for loop to traverse the input array using two variables i and j, such that 0 ≤ i < n-1 and 0 ≤ j < n-i-1
2. If arr[j] is greater than arr[j+1] then swap these adjacent elements, else move on
3. Print the sorted array
