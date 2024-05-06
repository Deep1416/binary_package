# Binary Search

A simple binary search algorithm implementation for JavaScript.

## Installation

You can install the package via npm:

```bash
npm install @your-username/binary-search

```
```javaScript
const binarySearch = require('@your-username/binary-search');

const arr = [1, 3, 5, 7, 9];
const target = 5;
const index = binarySearch(arr, target);

if (index !== -1) {
  console.log(`Element ${target} found at index ${index}`);
} else {
  console.log(`Element ${target} not found`);
}
```