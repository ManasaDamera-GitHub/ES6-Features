# ES6-Features

-> ES6 2015 is the 6th version of the ECMAScript programming language.
-> Major changes were done.

1. LET Keyword:

---

->The let variables are mutable i.e. their values can be changed.
-> It works similar to the var keyword with some key differences like scoping which makes it a better option when compared to var.

Ex:
let a=12;
{
let a = 28; //Block-Scoped variable
console.log(a); // output: 28
}
console.log(a); // output: 12

2. Const Keyword:

---

Const is used to declare variables with a constant Value,ensuring the value cannot be reassigned.

-> Ideal for declaring configuration constants or fixed values.

**NOTE**
X no re-assignment // a = 10
X No re-declaration // const a
X No re-Initialization // const a=20
ex: const PI = 3.14159;
PI = 3; //Error : Assignment to constant variable

3. Arrow Functions:

---

Arrow functions provide a concise syntax for writing function expressions.

- implicit return for single-expression functions.
- Do not have their own "this" context.

**NOTE**

1. if 1 parameter os passed then no need of ().
   ex: const fun= a => console.log(a)
2. for single statement no need of expression (i.e {})
   ex: const add = (a,b)=> a + b
3. if you use expression then must use return keyword.
   ex: const add =(a,b)=>{return a+b}

4. Destructuring Assignment:

---

Destructuring refers to breaking down the complex structures (Object or Arrays) into simpler parts.

## Object Destructuring:

const obj={name:"Kenny", age:7};
const {name,age}=obj;
console.log(name,age); // Kenny 7

## Array Destructuring:

const a =["red","blue","green"];
const [first,second]=a;
console.log(first,second);
