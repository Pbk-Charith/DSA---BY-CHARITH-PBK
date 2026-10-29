# 🚀 DSA by Charith PBK

> **My journey of learning Data Structures and Algorithms using JavaScript.**

Welcome to my DSA learning repository! 👋

This repository contains my notes, JavaScript fundamentals, coding examples, and problem-solving concepts that I'm learning step by step. My goal is to strengthen my programming fundamentals and build a strong foundation for solving DSA problems.

---

## 📚 Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [🟢 Episode 1: JavaScript Fundamentals](#-episode-1-javascript-fundamentals)
  - [1. Printing Hello World](#1-printing-hello-world)
  - [2. Variables and String Concatenation](#2-variables-and-string-concatenation)
  - [3. Arrays and Array Concatenation](#3-arrays-and-array-concatenation)
  - [4. Accessing Array Elements](#4-accessing-array-elements)
  - [5. Nested Arrays](#5-nested-arrays)
  - [6. JavaScript Objects](#6-javascript-objects)
- [🔵 Episode 2: Functions and Control Flow](#-episode-2-functions-and-control-flow)
  - [1. Printing Hello World Using a Function](#1-printing-hello-world-using-a-function)
  - [2. Functions with Parameters](#2-functions-with-parameters)
  - [3. Creating a Function to Add Two Numbers](#3-creating-a-function-to-add-two-numbers)
  - [4. Finding the Square of a Number Using `return`](#4-finding-the-square-of-a-number-using-return)
  - [5. Checking Voting Eligibility Using Conditional Statements](#5-checking-voting-eligibility-using-conditional-statements)
  - [6. Checking Whether a Number Is Even or Odd](#6-checking-whether-a-number-is-even-or-odd)
  - [**Key concept:** The modulus operator (`%`) is commonly used in DSA to check divisibility, identify even and odd numbers, and solve mathematical problems.](#key-concept-the-modulus-operator--is-commonly-used-in-dsa-to-check-divisibility-identify-even-and-odd-numbers-and-solve-mathematical-problems)
  - [7. Introduction to Loops in JavaScript](#7-introduction-to-loops-in-javascript)
    - [🔹 Example 1: Printing Names Using a `for` Loop](#-example-1-printing-names-using-a-for-loop)
    - [🧠 Understanding the `for` Loop](#-understanding-the-for-loop)
  - [8. Linear Search in an Array](#8-linear-search-in-an-array)
    - [💻 JavaScript Solution](#-javascript-solution)
    - [📤 Output](#-output)
    - [🧠 How It Works](#-how-it-works)
    - [📝 Examples](#-examples)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity)
  - [9. Counting Negative Numbers in an Array](#9-counting-negative-numbers-in-an-array)
    - [💻 JavaScript Solution](#-javascript-solution-1)
    - [📤 Output](#-output-1)
    - [🧠 How It Works](#-how-it-works-1)
    - [📝 Example](#-example)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-1)
  - [10. Finding the Largest Number in an Array](#10-finding-the-largest-number-in-an-array)
    - [💻 Approach 1: Basic Solution](#-approach-1-basic-solution)
    - [📤 Output](#-output-2)
    - [🧠 How It Works](#-how-it-works-2)
    - [💻 Approach 2: Robust Solution with Input Validation](#-approach-2-robust-solution-with-input-validation)
    - [📤 Output](#-output-3)
    - [📝 Handling Different Inputs](#-handling-different-inputs)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-2)
    - [🔑 Key Takeaways](#-key-takeaways)
  - [11. Finding the Lowest Number in an Array](#11-finding-the-lowest-number-in-an-array)
    - [💻 JavaScript Solution](#-javascript-solution-2)
    - [📤 Output](#-output-4)
    - [🧠 How It Works](#-how-it-works-3)
    - [📝 Example](#-example-1)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-3)
  - [12. Finding the Second Largest Number in an Array](#12-finding-the-second-largest-number-in-an-array)
    - [💻 JavaScript Solution](#-javascript-solution-3)
    - [📤 Output](#-output-5)
    - [🧠 How It Works](#-how-it-works-4)
    - [📝 Example](#-example-2)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-4)
    - [Approach 2 :](#approach-2-)
    - [💻 JavaScript Solution](#-javascript-solution-4)
    - [📤 Output](#-output-6)
    - [🧠 How It Works](#-how-it-works-5)
    - [📝 Example](#-example-3)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-5)
    - [🔑 Key Takeaways](#-key-takeaways-1)
  - [12. Understanding Nested Loops in JavaScript](#12-understanding-nested-loops-in-javascript)
    - [💻 JavaScript Solution](#-javascript-solution-5)
    - [📤 Output](#-output-7)
    - [🧠 How It Works](#-how-it-works-6)
    - [📝 Iteration Calculation](#-iteration-calculation)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-6)
  - [14. Printing a Pattern Using Nested Loops](#14-printing-a-pattern-using-nested-loops)
    - [💻 JavaScript Solution](#-javascript-solution-6)
    - [📤 Output](#-output-8)
    - [🧠 How It Works](#-how-it-works-7)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-7)
    - [🔑 Key Takeaway](#-key-takeaway)
  - [15. Understanding Nested Loops with Decrementing Inner Loop](#15-understanding-nested-loops-with-decrementing-inner-loop)
    - [💻 JavaScript Solution](#-javascript-solution-7)
    - [📤 Output](#-output-9)
    - [🧠 How It Works](#-how-it-works-8)
    - [📝 Iteration Breakdown](#-iteration-breakdown)
    - [🔢 Count Calculation](#-count-calculation)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-8)
    - [🔑 Key Takeaway](#-key-takeaway-1)
  - [16. Generating the Alphabet from A to Z Using ASCII Codes](#16-generating-the-alphabet-from-a-to-z-using-ascii-codes)
    - [💻 JavaScript Solution](#-javascript-solution-8)
    - [🧠 How It Works](#-how-it-works-9)
    - [📤 Example Usage and Output](#-example-usage-and-output)
    - [🔑 Important Concepts](#-important-concepts)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-9)
  - [17. Printing a Square Pattern Using Nested Loops](#17-printing-a-square-pattern-using-nested-loops)
    - [💻 JavaScript Solution](#-javascript-solution-9)
    - [📤 Output](#-output-10)
    - [🧠 How It Works](#-how-it-works-10)
    - [📝 Iteration Breakdown](#-iteration-breakdown-1)
    - [🔢 Total Iterations](#-total-iterations)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-10)
    - [🔑 Key Takeaway](#-key-takeaway-2)
  - [Nested loops are commonly used to print square, triangular, and other character patterns. The outer loop controls the **rows**, while the inner loop controls the **columns**.](#nested-loops-are-commonly-used-to-print-square-triangular-and-other-character-patterns-the-outer-loop-controls-the-rows-while-the-inner-loop-controls-the-columns)
  - [18. Printing a Growing Pattern Using Nested Loops](#18-printing-a-growing-pattern-using-nested-loops)
    - [💻 JavaScript Solution](#-javascript-solution-10)
    - [📤 Output](#-output-11)
    - [🧠 How It Works](#-how-it-works-11)
    - [📝 Important Difference](#-important-difference)
    - [🔢 Total Executions](#-total-executions)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-11)
    - [🔑 Key Takeaway](#-key-takeaway-3)
  - [**The position of `console.log()` matters.** When it is inside the inner loop, intermediate results are printed. When it is outside the inner loop, only the completed row is printed.](#the-position-of-consolelog-matters-when-it-is-inside-the-inner-loop-intermediate-results-are-printed-when-it-is-outside-the-inner-loop-only-the-completed-row-is-printed)
  - [19. Printing a Growing Pattern Using a Single Outer Loop](#19-printing-a-growing-pattern-using-a-single-outer-loop)
    - [💻 JavaScript Solution](#-javascript-solution-11)
    - [📤 Output](#-output-12)
    - [🧠 How It Works](#-how-it-works-12)
    - [📝 Iteration Breakdown](#-iteration-breakdown-2)
    - [🔑 Key Takeaways](#-key-takeaways-2)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-12)
  - [**Key takeaway:** The outer loop controls how many times the pattern is repeated, while the inner loop controls how the pattern grows.](#key-takeaway-the-outer-loop-controls-how-many-times-the-pattern-is-repeated-while-the-inner-loop-controls-how-the-pattern-grows)
  - [20. Reversing a Pattern Using Nested Loops](#20-reversing-a-pattern-using-nested-loops)
    - [💻 JavaScript Solution](#-javascript-solution-12)
    - [📤 Output](#-output-13)
    - [🧠 How It Works](#-how-it-works-13)
    - [📝 Iteration Breakdown](#-iteration-breakdown-3)
    - [🔑 Key Takeaways](#-key-takeaways-3)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-13)
  - [21. Printing a Number Triangle Pattern Using Nested Loops](#21-printing-a-number-triangle-pattern-using-nested-loops)
    - [💻 JavaScript Solution](#-javascript-solution-13)
    - [📤 Output](#-output-14)
    - [🧠 How It Works](#-how-it-works-14)
    - [📝 Iteration Breakdown](#-iteration-breakdown-4)
    - [🔢 Total Inner Loop Executions](#-total-inner-loop-executions)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-14)
    - [🔑 Key Takeaways](#-key-takeaways-4)
  - [**DSA Pattern:** Nested loops are useful for printing number patterns, understanding iteration counts, and developing the logical thinking required for more advanced DSA problems.](#dsa-pattern-nested-loops-are-useful-for-printing-number-patterns-understanding-iteration-counts-and-developing-the-logical-thinking-required-for-more-advanced-dsa-problems)
  - [22. Printing a Number Triangle with Repeated Row Values](#22-printing-a-number-triangle-with-repeated-row-values)
    - [💻 JavaScript Solution](#-javascript-solution-14)
    - [📤 Output](#-output-15)
    - [🧠 How It Works](#-how-it-works-15)
    - [📝 Iteration Breakdown](#-iteration-breakdown-5)
    - [🔢 Total Iterations](#-total-iterations-1)
    - [⏱️ Time and Space Complexity](#-time-and-space-complexity-15)
    - [🔑 Key Takeaways](#-key-takeaways-5)
    - [Another Approach but same result...](#another-approach-but-same-result)
    - [📤 Output](#-output-16)
- [🎯 Learning Goals](#-learning-goals)
  - [💡 My Learning Philosophy](#-my-learning-philosophy)

<!-- END doctoc -->

---

# 🟢 Episode 1: JavaScript Fundamentals

This episode covers the basics of JavaScript, including variables, strings, arrays, and objects.

## 1. Printing Hello World

The `console.log()` method prints messages or values to the console.

```javascript
console.log("Hello World");
console.log("Charith");
```

**Output:**

```text
Hello World
Charith
```

## 2. Variables and String Concatenation

Variables store data that can be used throughout a program.

In JavaScript, `let` declares a variable whose value can be reassigned.

The `+` operator combines strings.

```javascript
let firstName = "P.Sai ";
let lastName = "Charith";

let fullName = firstName + lastName;

console.log(fullName);
```

**Output:**

```text
P.Sai Charith
```

**Key concepts:**
- `let` — declares a variable.
- Strings — represent text enclosed in quotes.
- String concatenation — combines multiple strings using `+`.

## 3. Arrays and Array Concatenation

An array stores multiple values in a single variable.

```javascript
let arr1 = [2, 3, 5, 6];
let arr2 = [10, 11, 12, 13];

let array = arr1 + "," + arr2;

console.log(array);
```

**Output:**

```text
2,3,5,6,10,11,12,13
```

**Important:** Using `+` with arrays converts them to strings in this example. To combine arrays while keeping the result as an array, use `concat()` or the spread operator.

```javascript
let combinedArray = arr1.concat(arr2);

// Alternative:
// let combinedArray = [...arr1, ...arr2];

console.log(combinedArray);
```

**Output:**

```javascript
[2, 3, 5, 6, 10, 11, 12, 13]
```

## 4. Accessing Array Elements

Array indexing starts at `0`, not `1`.

```javascript
let array1 = ["ch", "li", "Na", "Kr"];

console.log(array1[2]);
```

**Output:**

```text
Na
```

**Index reference:**

| Index | Value |
|---:|---|
| 0 | ch |
| 1 | li |
| 2 | Na |
| 3 | Kr |

## 5. Nested Arrays

An array can contain another array. This is called a nested array.

```javascript
let array2 = [1, 2, [3, 4]];

console.log(array2[2]);
console.log(array2[2][0]);
console.log(array2[2][1]);
```

**Output:**

```text
[3, 4]
3
4
```

**Remember:**
- `array2[2]` accesses the nested array.
- `array2[2][0]` accesses its first element.
- `array2[2][1]` accesses its second element.

## 6. JavaScript Objects

An object stores data as key-value pairs. It is useful for representing entities with multiple properties.

```javascript
let object = {
    a: 27,
    name: "Charith",
    Boolean: true,
    Array: [1, 2, 3]
};

console.log(object.name);
console.log(object.a);
console.log(object.Boolean);
console.log(object.Array);
```

**Output:**

```text
Charith
27
true
[1, 2, 3]
```

**Key concepts:**
- `name`, `a`, `Boolean`, and `Array` are property keys.
- `"Charith"`, `27`, `true`, and `[1, 2, 3]` are their corresponding values.
- Dot notation, such as `object.name`, accesses a property.

---

# 🔵 Episode 2: Functions and Control Flow

This episode introduces functions, parameters, return values, and conditional statements using `if`, `else if`, and `else`.

## 1. Printing Hello World Using a Function

A function is a reusable block of code designed to perform a particular task.

```javascript
function printHelloWorld() {
    console.log("Hello World");
}

printHelloWorld();
```

**Output:**

```text
Hello World
```

**How it works:**
1. `function` defines a function.
2. `printHelloWorld` is the function name.
3. The code inside `{}` executes when the function is called.
4. `printHelloWorld()` calls the function.

## 2. Functions with Parameters

Parameters allow us to pass data into a function.

```javascript
function greet(name) {
    console.log("Namaste, " + name);
}

greet("Charith");
```

**Output:**

```text
Namaste, Charith
```

Here, `name` is the parameter, and `"Charith"` is the argument passed to the function.

You can reuse the same function with different arguments:

```javascript
greet("Rahul");
greet("Priya");
```

**Output:**

```text
Namaste, Rahul
Namaste, Priya
```

## 3. Creating a Function to Add Two Numbers

Functions can accept multiple parameters and perform calculations.

```javascript
function sum(first, last) {
    console.log(first + last);
}

sum(8, 10);
```

**Output:**

```text
18
```

**Explanation:**
- `first` receives `8`.
- `last` receives `10`.
- `first + last` calculates their sum.
- `console.log()` prints the result.

## 4. Finding the Square of a Number Using `return`

The `return` statement sends a result back to the place where a function was called.

```javascript
function square(x) {
    let result = x * x;
    return result;
}

let answer = square(2);

console.log(answer);
```

**Output:**

```text
4
```

**Explanation:**

For `square(2)`:

\[
2 \times 2 = 4
\]

The function returns `4`, which is stored in the `answer` variable.

**Important difference:**
- `console.log()` displays a value.
- `return` gives a value back to the caller so it can be stored or reused.

## 5. Checking Voting Eligibility Using Conditional Statements

Conditional statements allow a program to make decisions based on specific conditions.

```javascript
function checkEligibility(age) {
    if (age <= 0) {
        console.log("Invalid age");
    } else if (age < 18) {
        console.log("Not eligible to vote");
    } else {
        console.log("Eligible to vote");
    }
}

checkEligibility(15);
checkEligibility(-20);
checkEligibility(18);
checkEligibility(25);
checkEligibility(52);
```

**Output:**

```text
Not eligible to vote
Invalid age
Eligible to vote
Eligible to vote
Eligible to vote
```

**Explanation:**

| Condition | Result |
|---|---|
| `age <= 0` | Invalid age |
| `age < 18` | Not eligible to vote |
| Otherwise | Eligible to vote |

**Important:** In the original example, the conditions used `age < 15` and `age > 15 && age < 50`. That logic incorrectly excluded some ages, including 15 and 50. The revised version uses the general voting-age threshold of 18 years, applicable in India for ordinary elections, and handles invalid ages separately.

---

## 6. Checking Whether a Number Is Even or Odd

The **modulus operator (`%`)** returns the remainder after dividing one number by another. We can use it to determine whether a number is even or odd.

- **Even number:** Divisible by `2` with a remainder of `0`.
- **Odd number:** Divisible by `2` with a remainder of `1` (for positive integers).

```javascript
function isOddEven(num) {
    let remainder = num % 2;

    if (remainder === 0) {
        console.log("Is Even");
    } else {
        console.log("Is Odd");
    }
}

isOddEven(2);
isOddEven(5);
```

**Output:**

```text
Is Even
Is Odd
```

**Explanation:**

1. `num % 2` calculates the remainder when the number is divided by `2`.
2. If `remainder === 0`, the number is even.
3. Otherwise, the number is odd.

**Example:**

| Number | Calculation | Result |
|---:|---|---|
| 2 | `2 % 2 = 0` | Even |
| 5 | `5 % 2 = 1` | Odd |
| 8 | `8 % 2 = 0` | Even |
| 11 | `11 % 2 = 1` | Odd |

**Key concept:** The modulus operator (`%`) is commonly used in DSA to check divisibility, identify even and odd numbers, and solve mathematical problems.
---

## 7. Introduction to Loops in JavaScript

Loops allow us to execute a block of code repeatedly without writing the same statements multiple times.

### 🔹 Example 1: Printing Names Using a `for` Loop

```javascript
for (let i = 3; i < 15; i++) {
    console.log("Charith");
    console.log("Likhith");
}
```

**Output:**

```text
Charith
Likhith
Charith
Likhith
Charith
Likhith
...
```

*The output repeats 12 times because the loop runs for `i = 3` through `i = 14`.*

### 🧠 Understanding the `for` Loop

```javascript
for (initialization; condition; increment) {
    // Code to execute repeatedly
}
```

| Component | Explanation |
|---|---|
| `let i = 3` | Initializes the loop counter. |
| `i < 15` | Continues the loop while the condition is true. |
| `i++` | Increases `i` by 1 after each iteration. |

**Key takeaway:** A `for` loop is useful when you know the condition that determines how many times a block of code should execute.

---

## 8. Linear Search in an Array

Linear Search is a simple searching algorithm that checks each element of an array one by one until the target element is found.

**Problem Statement:** Write a function that searches for an element in an array and returns its index. If the element is not present, return `-1`.

### 💻 JavaScript Solution

```javascript
function search(arr, x) {
    for (let i = 0; i < arr.length; i++) {
        if (arr[i] === x) {
            return i;
        }
    }

    return -1;
}

let arr = [1, 2, 3, 4, 5];

// Search for an existing element
// let result = search(arr, 5);

// Search for a missing element
let result = search(arr, 6);

console.log(result);
```

### 📤 Output

```text
-1
```

### 🧠 How It Works

1. The `search()` function accepts an array (`arr`) and a target value (`x`).
2. The `for` loop checks each array element from index `0` to the last index.
3. If `arr[i] === x`, the function returns the index `i`.
4. If no matching element is found, the function returns `-1`.

### 📝 Examples

| Target (`x`) | Result | Explanation |
|---:|---:|---|
| `3` | `2` | Element found at index `2`. |
| `5` | `4` | Element found at index `4`. |
| `6` | `-1` | Element not found in the array. |

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n)\) — in the worst case, every element is checked.
- **Space Complexity:** \(O(1)\) — the algorithm uses constant extra space.

**Key takeaway:** Linear Search works on both sorted and unsorted arrays and is one of the fundamental searching algorithms in DSA.

---

## 9. Counting Negative Numbers in an Array

**Problem Statement:** Write a function that counts and returns the total number of negative numbers present in an array.

### 💻 JavaScript Solution

```javascript
let arr = [1, 2, 3, 4, -5, 6, 7, 8, 9];

function countNegativeNumbers(arr) {
    let count = 0;

    for (let i = 0; i < arr.length; i++) {
        if (arr[i] < 0) {
            count++;
        }
    }

    return count;
}

let result = countNegativeNumbers(arr);
console.log(result);
```

### 📤 Output

```text
1
```

### 🧠 How It Works

1. Initialize `count = 0` to track the number of negative elements.
2. Use a `for` loop to iterate through every element in the array.
3. Check whether `arr[i] < 0`.
4. If the condition is true, increment `count` by `1`.
5. Return the final count after checking all elements.

### 📝 Example

For the array:

```javascript
[1, 2, 3, 4, -5, 6, 7, 8, 9]
```

The only negative number is `-5`, so the function returns `1`.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n)\) — every element is checked once.
- **Space Complexity:** \(O(1)\) — only a single counter variable is used.

**Key takeaway:** Use a counter and a condition to count elements that satisfy a specific requirement. This pattern is useful in many DSA problems.

---

## 10. Finding the Largest Number in an Array

**Problem Statement:** Write a function that returns the largest number in an array.

There are two approaches to solve this problem: a basic approach and a robust approach with input validation.

### 💻 Approach 1: Basic Solution

```javascript
let arr = [1, 2, 3, 4, 5, 6, 7, 8, 9];

function largest(arr) {
    let max = -Infinity;

    for (let i = 0; i < arr.length; i++) {
        if (arr[i] > max) {
            max = arr[i];
        }
    }

    return max;
}

let result = largest(arr);
console.log(result);
```

### 📤 Output

```text
9
```

### 🧠 How It Works

1. Initialize `max` to `-Infinity` so that negative numbers are handled correctly.
2. Iterate through the array using a `for` loop.
3. Compare each element with the current maximum.
4. If the current element is greater, update `max`.
5. Return the largest number after checking all elements.

**Example:**

For the array `[1, 2, 3, 4, 5, 6, 7, 8, 9]`, the largest number is `9`.

---

### 💻 Approach 2: Robust Solution with Input Validation

This approach checks whether the input is a valid array, handles empty arrays, and rejects non-numeric or non-finite values.

```javascript
function findLargest(arr) {
    if (!Array.isArray(arr)) {
        return false;
    }

    if (arr.length === 0) {
        return null;
    }

    let max = -Infinity;

    for (let i = 0; i < arr.length; i++) {
        if (typeof arr[i] !== "number" || !Number.isFinite(arr[i])) {
            return false;
        }

        if (arr[i] > max) {
            max = arr[i];
        }
    }

    return max;
}

let arr = [1, 2, 3, 4, 5, 6, 7, 8, 9];

console.log(findLargest(arr));

// Export the function for use in other Node.js files
module.exports = { findLargest };
```

### 📤 Output

```text
9
```

### 📝 Handling Different Inputs

| Input | Return value | Reason |
|---|---|---|
| `[1, 5, 9, 3]` | `9` | Returns the largest number. |
| `[-10, -3, -7]` | `-3` | Correctly handles negative numbers. |
| `[]` | `null` | The array is empty. |
| `"hello"` | `false` | The input is not an array. |
| `[1, "5", 9]` | `false` | Contains a non-numeric value. |

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n)\) — each array element is checked once.
- **Space Complexity:** \(O(1)\) — only a constant amount of extra space is used.

### 🔑 Key Takeaways

- Use a loop to compare every element in an array.
- Initialize the maximum to `-Infinity` to handle arrays containing negative numbers.
- Input validation makes functions more reliable.
- `module.exports` allows the function to be imported into another CommonJS Node.js file.

**DSA Pattern:** Finding the maximum or minimum element is a fundamental array problem that builds the foundation for more advanced algorithms.

---

## 11. Finding the Lowest Number in an Array

**Problem Statement:** Write a function that returns the smallest number present in an array.

### 💻 JavaScript Solution

```javascript
let arr = [1, 2, 3, 4, -5, 6, 7, 8, 9];

function smallest(arr) {
    if (arr.length === 0) {
        return undefined;
    }

    let smallestNum = arr[0];

    for (let i = 1; i < arr.length; i++) {
        if (arr[i] < smallestNum) {
            smallestNum = arr[i];
        }
    }

    return smallestNum;
}

let result = smallest(arr);
console.log(result);
```

### 📤 Output

```text
-5
```

### 🧠 How It Works

1. Initialize `smallestNum` with the first element of the array.
2. Use a `for` loop to iterate through the remaining elements.
3. Compare each element with the current `smallestNum`.
4. If the current element is smaller, update `smallestNum`.
5. Return the smallest number after checking all elements.

### 📝 Example

For the array:

```javascript
[1, 2, 3, 4, -5, 6, 7, 8, 9]
```

The lowest number is `-5`.

**Why initialize with `arr[0]`?**

Initializing with the first element ensures that the function works correctly with positive numbers, negative numbers, and arrays containing only one element. The function returns `undefined` for an empty array.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n)\) — each element is checked at most once.
- **Space Complexity:** \(O(1)\) — only a constant amount of extra space is used.

**Key takeaway:** Track the current minimum and update it whenever you find a smaller element. This is a fundamental pattern in array-based DSA problems.

---

## 12. Finding the Second Largest Number in an Array

**Problem Statement:** Write a function that returns the second largest distinct number present in an array.

### 💻 JavaScript Solution

```javascript
let arr = [15, 14, 19, 18, 6, 17];

function secondLargest(arr) {
    let firstLargest = -Infinity;
    let secondLargest = -Infinity;

    for (let i = 0; i < arr.length; i++) {
        if (arr[i] > firstLargest) {
            secondLargest = firstLargest;
            firstLargest = arr[i];
        } else if (
            arr[i] > secondLargest && arr[i] < firstLargest
        ) {
            secondLargest = arr[i];
        }
    }

    return secondLargest === -Infinity ? undefined : secondLargest;
}

let result = secondLargest(arr);
console.log(result);
```

### 📤 Output

```text
18
```

### 🧠 How It Works

1. Initialize `firstLargest` and `secondLargest` to `-Infinity`.
2. Iterate through the array using a `for` loop.
3. If the current element is greater than `firstLargest`, move the previous largest value into `secondLargest` and update `firstLargest`.
4. Otherwise, if the current element is smaller than `firstLargest` but greater than `secondLargest`, update `secondLargest`.
5. Return the second largest distinct number. If no second distinct number exists, return `undefined`.

### 📝 Example

For the array:

```javascript
[15, 14, 19, 18, 6, 17]
```

The largest number is `19`, and the second largest number is `18`.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n)\) — the array is traversed once.
- **Space Complexity:** \(O(1)\) — only two variables are used to track the largest values.

**Key takeaway:** Track the largest and second largest values in a single traversal instead of sorting the entire array. This is an efficient and commonly asked DSA interview problem.

---

### Approach 2 : 

**Problem Statement:** Write a function that finds and returns the second-largest **distinct** number in an array. If the array is empty or does not contain a second distinct number, return `null`. Negative numbers are not allowed in this solution.

### 💻 JavaScript Solution

```javascript
let arr = [1, 2, 2];

function findSecondLargest(arr) {
    if (arr.length === 0) {
        return null;
    }

    let first_lar = -Infinity;
    let sec_lar = -Infinity;

    for (let i = 0; i < arr.length; i++) {
        if (arr[i] < 0) {
            return "Negative numbers should not be there";
        }

        if (arr[i] > first_lar) {
            sec_lar = first_lar;
            first_lar = arr[i];
        } else if (arr[i] > sec_lar && arr[i] !== first_lar) {
            sec_lar = arr[i];
        }
    }

    return sec_lar === -Infinity ? null : sec_lar;
}

let result = findSecondLargest(arr);
console.log(result);
```

### 📤 Output

```text
1
```

### 🧠 How It Works

1. Initialize `first_lar` and `sec_lar` to `-Infinity`.
2. Iterate through the array using a `for` loop.
3. If a number is greater than `first_lar`, move the current largest number into `sec_lar` and update `first_lar`.
4. Otherwise, if the number is smaller than the largest but greater than the second largest, update `sec_lar`.
5. Ignore duplicate occurrences of the largest number.
6. Return the second-largest distinct number, or `null` if one does not exist.

### 📝 Example

For the array `[1, 2, 2]`:

| Element | First Largest | Second Largest |
|---:|---:|---:|
| 1 | 1 | `-Infinity` |
| 2 | 2 | 1 |
| 2 | 2 | 1 |

The largest number is `2`, and the second-largest **distinct** number is `1`.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n)\) — the array is traversed once.
- **Space Complexity:** \(O(1)\) — only two variables are used to track the largest values.

### 🔑 Key Takeaways

- Track the largest and second-largest values simultaneously.
- Use `-Infinity` to initialize the variables so positive values can be compared correctly.
- Use `!==` to prevent duplicates of the largest number from becoming the second largest.
- Handle edge cases, such as empty arrays and arrays containing only one distinct value.

**DSA Pattern:** This is a single-pass array problem that helps build your understanding of comparisons, loops, and maintaining multiple variables while traversing an array.


---

## 12. Understanding Nested Loops in JavaScript

**Concept:** A nested loop is a loop inside another loop. The inner loop completes all its iterations for every single iteration of the outer loop.

### 💻 JavaScript Solution

```javascript
let count = 0;

for (let i = 0; i < 5; i++) {
    for (let j = 0; j < 5; j++) {
        console.log(`i = ${i}   j = ${j}`);
        count++;
    }
}

console.log("=====================");
console.log("Count is:", count);
```

### 📤 Output

```text
i = 0   j = 0
i = 0   j = 1
i = 0   j = 2
i = 0   j = 3
i = 0   j = 4
i = 1   j = 0
i = 1   j = 1
i = 1   j = 2
i = 1   j = 3
i = 1   j = 4
i = 2   j = 0
i = 2   j = 1
i = 2   j = 2
i = 2   j = 3
i = 2   j = 4
i = 3   j = 0
i = 3   j = 1
i = 3   j = 2
i = 3   j = 3
i = 3   j = 4
i = 4   j = 0
i = 4   j = 1
i = 4   j = 2
i = 4   j = 3
i = 4   j = 4
=====================
Count is: 25
```

### 🧠 How It Works

1. **Outer loop (`i`):** Runs 5 times, from `0` to `4`.
2. **Inner loop (`j`):** Runs 5 times for every iteration of the outer loop.
3. **`count++`:** Increments the counter every time the inner loop executes.
4. **Total iterations:** Each of the 5 outer-loop iterations triggers 5 inner-loop iterations.

### 📝 Iteration Calculation

\[
\text{Total Iterations} = 5 \times 5 = 25
\]

| Outer Loop (`i`) | Inner Loop Iterations | Count Added |
|---:|---|---:|
| 0 | 0, 1, 2, 3, 4 | 5 |
| 1 | 0, 1, 2, 3, 4 | 5 |
| 2 | 0, 1, 2, 3, 4 | 5 |
| 3 | 0, 1, 2, 3, 4 | 5 |
| 4 | 0, 1, 2, 3, 4 | 5 |
| **Total** | **25 iterations** | **25** |

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n^2)\) when both loops run `n` times.
- **Space Complexity:** \(O(1)\) because only a constant amount of extra space is used.

**Key takeaway:** Nested loops are commonly used in DSA for working with matrices, printing patterns, comparing array elements, and solving problems involving pairs of elements.

---

## 14. Printing a Pattern Using Nested Loops

**Problem Statement:** Use nested `for` loops to print `"x"` multiple times and count the total number of executions of the inner loop.

### 💻 JavaScript Solution

```javascript
let count = 0;

for (let i = 0; i < 5; i++) {
    for (let j = 0; j < i; j++) {
        console.log("x");
        count++;
    }
}

console.log("=====================");
console.log("Count is:", count);
```

### 📤 Output

```text
x
x
x
x
x
x
x
x
x
x
=====================
Count is: 10
```

### 🧠 How It Works

The outer loop runs from `i = 0` to `i = 4`. The inner loop executes only while `j < i`.

| Outer Loop (`i`) | Inner Loop Executions | Count |
|---:|---:|---:|
| 0 | 0 | 0 |
| 1 | 1 | 1 |
| 2 | 2 | 3 |
| 3 | 3 | 6 |
| 4 | 4 | 10 |
| **Total** | **10** | **10** |

**Why does the count equal 10?**

\[
0 + 1 + 2 + 3 + 4 = 10
\]

When `i = 0`, the inner loop does not execute because `j < 0` is false from the beginning. For each subsequent outer-loop iteration, the inner loop executes one additional time.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n^2)\) — the total number of inner-loop executions grows quadratically as the outer-loop limit increases.
- **Space Complexity:** \(O(1)\) — only a constant amount of extra space is used.

### 🔑 Key Takeaway

The number of inner-loop iterations depends on the outer-loop variable. Unlike two nested loops that each run five times, this example executes the inner loop a total of only 10 times.

---

## 15. Understanding Nested Loops with Decrementing Inner Loop

**Problem Statement:** Use nested `for` loops to print the values of `i` and `j`, where the inner loop starts at `i` and decrements until `j` reaches `0`. Count the total number of inner-loop executions.

### 💻 JavaScript Solution

```javascript
let count = 0;

for (let i = 0; i < 3; i++) {
    for (let j = i; j >= 0; j--) {
        console.log(`i = ${i}   j = ${j}`);
        count++;
    }
}

console.log("=====================");
console.log("Count is:", count);
```

### 📤 Output

```text
i = 0   j = 0
i = 1   j = 1
i = 1   j = 0
i = 2   j = 2
i = 2   j = 1
i = 2   j = 0
=====================
Count is: 6
```

### 🧠 How It Works

1. **Outer loop (`i`):** Runs from `0` to `2`.
2. **Inner loop (`j`):** Starts at the current value of `i` and decreases by `1` until `j` becomes `-1`.
3. **`count++`:** Increments the counter for every inner-loop execution.

### 📝 Iteration Breakdown

| Outer Loop (`i`) | Inner Loop Values (`j`) | Iterations |
|---:|---|---:|
| 0 | 0 | 1 |
| 1 | 1, 0 | 2 |
| 2 | 2, 1, 0 | 3 |
| **Total** | | **6** |

### 🔢 Count Calculation

\[
\text{Total Iterations} = 1 + 2 + 3 = 6
\]

For an outer loop running \(n\) times, this pattern executes the inner loop:

\[
\frac{n(n+1)}{2}
\]

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n^2)\) — the total number of iterations grows quadratically.
- **Space Complexity:** \(O(1)\) — only a constant amount of extra space is used.

### 🔑 Key Takeaway

The inner loop's starting value depends on the outer-loop variable. Since `j` starts at `i` and decreases to `0`, each outer iteration performs one more execution than the previous one.

---

## 16. Generating the Alphabet from A to Z Using ASCII Codes

**Problem Statement:** Write a function that generates all uppercase English letters from `A` to `Z` and returns them in an array.

### 💻 JavaScript Solution

```javascript
function generateAtoZ() {
    const letters = [];

    for (let code = 65; code <= 90; code++) {
        letters.push(String.fromCharCode(code));
    }

    return letters;
}

module.exports = { generateAtoZ };
```

### 🧠 How It Works

1. **Initialize an array:** `const letters = [];` creates an empty array to store the letters.
2. **Loop through ASCII codes:** The `for` loop iterates from `65` to `90`.
3. **Convert codes to characters:** `String.fromCharCode(code)` converts each numeric code into its corresponding uppercase letter.
4. **Add letters to the array:** `letters.push()` adds each letter to the array.
5. **Return the array:** `return letters;` returns all 26 uppercase letters.
6. **Export the function:** `module.exports = { generateAtoZ };` makes the function available to other CommonJS Node.js files.

### 📤 Example Usage and Output

To test the function, call it from your JavaScript file:

```javascript
const { generateAtoZ } = require("./yourFileName");

console.log(generateAtoZ());
```

**Output:**

```text
[
  'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I',
  'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R',
  'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'
]
```

*Replace `yourFileName` with your actual JavaScript filename, without the `.js` extension.*

### 🔑 Important Concepts

| Concept | Explanation |
|---|---|
| `String.fromCharCode()` | Converts a character code into a string character. |
| `letters.push()` | Adds a new element to the end of an array. |
| `return` | Sends the generated array back to the caller. |
| `module.exports` | Exports the function for use in other CommonJS modules. |

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(1)\) — the loop always runs exactly 26 times.
- **Space Complexity:** \(O(1)\) — the function always stores exactly 26 letters.

**Key Takeaway:** ASCII character codes allow us to generate letters programmatically instead of writing each character manually. This approach is useful for learning loops, character manipulation, and string-based DSA problems.

---
## 17. Printing a Square Pattern Using Nested Loops

**Problem Statement:** Write a program using nested `for` loops to print a square pattern of `x` characters with 4 rows and 4 columns.

### 💻 JavaScript Solution

```javascript
let n = 4;

for (let i = 0; i < n; i++) {
    let row = " ";

    for (let j = 0; j < n; j++) {
        row = row + " x ";
    }

    console.log(row);
}
```

### 📤 Output

```text
  x  x  x  x 
  x  x  x  x 
  x  x  x  x 
  x  x  x  x 
```

### 🧠 How It Works

1. **Initialize `n`:** Sets the size of the square to `4`.
2. **Outer loop (`i`):** Runs 4 times, creating 4 rows.
3. **Initialize `row`:** Starts with a single space for each new row.
4. **Inner loop (`j`):** Runs 4 times during each outer-loop iteration.
5. **Build the row:** `row = row + " x "` appends an `x` with spaces to the row string.
6. **Print the row:** `console.log(row)` prints the completed row after the inner loop finishes.

### 📝 Iteration Breakdown

| Outer Loop (`i`) | Inner Loop Executions | Result |
|---:|---:|---|
| 0 | 4 | Prints row 1 |
| 1 | 4 | Prints row 2 |
| 2 | 4 | Prints row 3 |
| 3 | 4 | Prints row 4 |
| **Total** | **16** | **4 × 4 square** |

### 🔢 Total Iterations

\[
\text{Total Iterations} = n \times n = 4 \times 4 = 16
\]

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n^2)\) — the inner loop runs `n` times for each of the `n` outer-loop iterations.
- **Auxiliary Space Complexity:** \(O(n)\) — the `row` string grows as the inner loop appends characters.

### 🔑 Key Takeaway

Nested loops are commonly used to print square, triangular, and other character patterns. The outer loop controls the **rows**, while the inner loop controls the **columns**.
---
## 18. Printing a Growing Pattern Using Nested Loops

**Problem Statement:** Use nested `for` loops to print a progressively growing pattern of `x` characters. The inner loop prints the row after adding each new character.

### 💻 JavaScript Solution

```javascript
let n = 4;

for (let i = 0; i < n; i++) {
    let row = " ";

    for (let j = 0; j < n; j++) {
        row = row + " x ";
        console.log(row);
    }
}
```

### 📤 Output

```text
  x
  x  x
  x  x  x
  x  x  x  x
  x
  x  x
  x  x  x
  x  x  x  x
  x
  x  x
  x  x  x
  x  x  x  x
  x
  x  x
  x  x  x
  x  x  x  x
```

*The pattern above repeats four times because the outer loop runs four times.*

### 🧠 How It Works

1. **Outer loop (`i`):** Runs 4 times, from `0` to `3`.
2. **Initialize `row`:** Each outer-loop iteration starts with a new string containing a space.
3. **Inner loop (`j`):** Runs 4 times for each outer-loop iteration.
4. **Build the pattern:** `row = row + " x "` adds another `x` to the existing string.
5. **Print the row:** `console.log(row)` is inside the inner loop, so it prints the string after every addition.

### 📝 Important Difference

Compare the position of `console.log(row)` in these two examples.

**Example 1: Inside the inner loop**

```javascript
for (let j = 0; j < n; j++) {
    row = row + " x ";
    console.log(row);
}
```

Each row is printed progressively, producing four output lines per outer-loop iteration.

**Example 2: Outside the inner loop**

```javascript
for (let j = 0; j < n; j++) {
    row = row + " x ";
}
console.log(row);
```

The completed row is printed only once, producing one output line per outer-loop iteration.

### 🔢 Total Executions

\[
\text{Total prints} = n \times n = 4 \times 4 = 16
\]

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n^2)\) — the inner loop executes \(n\) times for each of the \(n\) outer-loop iterations.
- **Auxiliary Space Complexity:** \(O(n)\) — the `row` string grows with each inner-loop iteration.

### 🔑 Key Takeaway

**The position of `console.log()` matters.** When it is inside the inner loop, intermediate results are printed. When it is outside the inner loop, only the completed row is printed.
---
## 19. Printing a Growing Pattern Using a Single Outer Loop

**Problem Statement:** Use nested `for` loops to print a growing pattern of `x` characters, displaying the pattern after adding each character.

### 💻 JavaScript Solution

```javascript
let n = 5;

for (let i = 0; i < 1; i++) {
    let row = " ";

    for (let j = 0; j < n; j++) {
        row = row + " x ";
        console.log(row);
    }
}
```

### 📤 Output

```text
  x
  x  x
  x  x  x
  x  x  x  x
  x  x  x  x  x
```

### 🧠 How It Works

1. **Initialize `n`:** Sets the number of `x` characters to `5`.
2. **Outer loop (`i`):** Runs only once because the condition is `i < 1`.
3. **Initialize `row`:** Starts with a string containing a space.
4. **Inner loop (`j`):** Runs 5 times, from `0` to `4`.
5. **Build the pattern:** `row = row + " x "` adds one more `x` during each iteration.
6. **Print the row:** `console.log(row)` prints the updated pattern immediately after each addition.

### 📝 Iteration Breakdown

| Inner Loop (`j`) | Number of `x` Characters | Output |
|---:|---:|---|
| 0 | 1 | `x` |
| 1 | 2 | `x x` |
| 2 | 3 | `x x x` |
| 3 | 4 | `x x x x` |
| 4 | 5 | `x x x x x` |

### 🔑 Key Takeaways

- The outer loop runs once, so the pattern is generated only once.
- The inner loop controls the number of `x` characters added.
- Placing `console.log(row)` inside the inner loop prints the pattern progressively.
- Changing `n` to `7`, for example, produces seven output lines, ending with seven `x` characters.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n)\) loop iterations because the outer loop runs once and the inner loop runs `n` times.
- **Space Complexity:** \(O(n)\) because the `row` string grows as characters are appended.

**Key takeaway:** The outer loop controls how many times the pattern is repeated, while the inner loop controls how the pattern grows.
---
## 20. Reversing a Pattern Using Nested Loops

**Problem Statement:** Write a JavaScript program using nested `for` loops to print a reverse pattern of `x` characters, starting with 5 characters and decreasing by 1 in each row.

### 💻 JavaScript Solution

```javascript
let n = 5;

for (let i = n; i >= 1; i--) {
    let row = " ";

    for (let j = 0; j < i; j++) {
        row = row + " x ";
    }

    console.log(row);
}
```

### 📤 Output

```text
  x  x  x  x  x
  x  x  x  x
  x  x  x
  x  x
  x
```

### 🧠 How It Works

1. **Initialize `n`:** Sets the maximum number of `x` characters to `5`.
2. **Outer loop (`i`):** Starts at `5` and decreases until `i` reaches `1`.
3. **Initialize `row`:** Creates a fresh string for every row.
4. **Inner loop (`j`):** Runs `i` times, adding one `x` during each iteration.
5. **Print the row:** Displays the completed row after the inner loop finishes.

### 📝 Iteration Breakdown

| Outer Loop (`i`) | Inner Loop Executions | Number of `x` Characters |
| ---------------: | --------------------: | -----------------------: |
|                5 |                     5 |                        5 |
|                4 |                     4 |                        4 |
|                3 |                     3 |                        3 |
|                2 |                     2 |                        2 |
|                1 |                     1 |                        1 |

### 🔑 Key Takeaways

- Use `i--` to decrease the number of characters in each row.
- The outer loop controls the number of rows.
- The inner loop controls the number of characters in each row.
- Moving `console.log(row)` outside the inner loop ensures that each completed row is printed only once.

### ⏱️ Time and Space Complexity

- **Time Complexity:** (O(n^2)) — the total number of character additions grows quadratically.
- **Auxiliary Space Complexity:** (O(n)) — the row string requires space proportional to its length.

**Key takeaway:** To reverse a pattern, start the outer loop at `n` and decrement it until it reaches `1`.

---
## 21. Printing a Number Triangle Pattern Using Nested Loops

**Problem Statement:** Write a JavaScript program using nested `for` loops to print a right-angled triangle pattern of numbers, starting from `1` and increasing the number of elements in each row.

### 💻 JavaScript Solution

```javascript
let n = 10;

for (let i = 0; i < n; i++) {
    let row = " ";

    for (let j = 0; j <= i; j++) {
        row = row + " " + (j + 1);
    }

    console.log(row);
}
```

### 📤 Output

```text
  1
  1 2
  1 2 3
  1 2 3 4
  1 2 3 4 5
  1 2 3 4 5 6
  1 2 3 4 5 6 7
  1 2 3 4 5 6 7 8
  1 2 3 4 5 6 7 8 9
  1 2 3 4 5 6 7 8 9 10
```

### 🧠 How It Works

1. **Initialize `n`:** Sets the total number of rows to `10`.
2. **Outer loop (`i`):** Runs from `0` to `9`, controlling the number of rows.
3. **Initialize `row`:** Creates a new string for each row.
4. **Inner loop (`j`):** Runs from `0` to `i`, adding numbers to the current row.
5. **Generate numbers:** `j + 1` converts the zero-based loop counter into numbers starting from `1`.
6. **Build the pattern:** `row = row + " " + (j + 1)` appends each number to the row.
7. **Print the row:** `console.log(row)` displays the completed row after the inner loop finishes.

### 📝 Iteration Breakdown

| Outer Loop (`i`) | Inner Loop Executions | Numbers Printed |
|---:|---:|---|
| 0 | 1 | `1` |
| 1 | 2 | `1 2` |
| 2 | 3 | `1 2 3` |
| 3 | 4 | `1 2 3 4` |
| 4 | 5 | `1 2 3 4 5` |
| ... | ... | ... |
| 9 | 10 | `1 2 3 4 5 6 7 8 9 10` |

### 🔢 Total Inner Loop Executions

Each row adds one more iteration than the previous row.

\[
\text{Total Iterations} = \frac{n(n+1)}{2}
\]

For \(n = 10\):

\[
\frac{10(10+1)}{2} = 55
\]

Therefore, the inner loop executes **55 times** in total.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n^2)\) — the inner loop performs an increasing number of operations for each row.
- **Auxiliary Space Complexity:** \(O(n)\) — the current row string grows with the number of elements in that row.

### 🔑 Key Takeaways

- The outer loop controls the number of rows.
- The inner loop controls how many numbers appear in each row.
- `j + 1` helps print numbers beginning at `1` instead of `0`.
- Placing `console.log(row)` outside the inner loop prints each completed row only once.

**DSA Pattern:** Nested loops are useful for printing number patterns, understanding iteration counts, and developing the logical thinking required for more advanced DSA problems.
---
## 22. Printing a Number Triangle with Repeated Row Values

**Problem Statement:** Write a JavaScript program using nested `for` loops to print a triangle in which each row contains the same number, repeated according to the row number.

### 💻 JavaScript Solution

```javascript
let n = 5;

for (let i = 0; i < n; i++) {
    let row = " ";

    for (let j = 0; j <= i; j++) {
        row = row + " " + (i + 1);
    }

    console.log(row);
}
```

### 📤 Output

```text
  1
  2 2
  3 3 3
  4 4 4 4
  5 5 5 5 5
```

### 🧠 How It Works

1. **Initialize `n`:** Sets the number of rows to `5`.
2. **Outer loop (`i`):** Runs from `0` to `4`, controlling the rows.
3. **Initialize `row`:** Creates a new empty-style string for each row.
4. **Inner loop (`j`):** Runs from `0` to `i`, determining how many times the current row number is repeated.
5. **Repeat the row number:** `(i + 1)` produces the current row number, starting from `1`.
6. **Build the pattern:** `row = row + " " + (i + 1)` appends the same number repeatedly.
7. **Print the row:** `console.log(row)` displays the completed row after the inner loop finishes.

### 📝 Iteration Breakdown

| Outer Loop (`i`) | Printed Number (`i + 1`) | Inner Loop Executions | Output |
|---:|---:|---:|---|
| 0 | 1 | 1 | `1` |
| 1 | 2 | 2 | `2 2` |
| 2 | 3 | 3 | `3 3 3` |
| 3 | 4 | 4 | `4 4 4 4` |
| 4 | 5 | 5 | `5 5 5 5 5` |

### 🔢 Total Iterations

The inner loop executes 1 time in the first row, 2 times in the second row, and so on.

\[
\text{Total Iterations} = \frac{n(n+1)}{2}
\]

For \(n = 5\):

\[
\frac{5(5+1)}{2} = 15
\]

Therefore, the inner loop executes **15 times** in total.

### ⏱️ Time and Space Complexity

- **Time Complexity:** \(O(n^2)\) — the number of operations increases quadratically as the number of rows grows.
- **Auxiliary Space Complexity:** \(O(n)\) — the `row` string grows with the number of elements in each row.

### 🔑 Key Takeaways

- The outer loop controls the row number.
- The inner loop determines how many times the number appears in each row.
- `i + 1` converts the zero-based loop counter into the desired number.
- The expression `(i + 1)` remains constant throughout each row, so the same number is printed repeatedly.

**DSA Pattern:** This problem builds your understanding of nested loops, row-based logic, and number-pattern problems commonly asked in programming interviews.

### Another Approach but same result... 

```javascript
let n = 5;

for (let i = 0; i <= n; i++) {
    let row = " ";

    for (let j = 1; j <= i; j++) {
        row = row + " " + i;
    }

    console.log(row);
}
...


### 📤 Output

```text
  1
  2 2
  3 3 3
  4 4 4 4
  5 5 5 5 5
```
---
# 🎯 Learning Goals

My goal is to progress from JavaScript fundamentals to advanced problem-solving concepts.

- [x] JavaScript variables and data types
- [x] Strings and concatenation
- [x] Arrays and nested arrays
- [x] Objects and properties
- [x] Functions and parameters
- [x] Return statements
- [x] Conditional statements
- [x] Loops (`for`, `while`, `do...while`)
- [ ] Array methods and common coding patterns
- [ ] Time and space complexity
- [ ] Searching and sorting algorithms
- [ ] Recursion and backtracking
- [ ] Linked lists, stacks, and queues
- [ ] Trees, graphs, and dynamic programming

---

## 💡 My Learning Philosophy

> **Consistency beats perfection. Learn the concept, write the code, understand the output, and practice until it becomes natural.**

I'm documenting my DSA journey one concept at a time to improve my programming skills and prepare for technical interviews.

⭐ If you're also learning DSA with JavaScript, feel free to explore this repository and learn along with me!

**Author:** Charith PBK  
**Language:** JavaScript  
**Focus:** Data Structures and Algorithms (DSA)

---

[⬆️ Back to Table of Contents](#-table-of-contents)
