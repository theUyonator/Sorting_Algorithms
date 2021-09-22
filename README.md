# Sorting_Algorithms
This repo holds the code to several sorting algorithms including:


**bubbleSort**
  - Given an array, bubbleSort will sort the values in the array.  
  - Bubble sort is an O(n^2) algorithm. You can learn about Bubble Sort


**merge**
  - This function accepts two sorted arrays and returns a new array with values from both arrays sorted.  
  - This function should run in O(n + m) time and O(n + m) space and should not modify the parameters passed to it.  
  - Also, do not use the built in .sort() method! We’re going to use this function to implement a sort, so the helper itself shouldn’t depend on a sort.


**mergeSort**
  - Given an array, this algorithm will sort the values in the array. 
  Here’s some guidance for how merge sort should work:  
    - Break up the array into halves until you can compare one value with another. 
    - Once you have smaller sorted arrays, merge those with other sorted pairs until you are back at the full length of the array. 
    - Once the array is merged back together, return the merged (and sorted!) array
In order to implement this function, you’ll also need to implement a merge function that takes in two sorted arrays and returns a new sorted array. You implemented this function in the previous exercise, so use that function!
