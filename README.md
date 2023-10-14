
# 🚀 JAVASCRIPT QUIZ 🚀

### Welcome to the JavaScript Quiz! 🎉 Get ready to embark on a JavaScript journey full of twists, turns, and some laughter along the way. 🤪 Test your JavaScript knowledge with these tricky questions and discover the secrets of this magical language! ✨

### Are you ready? Let's dive in and have some fun! 🎯


## 😄 Question 1: The Mysterious Loop

**You're in for a treat! Dive into this JavaScript adventure and solve the mystery of the loop.** 🕵️

```javascript
for (var i = 0; i < 5; i++) {
  setTimeout(function() {
    console.log(i);
  }, 100);
}

```

A. 🤨 0 1 2 3 4

B. 🤣 5 5 5 5 5

C. 😅 1 2 3 4 5

D. 😇 None of the above

<details>
<summary>Answer</summary>
The correct answer is option B. The output will be "5" printed five times because JavaScript loves surprises!
</details>
<details>
<summary>Explanation</summary>
In this code, JavaScript plays a little prank with closures. The setTimeout function captures the variable `i`, and it decides to shout "5" five times after the loop's done. Sneaky, isn't it? 🙃
</details>

## 😄 Question 2: The Null and Undefined Showdown

**Get ready for the ultimate showdown: `null` vs. `undefined`! Who's who in the JavaScript world?** 🤼‍♂️

Options:

A. 🤔 `null` is a variable that has been declared but has not been assigned a value.

B. 😇 `undefined` is a value that represents the intentional absence of any object value.

C. 🤣 `null` is a value that represents the intentional absence of any object value.

D. 😅 `undefined` is a variable that has been declared but has not been assigned a value.

<details>
<summary>Answer</summary>
The correct answer is option C. `null` plays the part of representing the intentional absence of any object value, while `undefined` is the variable that's just not quite sure what's going on.
</details>

<details>
<summary>Explanation</summary>
In the world of JavaScript, `null` is the actor who says, "I intentionally have no value!" while `undefined` is the character who's like, "Wait, did I miss something? 🤷‍♂️"
</details>



## 😄 Question 3: The Map-a-Palooza

**It's time to uncover the magic of the `map` function in arrays! Get ready for a fun ride. 🎢**

Options:

A. 🙅‍♂️ To remove elements from an array.

B. 🙉 To add elements to the beginning of an array.

C. 🚀 To create a new array by applying a provided function to each element of an existing array.

D. 🧐 To find the maximum value in an array.

<details>
<summary>Answer</summary>
The correct answer is option C. The `map` function is like a superhero that creates a brand-new array by working its magic on each element of an existing array.
</details>

<details>
<summary>Explanation</summary>
Imagine the `map` function as a fantastic painter. It takes your old array and transforms it into a brand-new masterpiece using a special formula for each element. Voilà! It's like art for arrays. 🎨🤩
</details>



## 😄 Question 4: The Hunt for Primitives

**Time for a primitive data type adventure! Can you spot the odd one out in the JavaScript world?** 🕵️‍♂️

Options:

A. 🧶 String

B. 🚀 Object

C. 🎉 Boolean

D. 😇 Undefined

<details>
<summary>Answer</summary>
The correct answer is option B. "Object" is the party crasher here; it's not a primitive data type in JavaScript.
</details>

<details>
<summary>Explanation</summary>
In the realm of JavaScript, primitive data types are like the cool kids at the playground: String, Number, Boolean, Undefined, Null, and Symbol. Objects, on the other hand, are more like the grown-ups, with their own rules and fancy properties. 🧶🕴️
</details>



## Question 5
**What is the output of the following JavaScript code?**

```javascript
const a = [1, 2, 3];
const b = a;

a.push(4);

console.log(b);
```

`A`. [1, 2, 3]

`B`. [1, 2, 3, 4]

`C`. [4]

`D`. None of the above

<details>
<summary>Answer</summary>
The correct answer is option B. The output will be [1, 2, 3, 4].
</details>
<details>
<summary>Explanation</summary>
In JavaScript, when you assign an array to another variable, you are creating a reference to the same array. So, when you modify `a` by pushing 4 into it, the array referred to by `b` is also modified, resulting in [1, 2, 3, 4].
</details>

## Question 6

**What does the following JavaScript code do?**

```javascript
function foo() {
  return bar();
}

function bar() {
  return "Hello, World!";
}

console.log(foo());
```
`A`. It returns the string "Hello, World!".

`B`. It throws a runtime error.

`C`. It returns undefined.

`D`. It goes into an infinite loop.

<details>
<summary>Answer</summary>
The correct answer is option A. It returns the string "Hello, World!".
</details>
<details>
<summary>Explanation</summary>
The `foo` function calls the `bar` function, which returns the string "Hello, World!". Therefore, the output of `foo()` is "Hello, World!".
</details>











