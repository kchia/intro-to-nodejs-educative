# Quiz Yourself on Introduction to Node.js Part III - JavaScript Essentials Review

1. Take a look at the code below. What will be logged to the console?

```js
const name = "Robert";
name = "Robbie";
console.log(name);
```

A) `null`
B) `Robbie`
C) `SyntaxError: Assignment to constant variable.`
D) `TypeError: Assignment to constant variable.`
**Answer: D** 

2. True or False: `var` variables cannot be updated and re-declared within its scope. `let` variables can be updated but not re-declared within its scope.

A) True
B) False
**Answer: B** 

3. Take a look at the code below. What will be logged to the console?

```js
let { a, b, ...pairs } = { a: 10, b: 20, c: 30, d: 40 };
console.log(pairs);
```

A) `{ c: 30 }`
B) `{ c: 30, d: 40 }`
C) `{ d: 40 }`
D) `undefined`
**Answer: A** 

4. True or False: The arrow function syntax below is valid and the function when called will return the output of multiplying `a` and `b`:
```js
const multiply = a, b => a * b;
```
A) True
B) False
**Answer: B** 

5. Which of the following is a correct definition of a **closure**?
A) A function that is nested inside of another function has access to variables declared in its local scope, in the outer function’s scope but not in the global scope.
B) A function that provides access to variables declared in its local scope to other functions.
C) A function that is nested inside of another function has access to variables declared in its local scope, in the outer function’s scope and in the global scope. 
D) None of the above
**Answer: C** 