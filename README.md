# Astana IT University
# Algorithms and Data Structures(Assignment-2)
Ospanova Tomiris(SE-2202)


MyArrayList

- `MyArrayList` is an implementation of the MyList interface using an array-based data structure. It provides a simple dynamic array that grows as needed to accommodate new elements.

Constructors
- `MyArrayList()` - creates a new empty list with an initial capacity of 10.
Public methods
- `void add(E element)` - adds the specified element to the end of the list. If the list is full, it will be automatically resized to twice its current capacity.
- `E get(int index)` - returns the element at the specified index. Throws IndexOutOfBoundsException if the index is out of range.
- `void remove(int index)` - removes the element at the specified index. Throws IndexOutOfBoundsException if the index is out of range.
- `int size()` - returns the number of elements in the list.
