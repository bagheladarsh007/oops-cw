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
![285602093-3a12426e-17f7-4f21-9846-eabe029e720c](https://github.com/bagheladarsh007/oops-cw/assets/142333682/0361fd85-2ec9-4ad1-af56-0f08e5645a50)
![285602115-7fd601f3-06f1-4bd3-a9e9-adb14546a1a2](https://github.com/bagheladarsh007/oops-cw/assets/142333682/af923263-5cb8-45ff-a47f-784a88282994)

![285602144-48f93460-2ce9-4077-8186-01c8f3cdf5c0](https://github.com/bagheladarsh007/oops-cw/assets/142333682/d8a7fa8f-0172-4f64-a35a-39407314dc93)
![285602174-bdb87ec5-c4a5-4b87-8fe2-2372382a2e84](https://github.com/bagheladarsh007/oops-cw/assets/142333682/7cbd39b1-71cc-4a6b-95f1-6a0d8cbe207a)



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
