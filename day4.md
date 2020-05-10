
## **Hoisting**
* The definition of hoisting is that variables and function declarations are moved to the top of your code. This makes sure that you can call a function before you even declared it. 
* MDN Web docs types that this is not what really happens, everything stays exactly where you typed them within your code but all the variable and function declarations are put into memory during the compile phase.
* Only declarations are hoisted.

## **Closures**
* Closures allow the ‘inner function’ to access the variables inside of its ‘outer function’. Even if the execution context of the outer function already happened. 