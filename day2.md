## **Functions**
> _A function is a JavaScript procedure—a set of statements that performs a task or calculates a value._

* Functions can have a set of parameters or none at all. `function function(x) -> x is the parameter.`
* Calling a function:  `function(12) -> 12 is the argument.`


> _A higher-order function takes a function as an argument. Or returns a function as a result of calling it._

**Callback function**
   
      function sing(){
      console.log("la la la");
      }

      function meow(){
      console.log("meow meow");
      }
      sing(meow); // the argument of sing is another function.


**Arrow functions**
* instead of keyword function, you use an arrow to declare a function (=>)
* The arrow comes after de parameters and is followed by the body of the function. It can look like this:
        
          const square1 = (x) => {
          return x * x;
          };

