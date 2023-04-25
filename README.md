# Binary-search
Binary search is an efficient algorithm used to search for a specific value in a sorted array or list. It works by repeatedly dividing the search interval in half until the target value is found or determined to be not present in the array.
# Algoritm
Here is a step-by-step explanation of how binary search works:

1. Start by identifying the middle element of the sorted array.
2. Compare the middle element to the target value.
3. If the middle element is equal to the target value, the search is complete and the index of the target element has been found.
4. If the middle element is greater than the target value, the search continues in the left half of the array.
5. If the middle element is less than the target value, the search continues in the right half of the array.
6. Repeat steps 1-5 with the new search interval until the target value is found or determined to be not present in the array.

Let's take an example to illustrate how binary search works. Consider the following sorted list of integers:

`[2, 4, 6, 8, 10, 12, 14, 16, 18, 20]`

Suppose we want to find the index of the element `10`. We start by identifying the middle element of the list, which is `10`. Since `10` is the target value, the search is complete and we have found the index of the target element.

Now suppose we want to find the index of the element `15`. We start by identifying the middle element of the list, which is `10`. Since `15` is greater than `10`, we know that the target value must be in the right half of the list. We repeat the search with the right half of the list, which consists of the elements:

`[12, 14, 16, 18, 20]`

We identify the middle element of this list, which is `16`. Since `15` is less than `16`, we know that the target value must be in the left half of this list. We repeat the search with the left half of this list, which consists of the elements:

`[12, 14]`

We identify the middle element of this list, which is `14`. Since `15` is greater than `14`, we know that the target value must be in the right half of this list. We repeat the search with the right half of this list, which consists of the element:

`[16]`

We identify the middle element of this list, which is `16`. Since `15` is less than `16`, we know that the target value is not present in the list.

Binary search has a time complexity of O(log n), which makes it an efficient algorithm for searching sorted arrays or lists. It can be used in a wide range of applications, such as searching for a specific item in a database or finding a value in a sorted data structure.
# Application
Binary search has a wide range of applications in computer science and beyond. Here are a few examples:

1. Searching in databases: Binary search is often used to search for specific items in large databases, such as phone directories, customer lists, or product catalogs.

2. Sorting algorithms: Binary search is used in some sorting algorithms, such as quicksort, to partition the data into subarrays and sort them recursively.

3. Game development: Binary search can be used to search for specific items or values in games, such as finding the location of a hidden object or the value of a game variable.

4. Image processing: Binary search can be used to find the threshold value in image processing applications, which is the pixel intensity value that separates the foreground and background regions of an image.

5. Machine learning: Binary search can be used to find the optimal value of a parameter in machine learning algorithms, such as the learning rate in gradient descent optimization.

6. Network routing: Binary search can be used to search for the shortest path between two nodes in a network by dividing the search space into smaller subspaces.

# Screenshot
![p5](https://user-images.githubusercontent.com/126184012/234291392-465dd3c9-d411-4149-9f0e-e02026848408.png)
