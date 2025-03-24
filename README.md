# ES6-Features

-> ES6 2015 is the 6th version of the ECMAScript programming language.
-> Major changes were done.

1. LET Keyword:

--------------

->The let variables are mutable i.e. their values can be changed.
-> It works similar to the var keyword with some key differences like scoping which makes it a better option when compared to var.

Ex:
let a=12;
{
let a = 28; //Block-Scoped variable
console.log(a); // output: 28
}
console.log(a); // output: 12



