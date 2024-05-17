# JavaScript

[MDN WebDocs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[JavaScript Info](https://javascript.info/)

![Alternative text](/home/pradip/Desktop/the_javascript_runtime_environment_example.svg)

## Call Stack
Whenever a function is called, a new frame, is added to the top of the call stack. When the function finishes executing, its stack frame is removed from the stack.

What deatils does frame contains in it?
Function Arguments:
If the function has parameters, their values are stored in the stack frame. These values are passed to the function when it's called.

Local Variables:
Any variables declared within the function are stored in the stack frame. These variables are accessible only within the scope of the function.


Return Address:
The address in memory where the execution should return after the function completes. This allows the program to continue executing from the correct point.

Saved Stack Pointer:
A pointer that indicates the location of the previous stack frame. This allows the program to return to the calling function after the current function completes.


Why you cant access local variable outside of Function?

when a function is called it's execution stack

so, after the functions execeution it would have been removed from call stack and allocated memory for local variables would have been deallocated