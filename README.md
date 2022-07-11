# JavaScript For Loop Cheat Sheet
This is a supplement to [soundof.it JavaScript For Loop](https://soundof.it/javascript-for-loop).

1. [Section 1](#es1-classic-for-loop)
2. [Section 2](#section-2)
    - [Subsection a](#subsection-a)
    - [Subsection b](#subsection-b)

---

## ES1 Classic For Loop
The classic for loop was introduced in ES1.

### Syntax
The classic ES1 for loop is constructed through using the `for` keyword, the three initialization statements and the loop body.
```
for (statement_1, statement_2, statement_3) {
  // body
}
```
`statement_1` initializes values. `statement_2` specifies conditions for the initialized values. `statement_3` changes the initialized values. The loop continues until `statement_2` conditions are no longer met.
```JavaScript
for (var i = 0; i < 6; i++) {
  console.log(i)
} // 0 1 2 3 4 5
```

### Usage
The classic ES1 for loop can be used in multitude of scenarios. For example it can be used to iterate over an array or a string.
```JavaScript
const foo = 'bar'

for (var i = 0; i < foo.length; i++) {
  console.log(foo[i])
} // b a r
```

### Returning
Using the `return` keyword within the block of the classic ES1 for loop throws `Uncaught SyntaxError: Illegal return statement`.

### Breaking
The classic ES1 for loop can be halted using the `break` keyword.

---

## ES1 for...in Loop
The for...in loop was introduced in ES1.

### Syntax
The ES1 for...in loop is constructed through using the `for` keyword, a loop key variable name, the keyword `in` and the object reference.

```JavaScript
const captains = {
  picard: 'Enterprise',
  hook: 'Jolly Roger',
  blackbeard: 'Queen Anne\'s Revenge'
}

for (var captain in captains) {
  console.log(captain)
}  // picard hook blackbeard
```

### Usage
The ES1 for...in loop can be used to loop over object keys when the order of the keys is not important as the order is not guaranteed by the ES1 for...in loop.

### Returning
Using the `return` keyword within the block of the ES1 for...in loop throws `Uncaught SyntaxError: Illegal return statement`.

### Breaking
The ES1 for...in loop can be halted using the `break` keyword.

---

## ES5 forEach Loop
Incoming...

---

## ES6 for...of Loop
Incoming...
