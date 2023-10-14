
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
Options:


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



## 😄 Question 5: The Great Array Adventure

**Get ready for an epic array adventure! What happens when arrays collide in JavaScript?** 🦸‍♂️

```javascript
const a = [1, 2, 3];
const b = a;

a.push(4);

console.log(b);

```

Options:

A. 🚁 [1, 2, 3]

B. 🚀 [1, 2, 3, 4]

C. 🌪️ [4]

D. 😇 None of the above

<details>
<summary>Answer</summary>
The correct answer is option B. It's a teamwork of arrays, and the result is [1, 2, 3, 4].
</details>
<details>
<summary>Explanation</summary>
In the magical land of JavaScript, arrays have a special bond. When one changes, the other feels it too. When `a` adds a 4, `b` is there to celebrate the array growth. Teamwork makes the dream work! 🚀🌟
</details>

## 😄 Question 6: The Whimsical Functions

**Get ready for a whimsical adventure with JavaScript functions! Let's see how they play together. 🤹‍♂️**

```javascript
function foo() {
  return bar();
}

function bar() {
  return "Hello, World!";
}

console.log(foo());

```
Options:

A. 🎉 It returns the string "Hello, World!" and throws a mini celebration.

B. 😱 It throws a runtime error and the functions decide to have a tea party instead.

C. 😇 It returns undefined and quietly sips a cup of coffee.

D. 🌀 It goes into an infinite loop and starts spinning around in code circles.

<details>
<summary>Answer</summary>
The correct answer is option A. It's a party in JavaScript-land as it returns the string "Hello, World!" and celebrates with confetti!
</details>
<details>
<summary>Explanation</summary>
In this magical JavaScript world, `foo` invites `bar` for a chat. And guess what? They exchange greetings and "Hello, World!" is the life of the party! 🥳🎈
</details>

## 😄 Question 7: The Magical Promise

**Enter the realm of JavaScript Promises, where the code is full of surprises!** 🌠

```javascript
function asyncTask(ms) {
  return new Promise(resolve => {
    setTimeout(() => {
      resolve(ms);
    }, ms);
  });
}

async function executeTasks() {
  const tasks = [asyncTask(200), asyncTask(100), asyncTask(300)];
  const results = await Promise.all(tasks);
  return results;
}

executeTasks()
  .then(data => console.log(data))
  .catch(error => console.error(error));
```
Options:

A. 🎉 [200, 100, 300]

B. 😅 [100, 200, 300]

C. 🤯 [300, 200, 100]

D.  🌠 The order is not guaranteed; it depends on the execution time of promises.

<details>
<summary>Answer</summary>
The correct answer is option D. It's a magical show, and the order is not guaranteed; it depends on the execution time of promises.
</details>
<details>
<summary>Explanation</summary>
In the world of asynchronous JavaScript, promises are like magic spells. The order of their execution depends on the promises' mood and how fast they can perform their tricks. It's all about timing! 🌠✨
</details>

## 😄 Question 8: The Scrambled Code

**Time for some code detective work! Can you unravel this JavaScript mystery?** 🕵️‍♀️

```javascript
const mystery = () => {
  return {
    fun: () => {
      return "JavaScript is awesome!";
    },
  };
};

console.log(mystery().fun());
```
Options:

A. 🤯 "JavaScript is awesome!"

B. 😄 It throws a confetti party!

C. 🙈 "fun is not a function."

D. 🚀 "undefined"

<details>
<summary>Answer</summary>
The correct answer is option A. It's a pure celebration: "JavaScript is awesome!"
</details>
<details>
<summary>Explanation</summary>
In this code, there's a little mystery, but not a real one! The `mystery` function returns an object with a `fun` function inside, and that `fun` function is all about celebrating the awesomeness of JavaScript. 🎉😎
</details>

## 😄 Question 9: The Slippery Scope

**Let's delve into the mysteries of scope in JavaScript! Can you predict the outcome?** 🔍

```javascript
let scopeVar = "global";

function trickyScope() {
  if (true) {
    let scopeVar = "local";
  }
  return scopeVar;
}

console.log(trickyScope());
```
Options:

A. 🌎 "global"

B. 🤯 "local"

C. 😅 "undefined"

D. 🎉 "local" followed by a surprise party

<details>
<summary>Answer</summary>
The correct answer is option A. It's "global" all the way in the world of JavaScript scope!
</details>
<details>
<summary>Explanation</summary>
In this tricky scenario, there's a global `scopeVar` and a local `scopeVar`. However, the local one doesn't affect the global one, and the function returns the global "scopeVar." No surprises this time! 🔍🎩🌐
</details>

## 😄 Question 10: The Enigmatic Callback

**Get ready to decipher the world of JavaScript callbacks! Can you predict the outcome?** 🧩

```javascript
function performMagic(callback) {
  setTimeout(function() {
    callback("You've unlocked the callback magic!");
  }, 1000);
}

performMagic(function(result) {
  console.log(result);
});
```
Options:

A. 🧙 "You've unlocked the callback magic!"

B. 🎉 "Magic is in the air!"

C. 🤯 "Callback hell!"

D. 😅 It throws a timeout error.

<details>
<summary>Answer</summary>
The correct answer is option A. It's the sweet sound of success: "You've unlocked the callback magic!"
</details>
<details>
<summary>Explanation</summary>
In this enigmatic JavaScript scenario, the `performMagic` function uses a callback to reveal its magical message. After 1 second, the callback unlocks the magic and logs the message to the console. ✨🎩
</details>

## 😄 Question 11: The Arrow Mystery

**Time to explore the mysteries of arrow functions in JavaScript! Are you up for the challenge?** 🏹

```javascript
const arrowFunction = () => {
  return this;
};

function regularFunction() {
  return this;
}

const mysteryObject = {
  key1: arrowFunction(),
  key2: regularFunction(),
};

console.log(mysteryObject.key1 === mysteryObject.key2);
```
Options:

A. 😅 true

B. 🤯 false

C. 🏹 It throws a "this" party.

D. 🎉 undefined

<details>
<summary>Answer</summary>
The correct answer is option B. It's a mystery - `false` is the outcome!
</details>
<details>
<summary>Explanation</summary>
In the world of JavaScript, arrow functions and regular functions handle the `this` keyword differently. Arrow functions don't have their own `this` context, while regular functions do. In this mystery, they're not equal! 🤷‍♂️🔍🏹
</details>

## 😄 Question 12: The Infinity Conundrum

**Time to tackle an infinity riddle in JavaScript! Are you ready for the challenge?** 🌌

```javascript
const infinityMath = Math.pow(2, 1023) * 2;

const isInfinity = Number.isFinite(infinityMath);

console.log(isInfinity);
```
Options:

A. 🌌 false

B. 🤯 true

C. 😄 NaN

D. 🚀 It creates a black hole in your console.

<details>
<summary>Answer</summary>
The correct answer is option A. It's not a black hole; it's `false` because `infinityMath` is indeed `Infinity`.
</details>
<details>
<summary>Explanation</summary>
In this JavaScript universe, we're dealing with incredibly large numbers. `Number.isFinite` checks if a number is finite or not. Despite the large value, it's `Infinity`, which is not a finite number. No black holes here! 🪐🔭🌌
</details>

## 😄 Question 13: The Array Alchemy

**Get ready to perform some array alchemy in JavaScript, spiced up with funny emojis! Can you predict the outcome?** 🎩🍭

```javascript
const wizardSkills = ["🧙‍♂️", "✨", "🦄", "🔮"];

const advancedSkills = wizardSkills.slice(2);

advancedSkills.push("⏰");

console.log(wizardSkills);
```
Options:

A. 🔮 ["🧙‍♂️", "✨", "🦄", "🔮"]

B. 🍭 ["🧙‍♂️", "✨", "🦄", "🔮", "⏰"]

C. 😅 ["🦄", "🔮", "⏰"]

D. 🎉 ["🔮", "⏰"]

<details>
<summary>Answer</summary>
The correct answer is option A. The original array remains untouched: ["🧙‍♂️", "✨", "🦄", "🔮"].
</details>
<details>
<summary>Explanation</summary>
In this array alchemy spiced up with funny emojis, we create a new array `advancedSkills` by slicing a portion of `wizardSkills` and then push "⏰" into `advancedSkills`. However, this doesn't affect the original array. 🎩🍭📦
</details>

## 😄 Question 14: The Magic of Equality

**It's time to unravel the mysteries of equality in JavaScript! Can you determine the outcome?** 🔍🔗

```javascript
const firstMagic = [1, 2, 3];
const secondMagic = [1, 2, 3];

const areTheyEqual = firstMagic == secondMagic;

console.log(areTheyEqual);
```
Options:

A. 🎩 true

B. 🤯 false

C. 🎉 It triggers a magic showdown.

D. 😅 It throws a syntax error.

<details>
<summary>Answer</summary>
The correct answer is option B. The magic of JavaScript equality is tricky - it's `false`!
</details>
<details>
<summary>Explanation</summary>
In the world of JavaScript, comparing two arrays with `==` checks if they reference the same object, not if their contents are the same. In this case, the arrays are different objects, so it's `false`. 🎩🔗📜
</details>

## 😄 Question 15: The Mysterious Spread

**Get ready to dive into the mysteries of the JavaScript spread operator! Can you unveil its secrets?** 🌊✨

```javascript
const originalArray = [1, 2, 3];
const mysteriousCopy = [...originalArray];

mysteriousCopy.push(4);

console.log(originalArray);
```
Options:

A. 🌊 [1, 2, 3]

B. 🤯 [1, 2, 3, 4]

C. 😅 [4]

D. 🎩 It creates a parallel universe in your console.

<details>
<summary>Answer</summary>
The correct answer is option A. The original array remains unchanged: [1, 2, 3].
</details>
<details>
<summary>Explanation</summary>
In this JavaScript mystery, we make a copy of `originalArray` using the spread operator. When we push 4 into `mysteriousCopy`, the original array is unaffected. The spread operator creates a true copy. 🌊✨🔮
</details>

## 😄 Question 16: The Magical NaN

**Let's delve into the world of NaN in JavaScript! Can you decipher its mystical properties?** 🧙‍♂️🔮

```javascript
const mystery1 = NaN;
const mystery2 = 0 / 0;

const areTheyEqual = mystery1 === mystery2;

console.log(areTheyEqual);
```
Options:

A. 🧙‍♂️ true

B. 🤯 false

C. 😅 NaN

D. 🎩 It opens a portal to the unknown.

<details>
<summary>Answer</summary>
The correct answer is option B. NaN is so mysterious that even when two NaN values are compared, it's `false`!
</details>
<details>
<summary>Explanation</summary>
In the realm of JavaScript, NaN (Not-a-Number) is indeed mysterious. When you compare two NaN values with `===`, it's always `false`. It's one of JavaScript's peculiarities. 🧙‍♂️🔮📜
</details>

## 😄 Question 17: The Fantastic Function

**Get ready to explore the world of JavaScript functions! Can you anticipate the outcome of this magical function?** 🌟🔮

```javascript
function magicalFunction(a, b) {
  return a + b;
}

const result = magicalFunction(3, "3");

console.log(result);
```
Options:

A. 🌟 6

B. 🤯 33

C. 😅 TypeError

D. 🎩 undefined

<details>
<summary>Answer</summary>
The correct answer is option B. JavaScript's loose typing leads to "33" because it converts the number to a string and performs string concatenation.
</details>
<details>
<summary>Explanation</summary>
JavaScript's dynamic typing allows it to implicitly convert the number to a string and perform string concatenation when you add a number and a string. In this case, "3" + 3 results in "33". 🌟🔮📜
</details>




