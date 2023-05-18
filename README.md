# Data Structures & Algorithms
<a href="https://jaggehn-portfolio.netlify.app/"><img alt="Website" src="https://img.shields.io/badge/Website-www.jaggehns.com-blue?style=flat-square&logo=google-chrome"></a>
<a href="https://www.linkedin.com/in/jaggehn-sivabalan/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Jaggehn%20Sivabalan-blue?style=flat-square&logo=linkedin"></a>
<a href="mailto:jaggehns@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-jaggehns@gmail.com-blue?style=flat-square&logo=gmail"></a>
<a href="https://www.instagram.com/jaggehn_/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-jaggehn__-blue?style=flat-square&logo=instagram"></a>

> In this repository, I document my learning journey of data structures and algorithms in JavaScript. This material can be used as a reference manual for developers, or you can refresh specific topics before an interview. Also, you can find ideas to solve problems more efficiently.


## Table of Contents

- [Algorithms](#algorithms)
  - [What is an Algorithm?](#what-is-an-algorithm)
  - [Why Algorithms?](#why-algorithms)
  - [Algorithm Analysis](#algorithm-analysis)
    - [Time Complexity](#time-complexity)
    - [Space Complexity](#space-complexity)
  - [Big-O Notation](#big-o-notation)
    - [Big-O Time Complexity](#big-o-time-complexity)
    - [Big-O Calculation](#big-o-calculation)
    - [Big-O Space Complexity](#big-o-space-complexity)
    - [Big-O Trend](#big-o-trend)
  - [Objects and Arrays Big-O](#objects-and-arrays-big-o)
    - [Objects Big-O](#objects-big-o)
    - [Arrays Big-0](#arrays-big-o)
  - [Math Algorithms](#math-algorithms)
    - [Fibonacci Sequence](#fibonacci-sequence)
    - [Factorial of a Number](#factorial-of-a-number)
    - [Prime Number](#prime-number)
      - [First Solution](#first-solution)
      - [Optimized Primality Test](#optimized-primality-test)

---

## Algorithms

### What is an Algorithm?

 - A set of well-defined instructions to solve a particular problem

#### Recipe Analogy
  
    - Algorithm to cook some tasty noodles
<img width="624" alt="Screenshot 2023-05-17 at 2 27 02 AM" src="https://github.com/jaggehns/DSA/assets/72048640/c7ae2fab-c3de-4843-a4b5-2e89f0289149">

#### Programming Analogy
  
    - Algorithm to add two numbers
<img width="624" alt="Screenshot 2023-05-17 at 2 02 06 AM" src="https://github.com/jaggehns/DSA/assets/72048640/071e64f2-19a3-40ba-9971-00a75967bd24">
  
#### Characteristics
- Well defined inputs & outputs
- Each step should be clear and unambiguous
- Language independent

---

### Why Algorithms?

#### Efficient problem solving

- Learning algorithms translates to learning different techniques to efficiently solve problems 
- One problem can be solved in many ways using different algorithms
- Every algorithm comes with its own trade-offs when it comes to performance

---

 ### Algorithm Analysis

  - We evaluate the performance of an algorithm in terms of its input size
  
#### Time Complexity
      - Amount of time taken for an algorithm to run, as a function of input size
  
#### Space Complexity
      - Amount of memory taken for an algorithm to run, as a function of input size
  
  ---
  
  - By evaluating against the input size, the analysis is not only machine independent but the comparison is also more appropriate
  
  - There is no one solution that works every single time. It is always good to know multiple ways to solve the problem and use the best solution, given your constraints
  
  - If your app needs to be very quick and has plenty of memory to work with, you don't have to worry about space complexity
  
  - If you have very little memory to work with, you should picl a solution that is relatively slower but needs less space
  
---

 ### Big-O Notation

####  The worse case complexity of an algorithm

- Big-O notation describes the complexity of an algorithm using algebraic terms
  
- It has two important characteristics
  - It is expressed in terms of the input
  - It focuses on the bigger picture without getting caught up in the minute details
  
---
  
#### Big-O Time Complexity
  
  <br />
  
  <img width="624" alt="Screenshot 2023-05-17 at 3 40 16 PM" src="https://github.com/jaggehns/DSA/assets/72048640/a53daec4-435f-4b6c-b5fa-2fc425b5be62">
  
  <br /> <br />
  
  <img width="624" alt="Screenshot 2023-05-17 at 3 41 26 PM" src="https://github.com/jaggehns/DSA/assets/72048640/54b05895-b87b-4881-804c-9432efb8cb3f">
  
  <br /><br />
  
  - It focuses on the bigger picture without getting caught up in the minute details
  
  <br /> <br />
  
<img width="624" alt="Screenshot 2023-05-17 at 3 53 17 PM" src="https://github.com/jaggehns/DSA/assets/72048640/f512c813-3433-403d-8450-39c0fc736f75">
  
---
  
  #### Big-O Calculation 
  
   <br />
  
  <img width="624" alt="Screenshot 2023-05-17 at 3 58 23 PM" src="https://github.com/jaggehns/DSA/assets/72048640/bb4b7ec1-03b8-4327-bba8-405812d8e0bf">
  
  <br /><br />
  
<img width="624" alt="Screenshot 2023-05-17 at 4 01 31 PM" src="https://github.com/jaggehns/DSA/assets/72048640/b80e8aac-5d9a-4227-9433-2c128dfc4858">
  
---
  
  #### Big-O Space Complexity
  
      O(1) - Constant - Sorting Algorithms etc.
  
      O(n) - Linear
  
      O(logn) - Logarithmic
  
 ---
  
  #### Big-O Trend
  
  <br />
  
  <img width="624" alt="Screenshot 2023-05-17 at 4 09 37 PM" src="https://github.com/jaggehns/DSA/assets/72048640/df5a8415-c0da-4147-90f0-86ad1e002a13">

---

### Objects and Arrays Big-O

 #### Objects Big-O
  
  - an object is a collection of key value pairs
  
  <br />
  
 ```js
  const person = {
    firstName: 'Bruce',
    lastName: 'Wayne'
  }
  ```
  
  <br /><br />
  
    Insert - O(1)
  
    Remove - O(1)
  
    Access - O(1)
  
    Search - O(n)
  
    Object.keys() - O(n)
  
    Object.values() - O(n)
  
    Object.entries() - O(n)
  
---
  
   #### Arrays Big-O
  
  - an array is an ordered collection of values
  
  <br />
  
 ```js
  const odd = [1, 3, 5, 7, 9]
  ```

  <br /><br />
  
    Insert / remove at end - O(1)
  
    Insert / remove at beginning - O(n) - index needs to be reset
  
    Access - O(1)
  
    Search - O(n)
  
    Push / pop - O(1)
  
    Shift / unshift / concat / slice / splice - O(n)
  
    forEach / map / filter / reduce - O(n)

---

### Math Algorithms

 #### [Fibonacci Sequence](algorithms/math-algorithms/fibonacci-sequence/fibonacci-sequence.js)
  
  **Problem** - Given a number 'n', find the first 'n' elements of the Fibonacci Sequence
  
   In mathematics, the Fibonacci sequence is a sequence in which each number is the sum      of the two preceeding ones
  
     The first two numbers in the sequence are 0 and 1
  
     fibonacci(2) = [0,1]
     fibonacci(3) = [0,1,1]
     fibonacci(7) = [0,1,1,2,3,5,8]
  
  
  ```js
  const fibonacci = (n) => {
     const fib = [0, 1];

     for (let i = 2; i < n; i++) {
       fib[i] = fib[i - 1] + fib[i - 2];
     }

     return fib;
  };
  ```
   - Big O - O(n)                 
                           
---
  
  #### [Factorial of a Number](algorithms/math-algorithms/factorial-of-a-number/factorial-of-a-number.js)
  
  **Problem** - Given an integer 'n', find the factorial of that integer
  
   In mathematics, the factorial of a non-negative integer 'n', denoted n!, is the          product of all positive integers less than or equal to 'n'
   
   The first two numbers in the sequence are 0 and 1
  
     Factorial of zero is 1
     factorial(4) = 4*3*2*1 = 24
     factorial(5) = 5*4*3*2*1 = 120
  
  
```js
const factorial = (n) => {
   let result = 1;
   
   //i = 2 because multiplying by 1 has no effect
   for (let i = 2; i <= n; i++) {
     result *= i;
   }
   
   return result;
};
```
   - Big O - O(n)       

---

  #### [Prime Number](algorithms/math-algorithms/prime-number/prime-number.js)
  
  **Problem** - Given a natural number 'n', determine if the number is prime or not
  
   A prime number is a natural number greater than 1 that is not a product of two smaller    natural numbers
  
     isPrime(5) = true (1*5 or 5*1)
     isPrime(4) = false (1*4 or 2*2 or 4*1)
  
  #### First Solution

```js
const isPrime = (n) => {
  if (n < 2) {
    return false;
  }

  for (let i = 2; i < n; i++) {
    if (n % i === 0) {
      return false;
    }
  }

  return true;
};
```
   - Big O - O(n)

---

  #### Optimized Primality Test

  Integers larger than the square root do not need to be checked because, whenever         'n=a*b', one of the two factors 'a' and 'b' is less than or equal to the square root of   'n'
  
     n=24, a=4 and b=6
     The square root of 24 is is 4.89
     4 is less than 4.89
     a is less than the square root of n
     
     n=35, a=5 and b=7
     The square root of 35 is 5.91
     5 is less than 5.91
     a is less than the square root of n

```js
const isOptimizedPrime = (n) => {
  if (n < 2) {
    return false;
  }

  for (let i = 2; i <= Math.sqrt(n); i++) {
    if (n % i === 0) {
      return false;
    }
  }

  return true;
};
```
   - Big O - O(sqrt(n))       

---
