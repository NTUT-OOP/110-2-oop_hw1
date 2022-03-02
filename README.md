# Specification
Write a program that can receive object type, width, length or radius, and calculate its area

## Input
There are 3 shape types: circle, triangle, rectangle
Example:
area.out [type] [w] [l]

## Output
Print the size of input shape directly. Example:
```
> area.out triangle 3 4
> 6
```

# Requirements

We have provided a template. Create a “shapes.h” file and define 4 classes with area() function. The 4 class you need to write are:
Base class: Shape
Derived class: Circle, Triangle, Rectangle

## Compile Your Code

We include a Makefile. Just type “make”


## Test your code
Example, execute the command on Linux
```
kt@ntut:~/oop/hw1$ make
kt@ntut:~/oop/hw1$ ./area.out rectangle 2 4.5
kt@ntut:~/oop/hw1$ 9
```