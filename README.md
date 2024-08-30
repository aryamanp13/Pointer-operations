# Aim:
To study the call by value and call by reference in pointer


## Theory:

Call by Reference
Definition: Call by Reference means passing the address (reference) of the actual parameters to the function. This allows the function to modify the original values.

Working: The function receives pointers to the variables, and operations performed inside the function affect the original variables directly.

Call by Value
Definition: Call by Value means passing a copy of the actual parameters to the function. Changes made to the parameters inside the function do not affect the original variables.

## Algorithm:

### Call by reference

1.Start

2.Define Function swap(int *x, int *y)

3.Input: Pointers to two integers x and y

4.Output: Swapped values of the integers pointed to by x and y

5.Steps:

Make a temporary variable temp

Assign the value pointed to by x to temp (temp = *x)

Assign the value pointed to by y to the location pointed to by x (*x = *y)

Assign the value of temp to the location pointed to by y (*y = temp)

6.In main Function

Define integers a and b with 5 and 2.

Call swap(&a, &b) function

Print the value of a

Print the value of b

7.End


### Call by value

1.Start

2.Define Function swap(int x, int y)

3.Input: Two integers x and y

4.Output: Swapped values of x and y

5.Inside Swap function:

6.Create a temporary variable temp

Assign the value of x to temp

Assign the value of y to x

Assign the value of temp to y

7.Inside main Function

Define two integers a and b with 5 and 2

Call swap(a, b)

Print the value of a

Print the value of b

8.End
