1️⃣ Difference between var, let, const

var, let, and const are used to declare variables in JavaScript.

var is the old way of declaring variables and it is function scoped.
let is block scoped and allows variable value to be changed.
const is also block scoped but its value cannot be reassigned after declaration.

2️⃣ Spread Operator (...)

The spread operator (...) is used to expand elements of an array or object.

Example:

const arr1=[1,2,3]
const arr2=[...arr1,4,5]

It helps copy arrays, merge arrays, and pass multiple values easily.

3️⃣ Difference between map(), filter(), forEach()

map() creates a new array after applying a function to each element.

filter() creates a new array containing elements that match a condition.

forEach() only loops through elements but does not return a new array.

4️⃣ Arrow Function

Arrow function is a shorter syntax for writing functions in JavaScript.

Example:

const sum=(a,b)=>a+b

It also does not have its own this context.

5️⃣ Template Literals

Template literals allow embedding variables inside strings using backticks.

Example:

const name="Anik"
console.log(`Hello ${name}`)

It makes string formatting easier.