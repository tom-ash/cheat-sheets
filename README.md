# JavaScript For Loop Cheat Sheet
This is a supplement to [soundof.it JavaScript For Loop](https://soundof.it/javascript-for-loop).

## 1. ES1 Classic For Loop
The classic for loop was introduced in ES1.

### 1.1 Syntax
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

### 1.2 Usage
The classic ES1 for loop can be used in multitude of scenarios. For example it can be used to iterate over an array or a string.
```JavaScript
const foo = 'bar'

for (var i = 0; i < foo.length; i++) {
  console.log(foo[i])
} // b a r
```

### 1.3 Returning
Using the `return` keyword within the block of the classic ES1 for loop throws `Uncaught SyntaxError: Illegal return statement`.

### 1.4 Breaking
The classic ES1 for loop can be halted using the `break` keyword.
