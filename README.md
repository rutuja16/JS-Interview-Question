# JS Interview Question

What is Hoisting?
In JS each and every variable declared using either var, let or const gets some memory space. 
If variable is declared using var then it will get memory space in global scope. So if you will try to access the variable in this case before initialising it then it will return “undefined”.
If variable is declared using either let or const then it will get memory space in separate scope not in global scope. So if you will try to access the variable in this case before initialising it then it will return Reference error saying you cannot access the variable before initialization.
Hoisting is a default behaviour of javascript where all the variable and function declarations are moved on top.




