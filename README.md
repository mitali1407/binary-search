# binary-search

Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. 
The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). 

![image](https://user-images.githubusercontent.com/110607289/234480445-bd5a9193-6a83-4e87-b6f7-62e6664179f5.png)

Conditions for when to apply Binary Search in a Data Structure:
To apply binary search in any data structure, the data structure must maintain the following properties:

The data structure must be sorted.
Access to any element of the data structure takes constant time.

When to use Binary Search?
When searching a large dataset as it has a time complexity of O(log n), which means that it is much faster than linear search.
When the dataset is sorted.
When data is stored in contiguous memory.
Data does not have a complex structure or relationships.

Iterative  Binary Search Algorithm:
Pseudocode of Iterative  Binary Search Algorithm:
binarySearch(arr, x, low, high)
    repeat till low = high
           mid = (low + high)/2
           if (x = arr[mid])
               return mid
          else if (x > arr[mid])
               low = mid + 1
          else
               high = mid – 1
