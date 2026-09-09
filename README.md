# BubblesAndPointersLab
**Algorithm**
```
constant MAX is max length of array

void a print value function
void a sort function
void a swap function

function sort(array):
    create integer variables i and j
    for i from 0 to MAX - 1:
        for j from 0 to MAX - 2:
            if array[j] > array[j + 1]:
                swap array[j] with array[j + 1]
                printArray(array)

function printValues (int* array)
Print the open bracket "[" to start output
Create an integer variable "i" to use as a loop counter
set i = 0
While i is less than max
    Access the value stored at position "i" in array
    Print that value
    increase i by 1

function swap(int* a, int* b)
create temporary integer variable
store value of a in temporary variable
store the value of b in the memory location of a
store the temporary value into the memory location pointed to by b

function sort(int* array)
create variable i and j
set i to 0
while is less than MAX -1:
    set j to 0
    while j is less than MAX -1:
        compare values of j and j + 1
        if j > j + 1 :
            swap the two values using swap function
            call printValues to display array after swap
        increase j by 1
    increase i by 1



