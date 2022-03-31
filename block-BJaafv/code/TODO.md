1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
the first returns the result of a+b i.e 10
whereas second finction is printing the value of a+b

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

First function will return the value of a+b
whereas second function will return undefined

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
Output will be 36 as the first two parameter will take the respective value and will perform the action 
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
yes we can store as it is an operation on two operand it can be stored in 3rd variable
5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

function sayHello(name)
{
  return(`Hello ${name}`);
}
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
'Hello, John'

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 John

showMessage(); // Output 2 'Hello , John'

alert(userName); // Output 3 John
```

8. What is a Anonymous Function give example of three functions.
anonymous function is a function that is defined without name identifier.
const add= function(numA,numB)
{
  return(numA+numB);
} 
let show = function() {
    console.log('Anonymous');
}
let mul = (num) => num*num;
9. Can function declaration be a Anonymous Function? Explain
yes, we can declare anonymous function by 
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
function add(numA, numB)
{
  return(numA+numB)
}
function userName(name)
{
  return(name);

}
function marks(number)
{
  return(number);

}
function sub(numA, numB)
{
  return(numA-numB)
}
