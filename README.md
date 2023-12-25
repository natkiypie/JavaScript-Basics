# ![JavaScript](./assets/javascript.png) JavaScript - Study Plan

## Weeks 1-3: JavaScript Basics

**Days 1-2: Introduction to JavaScript**

- _Resource_:
  - [ MDN Web Docs - JavaScript Guide ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- _Exercise_: Set up your development environment and write a "Hello World" program.
- _Coding Challenge_: Complete simple JavaScript challenges on [CodeWars](https://www.codewars.com/kata/search/my-languages?q=JavaScript&beta).
- _Project_: Create a simple webpage with JavaScript that displays an alert or changes the content dynamically.

```JavaScript
// example:

console.log("Hello, World!");

```

**Days 3-5: Variables, Data Types, and Operators**

- Resource:
  - [ W3Schools - JavaScript Variables ](https://www.w3schools.com/js/js_variables.asp)
  - [ JavaScript Tutorial for Beginners: Learn JavaScript in 1 Hour ](https://youtu.be/W6NZfCO5SIk?si=MAp4y9fhztbNT9l3)
- Exercise: Practice creating variables, working with different data types, and using operators.
- _Coding Challenge_: Solve JavaScript challenges focusing on variables and operators on [CodeWars](https://www.codewars.com/kata/50ee6b0bdeab583673000025/javascript).
- _Project_: Build a basic calculator that takes user input and performs arithmetic operations.

```JavaScript
// example:

let name = "John";
let age = 25;
let isStudent = true;

console.log(name, age, isStudent);
```

**Days 6-8: Control Flow (If statements, loops)**

- _Resource_:
  - [ JavaScript.info - Control flow ](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
  - [ Code Institute - Control flow ](https://codeinstitute.net/global/blog/control-flow-in-javascript/)
  - [ JavaScript Tutorial for Beginners: Learn JavaScript in 1 Hour ](https://youtu.be/W6NZfCO5SIk?si=MAp4y9fhztbNT9l3)
- _Exercise_: Write programs that involve if statements and loops.
- _Coding Challenge_: Complete challenges related to control flow on [Sololearn](https://www.sololearn.com/en/Discuss/1338132/javascript-control-flow-exercise).
- _Project_: Create a program that checks if a given number is prime.

```JavaScript
// example:

let num = 10;

if (num > 0) {
  console.log("Positive number");
} else {
  console.log("Negative number or zero");
}

for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

**Days 9-10: Functions**

- _Resource_:
  - [ MDN Web Docs - Functions ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
  - [ JavaScript Functions - Lookkle](https://www.lookkle.com/javascript-functions-practice-for-beginners)
  - [ JavaScript Functions - The Net Ninja (YouTube) ](https://www.youtube.com/watch?v=xUI5Tsl2JpY)
- _Exercise_: Create functions, understand parameters and return values.
- _Coding Challenge_: Solve challenges focused on functions on [edabit](https://edabit.com/challenges/javascript)
- _Project_: Develop a simple to-do list application with add, delete, and mark as completed functionalities.

```JavaScript
// example:

function greet(name) {
  return "Hello, " + name + "!";
}

let message = greet("Alice");
console.log(message);
```

## Weeks 4-6: DOM Manipulation and Asynchronous JavaScript

**Days 11-12: Document Object Model (DOM)**

- _Resource_:
  - [ MDN Web Docs - Introduction to the DOM ](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
  - [ JavaScript DOM Tutorial - Net Ninja (YouTube) ](https://www.youtube.com/watch?v=FIORjGvT0kk)
- _Exercise_: Manipulate the DOM using JavaScript.
- _Coding Challenge II_: Solve challenges related to DOM manipulation on [CroCoder](https://www.crocoder.dev/blog/the-dom-exercises/).
- _Coding Challenge I_: Solve challenges related to DOM manipulation on [CodeWars](https://www.codewars.com/kata/5b3cd4e72f4b20e09600018b).
- _Project_: Build a dynamic webpage that allows users to add and remove elements.

```html
<!-- example: -->

<!doctype html>
<html>
  <body>
    <h2>JavaScript DOM Example</h2>

    <p id="demo">This is a paragraph.</p>

    <script>
      document.getElementById("demo").innerHTML = "Hello, DOM!";
    </script>
  </body>
</html>
```

**Days 13-15: Event Handling and Callbacks**

- _Resource_:
  - [ W3Schools - JavaScript Events ](https://www.w3schools.com/js/js_events.asp)
  - [ Mozilla - Introduction to events ](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
  - [ JavaScript DOM Tutorial - Net Ninja (YouTube) ](https://www.youtube.com/watch?v=FIORjGvT0kk)
- _Exercise_: Practice handling events and using callbacks.
- _Coding Challenge_: Complete challenges related to event handling on [mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Test_your_skills:_Events).
- _Coding Challenge_: Complete challenges related to event handling on [w3resource](https://www.w3resource.com/javascript-exercises/event/index.php).
- _Project_: Create an interactive form with JavaScript validation.

```html
<!-- example: -->

<!doctype html>
<html>
  <body>
    <button onclick="myFunction()">Click me</button>

    <script>
      function myFunction() {
        alert("Button clicked!");
      }
    </script>
  </body>
</html>
```

**Days 16-17: Asynchronous JavaScript (Promises)**

- _Resource_:
  - [ MDN Web Docs - Promises ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
  - [ freeCodeCamp - How JavaScript Promises Work – Tutorial for Beginners ](https://www.freecodecamp.org/news/javascript-promise-object-explained/)
  - [ JavaScript Promises - Traversy Media (YouTube) ](https://www.youtube.com/watch?v=XJEHuBZQ5dU)
  - [ JavaScript Async: Callbacks, Promises & Async Await - Traversy Media (YouTube) ](https://www.youtube.com/watch?v=PoRJizFvM7s)
- _Exercise_: Understand and practice asynchronous programming with Promises.
- _Coding Challenge_: Solve challenges related to Promises on [CodeWars](https://www.codewars.com/collections/async-and-promises).
- _Project_: Fetch data from a public API and display it on your webpage.

```JavaScript
// example:

function fetchData() {
  return new Promise((resolve, reject) => {
    // Simulating an asynchronous operation
    setTimeout(() => {
      const data = { name: "John", age: 30 };
      resolve(data);
    }, 2000);
  });
}

fetchData().then((result) => {
  console.log(result);
});
```

**Days 18-20: AJAX and Fetch API**

- _Resource_:
  - [ MDN Web Docs - Fetch APIFetch ](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
  - [ Fetch API - Traversy Media (YouTube) ](https://www.youtube.com/watch?v=Oive66jrwBs)
- _Exercise_: Fetch data from an API and update the DOM dynamically.
- _Coding Challenge_: Complete challenges related to Fetch API on [ github.com/lilybarrett/es6-fetch-api-practice ](https://github.com/lilybarrett/es6-fetch-api-practice/blob/master/es6-fetch-api.md).
- _Project_: Build a weather app that fetches and displays current weather information.

```JavaScript
// example:

fetch('https://jsonplaceholder.typicode.com/posts/1')
  .then(response => response.json())
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error('Error:', error);
  });
```

## Additional Resources:

- Coding Challenges:

  - [ Follow along with Sampath's 100 days of coding ](https://medium.com/@sampath.theekoder/list/100-days-of-coding-aeb4309848ee)
  - [CodeWars- JavaScript Challenges ](https://www.codewars.com/dashboard)
  - [ HackerRank - 10 Days of JavaScript ](https://www.hackerrank.com/domains/tutorials/10-days-of-javascript)

- Community and Support:
  - [ Stack Overflow ](https://stackoverflow.com/)
  - [ GitHub ](https://github.com/)
