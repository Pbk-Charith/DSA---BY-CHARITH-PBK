# 🚀 DSA by Charith PBK

> **My journey of learning Data Structures and Algorithms using JavaScript.**

Welcome to my DSA learning repository! 👋

This repository contains my notes, JavaScript fundamentals, coding examples, and problem-solving concepts that I'm learning step by step. My goal is to strengthen my programming fundamentals and build a strong foundation for solving DSA problems.

---

## 📚 Table of Contents

- **[🟢 Episode 1: JavaScript Fundamentals](#-episode-1-javascript-fundamentals)**
  - [1. Printing Hello World](#1-printing-hello-world)
  - [2. Variables and String Concatenation](#2-variables-and-string-concatenation)
  - [3. Arrays and Array Concatenation](#3-arrays-and-array-concatenation)
  - [4. Accessing Array Elements](#4-accessing-array-elements)
  - [5. Nested Arrays](#5-nested-arrays)
  - [6. JavaScript Objects](#6-javascript-objects)

- **[🔵 Episode 2: Functions and Control Flow](#-episode-2-functions-and-control-flow)**
  - [1. Printing Hello World Using a Function](#1-printing-hello-world-using-a-function)
  - [2. Functions with Parameters](#2-functions-with-parameters)
  - [3. Creating a Function to Add Two Numbers](#3-creating-a-function-to-add-two-numbers)
  - [4. Finding the Square of a Number Using `return`](#4-finding-the-square-of-a-number-using-return)
  - [5. Checking Voting Eligibility Using Conditional Statements](#5-checking-voting-eligibility-using-conditional-statements)
  - [6. Checking Whether a Number Is Even or Odd](#6-checking-whether-a-number-is-even-or-odd)
  - [7. Introduction to Loops in JavaScript](#7-introduction-to-loops-in-javascript)
  - [8. Linear Search in an Array](#8-linear-search-in-an-array)
  - [9. Counting Negative Numbers in an Array](#9-counting-negative-numbers-in-an-array)
  - [10. Finding the Largest Number in an Array](#10-finding-the-largest-number-in-an-array)
  - [11. Finding the Smallest Number in an Array](#11-finding-the-smallest-number-in-an-array)
  - [12. Finding the Second Largest Number in an Array](#12-finding-the-second-largest-number-in-an-array)
  - [13. Understanding Nested Loops in JavaScript](#13-understanding-nested-loops-in-javascript)

- **[🎯 Learning Goals](#-learning-goals)**
- **[💡 My Learning Philosophy](#-my-learning-philosophy)**

- **[Learning Goals](#-learning-goals)**

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
