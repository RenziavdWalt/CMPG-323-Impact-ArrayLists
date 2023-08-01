# CMPG_323-Impact-ArrayLists-Development
CMPG 323: Homework1 due 3/8

Problem Description
    The code provides an implementation of a generic ArrayList data structure named MyArrayList. An ArrayList is a resizable array that allows the insertion, deletion, and retrieval of elements in a dynamic manner.

Problem-Solving Approach
    The problem-solving approach for this code is to implement a generic ArrayList data structure from scratch. The code uses an array (E[] data) to store elements of type E. The data structure provides the following functionalities:

    1. Creating an empty list: The constructor initializes an array of type E with a default capacity of 100 and sets the size to 0.

    2. Adding an element: The add method allows users to add an element of type E at a specified index. It ensures that the index is valid (within the range 0 to size). If the index is not within this range, an IndexOutOfBoundsException is thrown. The elements at and after the specified index are shifted to the right, and the new element is inserted at the index.

    3. Checking element existence: The contains method checks whether a given object exists in the list. It iterates through the elements and compares them using the equals method.

    4. Retrieving an element: The get method allows users to retrieve an element at a specified index. It ensures that the index is valid before returning the element. If the index is out of bounds, an IndexOutOfBoundsException is thrown.

    5. Removing an element: The remove method removes the element at the specified index. Similar to other methods, it checks the index's validity and throws an IndexOutOfBoundsException if the index is not within the correct range. The elements after the removed index are shifted to the left, and the size is decremented.

    6. Sorting the list: The sortList method implements a simple bubble sort algorithm to sort the elements in the list in ascending order. The elements in the list must be of a type that implements the Comparable interface to enable comparison and sorting.

    7. Getting the size of the list: The size method returns the current number of elements in the list.

Usage
    The MyArrayList class provides a basic implementation of a dynamic ArrayList data structure in Java. Users can create a new instance of MyArrayList, add elements to it, check for the existence of an element, retrieve elements by index, remove elements, sort the list, and get the current size of the list.
