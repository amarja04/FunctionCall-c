# FunctionCall-c

Call by value

In this method, the called function creates new variables to store the value of the arguments passed to it.
Therefore, the called function uses a copy of the actual arguments to perform its intended task.

If the called function is supposed to modify the value of the parameters passed to it, then the change will be reflected only in the called function.
      In the calling function, no change will be made to the value of the variables. This is because all the changes are made to the copy of the variables and not to the actual variables.
      
      

Call by Reference

In this method, we declare the function parameters as references rather than normal variables.
When this is done, any changes made by the function to the arguments it received are also visible in the calling function.
      To indicate that an argument is passed using call by reference, an asterisk (*) is placed after the type in the parameter list.

Hence, in the call-by-reference method, a function receives an implicit reference to the argument, rather than a copy of its value.
