# 🚀 DSA by Charith PBK

> **My journey of learning Data Structures and Algorithms using JavaScript.**

Welcome to my DSA learning repository! 👋

This repository contains my notes, JavaScript fundamentals, coding examples, and problem-solving concepts that I'm learning step by step. My goal is to strengthen my programming fundamentals and build a strong foundation for solving DSA problems.

---

## 📚 Table of Contents

- [Episode 1: JavaScript Fundamentals](#-episode-1-javascript-fundamentals)
  - Hello World
  - Variables and Strings
  - Arrays and Array Concatenation
  - Array Indexing and Nested Arrays
  - Objects
- [Episode 2: Functions and Control Flow](#-episode-2-functions-and-control-flow)
  - Printing Hello World
  - Functions with Parameters
  - Adding Two Numbers
  - Returning the Square of a Number
  - Voting Eligibility Checker
- [Learning Goals](#-learning-goals)

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

# 🎯 Learning Goals

My goal is to progress from JavaScript fundamentals to advanced problem-solving concepts.

- [x] JavaScript variables and data types
- [x] Strings and concatenation
- [x] Arrays and nested arrays
- [x] Objects and properties
- [x] Functions and parameters
- [x] Return statements
- [x] Conditional statements
- [ ] Loops (`for`, `while`, `do...while`)
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
