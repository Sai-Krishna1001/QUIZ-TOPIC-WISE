# QUIZ-TOPIC-WISE

# JavaScript Quiz

### Welcome to the JavaScript Quiz! Test your knowledge of JavaScript with these tricky questions. Check your answers and read the explanations to learn more.

## Question 1

**What is the output of this code?**

```javascript
for (var i = 0; i < 5; i++) {
  setTimeout(function() {
    console.log(i);
  }, 100);
}
```

`A`. 0 1 2 3 4
`B`. 5 5 5 5 5
`C`. 1 2 3 4 5
`D`. None of the above
<details>
<summary>Answer</summary>
The output will be "5" printed five times.

</details>
<details>
<summary>Explanation</summary>
This is a common mistake in JavaScript due to closures. In this code, a setTimeout function is inside a for loop, and it captures the variable i. However, the setTimeout callback is executed after the loop has completed, and the value of i is 5. Therefore, it will log "5" five times.

</details>

## Question 2

**What is the difference between `null` and `undefined` in JavaScript?**

`A`. `null` is a variable that has been declared but has not been assigned a value.
`B`. `undefined` is a value that represents the intentional absence of any object value.
`C`. `null` is a value that represents the intentional absence of any object value.
`D`. `undefined` is a variable that has been declared but has not been assigned a value.

<details>
<summary>Answer</summary>
The correct answer is option 3. `null` is a value that represents the intentional absence of any object value, while `undefined` is a variable that has been declared but has not been assigned a value.
</details>

<details>
<summary>Explanation</summary>
`null` is a value that can be assigned to a variable to represent that it has no value or that it is explicitly empty. On the other hand, `undefined` means a variable has been declared but hasn't been assigned any value. In some cases, JavaScript sets variables to `undefined` by default.
</details>


## Question 3

**What is the purpose of the JavaScript `map` function in arrays?**

`A`. To remove elements from an array.
`B`. To add elements to the beginning of an array.
`C`. To create a new array by applying a provided function to each element of an existing array.
`D`. To find the maximum value in an array.

<details>
<summary>Answer</summary>
The correct answer is option 3. The `map` function is used to create a new array by applying a provided function to each element of an existing array. It returns a new array with the results.
</details>

<details>
<summary>Explanation</summary>
The `map` function is a higher-order function in JavaScript that is commonly used for transforming data in arrays. It applies a given function to each element of the array, creating a new array with the results. This allows for a more concise and functional approach to array manipulation.
</details>


## Question 4

**Which of the following is NOT a primitive data type in JavaScript?**

A. String
B. Object
C. Boolean
D. Undefined

<details>
<summary>Answer</summary>
The answer is option 2, "Object." Objects are not primitive data types in JavaScript.
</details>

<details>
<summary>Explanation</summary>
In JavaScript, primitive data types include String, Number, Boolean, Undefined, Null, and Symbol. Objects, on the other hand, are considered reference data types because they can hold multiple values and have properties and methods.
</details>






