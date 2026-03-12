C++ Insertion Algorithm Implementation (Ascending Order)
This approach uses a standard array and handles the logic in-place, meaning it doesn't require extra memory.

Logic Breakdown in the above C++ code

The Key Variable: This stores the value currently being "picked up" from the unsorted part. Since we start the loop at i = 1, we assume the first element (index 0) is a sorted list of one.

The Shifting Mechanism: The while loop is the engine of the algorithm. It compares the key to the elements on its left. If arr[j] > key, it copies arr[j] to the right (arr[j + 1]).

Insertion Point: Once the while loop finds an element smaller than the key (or hits the start of the array), the loop ends. We then place the key into its correct spot at arr[j + 1].
