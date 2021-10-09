# syntax
Syntax of raj language

```raj
// Single line comment

/*
* Multi
* line
* comment
*/

// Defining a function

fn main() {
  print("Hello World"); // Without new line
  println("Hello World"); // With new line
}

// defining variables

let myvar1 = 1; // mutable variable with local scope
// or
myVar2 = 10 // doesn't need keyword to declare. if already declared then changes it
const PI = 3.1415; // im-mutable constant with global scope

// Loops

for ( i = 0; i < 10; i++ ) {
  println(i);
}

while ( true === true ) {
  print("Hello World");
  break;
}

// arrays

myArr = [ 1, 2, 3, 4, 5 ];

myNestedArr = [ 1, [ 2, 20, 200, 2000 ], 3, 4, [ 5, 4, 3, 2, 1 ] ]; // arrays within array


// Object

myObj = {
  name: "Rajaniraiyn",
  age: 17,
  nationality: "Indian"
  location: {
    village: "Okkur",
    district: "Sivagangai",
    state: "Tamilnadu",
    country: "India",
  },
}

// Conditionals

if ( a == b) {
  println("Hello World");
} else {
  println("Hello Everyone");
}
```