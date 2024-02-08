#### Go through each requirements and solve it:

1. Define a function named sayHello when called alert saying "Hello JavaScript".

   - Call above function.
   - Store the return value in a variable named one
   - What is the typeof the value in one

```js

function sayHello (){
    alert("Hello Javascript")
}
sayHello()

let one = sayHello();
typeof one; //"undefined"

```
2. Change function (from Part 1 above) to accept name from user using prompt and store it in a variable named usename and alert message saying Hello [username].

   - Call above function.
   - Store the return value in a variable named two
   - What is the typeof the value in two

```js

function sayHello () {
    let username = prompt("Enter Your name ");
    alert(`Hello ${username} `)
}
sayHello()
let two = sayHello()
typeof two // undefined
```

3. Change the function (from Part 2 above) to accept username as a parameter not from prompt.

```js

function sayHello (username) {
    alert(`Hello ${username} `)
}

```
4. Change (from Part 3 above) return the message Hello username instead of alerting it.

   - Call above function.
   - Store the return value in a variable named four
   - What is the typeof the value in four

```js

function sayHello (username) {
    return `Hello ${username} `
}
sayHello("oggy");
let four = sayHello("oggy")
typeof four; // "string"
```   