# oops-cw
# Custom JavaScript Array Methods
This project provides custom implementations for three common array methods in JavaScript: `mineFilter`, `mineReduce`, and `mineMap`.
## Table of Contents
- [Overview](#overview)
- [Usage](#usage)
- [Examples](#examples)
## Overview
In this project, we've created custom functions that mimic the behavior of popular array methods in JavaScript. These functions provide alternatives to `filter`, `reduce`, and `map`.
## Usage
### `mineFilter(arr, callback)`
Filters elements in an array based on a provided callback function.
### `mineReduce(arr, callback, initialValue)`
Reduces an array to a single value using a callback function. An initial value can be provided.
### `mineMap(arr, callback)`
Maps each element in an array to a new value using a callback function.




// Custom filter function
const numbers = [1, 2, 3, 4, 5];
const filteredNumbers = mineFilter(numbers, (num) => num > 2);
console.log(filteredNumbers); // Output: [3, 4, 5]
// Custom reduce function
const sum = mineReduce(numbers, (acc, num) => acc + num, 0);
console.log(sum); // Output: 15
// Custom map function
const squaredNumbers = mineMap(numbers, (num) => num * num);
console.log(squaredNumbers); // Output: [1, 4, 9, 16, 25]
