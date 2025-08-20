# AIM: To study and implement C++ Pointer basics
## SOFTWARE USED:Visual Studio
### Theory:A pointer is a unique type of variable that stores the memory address of another variable instead of holding the actual value directly. Pointers enable programs to efficiently access and manipulate memory, making them essential for system-level programming and managing dynamic memory. Accessing a pointer directly retrieves the address it contains, not the data stored at that location.

Assigning Address:

The address-of operator (&) provides the memory address of any variable in C++. This address can be assigned to a pointer to initialize it with the location of the variable.

Dereferencing:

Dereferencing refers to obtaining the value stored at the memory location a pointer points to. The * operator is used to dereference a pointer and access its value.

Uses of Pointers:

Pointers are an important concept in C++ that allow direct interaction with memory, giving more control over data manipulation. Key applications include:

Dynamic Memory Allocation: Pointers enable memory allocation during program execution using new and delete, allowing the creation of objects or arrays whose sizes are determined at runtime.

Implementing Data Structures: Pointers are fundamental for building linked lists, trees, and graphs, where elements are dynamically allocated and interconnected.

Passing Arguments by Pointer: Pointers allow passing the address of variables so that functions can modify the original values directly.

Implementation:

Pointers in C++ can be implemented through various examples, such as:

Incrementing pointers

Adding or subtracting pointers

Reversing an array with pointers

Printing a string using a pointer

Algorithms:

Reverse an Array Using Pointers

Start

Declare an integer array arr[5].

Display "Enter the Elements of the array:".

For i from 0 to 4:

Read arr[i].
Display "The Array is:" followed by each element of arr in order.

Declare a pointer array arr1[5].

Set arr1[5] = &arr[5] (pointer to the element after the last element).

Display "The reversed array is:".

For i from 0 to 4: Display (arr1[5] - i - 1) (access elements in reverse).

End

Demonstrating Pointer Arithmetic with Different Data Types

Start

Declare an integer x = 123.
Declare an integer pointer x1 storing the address of x.
Display "Integer Address Before increment:" followed by x1.
Increment x1 by 1 and display "Integer Address After increment:" followed by x1.

Declare a float y = 6.9.
Declare a float pointer y1 storing the address of y.
Display "Float Address Before increment:" followed by y1.
Increment y1 by 1 and display "Float Address After increment:" followed by y1.

Declare a double z = 678910890.
Declare a double pointer z1 storing the address of z.
Display "Double Address Before increment:" followed by z1.
Increment z1 by 1 and display "Double Address After increment:" followed by z1.

Declare a boolean t = true.
Declare a boolean pointer t1 storing the address of t.
Display "Boolean Address Before increment:" followed by t1.
Increment t1 by 1 and display "Boolean Address After increment:" followed by t1.

End

Conclusion:

The concept of pointers was explained along with practical examples demonstrating their implementation in C++.
