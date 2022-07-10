# JavaScript For Loop Cheat Sheet

This is a supplement to [JavaScript For Loop](https://soundof.it/javascript-for-loop).

## ES1 Classic For Loop
The classic for loop was introduced in ES1.

### Syntax
The classic ES1 for loop is constructed through using the `for` keyword, the three initialization statements and the loop body.
```
for (statement_1, statement_2, statement_3) {
  // body
}
```
`statement_1` initializes values. `statement_2` specifies conditions for the initialized values. `statement_3` increments the initialized values. The loop continues until `statement_2` conditions are no longer met.
```JavaScript
for (let i = 0; i < 6; i++) {
  console.log(i)
} // 0 1 2 3 4 5
```
