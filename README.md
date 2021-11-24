# Raj Lang Syntax

Syntax of raj programming language


## 🤝 Contribution

Please Vote for proposals or propose new at [Dicussions](https://github.com/rajlang/Syntax/discussions/categories/proposals)


## Syntax

<!-- Using rust lang for some syntax highlighting -->
```rs
// Single line comment
# This is also single line comment

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

// Defining variables

let myVar1 = 1; // mutable variable with local scope
// or
myVar2 = 10 // doesn't need keyword to declare. if already declared then changes it
const PI = 3.1415; // im-mutable constant with global scope

// Loops

// for
for ( i = 0; i < 10; i++ ) {
  println(i);
}

// while (not infinite loop)
while (sayHello) {
  print("Hello World");
  break;
}

// loops infinitely with optimizations
loop {
  println("I love Programming");
}

// do-while
do {
  println("Do");
}
while (true) {
  println("while");
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

// template literals

`
this is the 
m
u
l
t
i
line
template-literal
`
"""
this is also a 
m
u
l
t
i
line
template-literal
"""

// switch statements


switch(a) {
  1 || 3 :
    println("a is one");
    break;
    
  2 || 4:
    println("a is two");
    break;
    
  default:
    println("a is not one or two");
    break;
}
```

## 🤝 Contributing

  Feel free to add or improve this syntax by creating an issue.
  Once the syntax is added to all implementations it will be reflected in this repo and the issue will be closed.
