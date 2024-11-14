# JavaScript & TypeScript Revision

---

## Week 1: Basics of JavaScript

- **Topics:**
  - **HTML and CSS**
    - Basic HTML and CSS
  - **Introduction to JavaScript**
    - How does JavaScript work?
    - JS Runtime Environment
    - JS Engine
  - **JavaScript Fundamentals**
    - Basic syntax & comments
    - Declarations
    - Variable scope
    - Data structures and types
    - Literals
    - Expressions and operators
    - Loops and iteration
  - **JavaScript Concepts**
    - `window` and `this`
    - Functions
    - Popups and Popup Boxes
    - DOM Manipulation
    - JavaScript Events
    - Numbers and Dates
    - Objects

- **Week 1 Assignment:**
  - Note: CSS and JS files should be separate.
    -Create an HTML Page with JavaScript Events Handling.
    -Create an HTML page with DOM manipulation. 
    -Create a calculator with basic operations.
    
- **Learning Resources:**  
  - Source 1: [js info](https://javascript.info/)
  - Source 2: [mdn docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

---

## Week 2: Basics of JavaScript (continued)

- **Topics:**
  - Callback functions
  - Promises
  - Async/Await
  - Hoisting
  - Closures
  - Regular Expressions
  - Strict mode
  - JavaScript typed arrays
  - Debugging

- **Note:** Please use the same learning sources provided in Week 1.

- **Week 2 Assignment**
  Note: CSS and JS files should be separate.

  -Develop a gallery view for the company employees. Only 1 image should be displayed big in the center and the left and right arrows should be there for see next employee image. At the bottom user, details should be there like the name, designation, project year of experience etc... (Use objects and external JSON files for storing the data and load JSON file while the app will launch).

  -Create a login and registration and welcome for users. The first user will register and data stored in local storage. After registration, the user can log in with a valid username and password. Once successfully logged in, the user will jump to the welcome screen above the gallery view.
---

## Week 3: Advanced JavaScript & JavaScript ES5 & ES6

- **Advanced JavaScript Topics:**
  - Inheritance and prototype
  - Event Loop
  - `map`, `filter`, `reduce`
  - Scope chain, scope & lexical environment
  - Blocks in JavaScript

- **JavaScript ES5 & ES6:**
  - ES5 Features
  - ES6 Features
  - Differences between ES5 and ES6

- **Note:** Please use the same learning sources provided in Week 1.

- **Week 3 Assignment**
    Create a Task management application: This application will help users organize and manage their tasks. We'll incorporate various JavaScript concepts such as event handling, scope, lexical environment, and higher-order functions.

  -Features:
    -Display a list of tasks.
    -Add new tasks.
    -Mark tasks as completed.
    -Filter tasks (e.g., show only completed tasks).


  -JavaScript Concepts Applied:

  -Event Handling and Event Loop:
    -Use event listeners to capture user interactions (e.g., button clicks).
    -Understand how the event loop handles asynchronous tasks (e.g., fetching data).

  -Scope and Lexical Environment:
    -Implement functions with proper scoping for adding tasks and handling user interactions.
    -Manage variables in different scopes, such as within functions and event listeners.

  -Block Scope and Variables:
    -Utilize block-scoped variables for managing tasks within specific blocks of code.

  -Scope Chain:
    -Showcase the scope chain when accessing variables from different levels of the application, such as global and local scopes.

  -Higher-Order Functions (Map, Filter, Reduce):
    -Use Array.map to transform task data for display purposes.
    -Implement Array.filter to filter tasks based on completion status.
    -Utilize Array.reduce to calculate statistics, like the total number of completed tasks.


  -Additional features:
    -Implement task deletion functionality.
    -Add due dates to tasks and sort them accordingly.
    -Explore local storage for persisting tasks across sessions.
---

## Week 4: TypeScript and ES6

- **TypeScript Basics:**
  - What is TypeScript?
  - Type Basics
  - Numbers & Booleans
  - Explicit Type Assignment
  - Arrays and Types
  - Tuples
  - Enums
  - The "Any" Type
  - Understanding generated JavaScript code
  - Using Types in Functions (Arguments & Return Values)
  - Functions as Types
  - Objects and Types
  - Creating custom types with Type Aliases
  - Allowing multiple types with Union Types
  - Checking types at runtime
  - The "never" Type (TypeScript 2.0)
  - Nullable Types (TypeScript 2.0)

- **TypeScript & ES6 Compatibility:**
  - "Let" and "Const"
  - Block Scope
  - Arrow Functions and Variations
  - Default Parameters
  - Spread and Rest Operators
  - Destructuring Arrays and Objects
  - Template Literals
  - Higher Order Functions (`map`, `filter`, `reduce`, `forEach`)
  - `call`, `apply`, and `bind`
  - Memory Management
  - Event Loop
  - Other ES6 Features

- **Using Classes in TypeScript:**
  - Creating Classes and Class Properties
  - Class Methods and Access Modifiers
  - Inheritance and Constructors
  - Getters & Setters
  - Static Properties and Methods
  - Abstract Classes
  - Private Constructors & Singletons (TypeScript 2.0)
  - `read-only` Properties (TypeScript 2.0)

- **Assignment 4**
  -Quiz App:
    Users should be provided with a series of multiple-choice questions and we track their score as they progress through the quiz.

  -Features:
    -Create a pool of questions and answers (7-10 max).
    -Randomly select questions to display to the user.
    -Implement a user interface for answering questions and navigating the quiz.
    -Display the user's score and provide feedback on their performance.

  -Additional feature:
    -A timer to limit how long users have to answer each question.
    -Support for different quiz categories or difficulty levels.
    -A leaderboard to track and compare scores.
    -Integrate it with the week 2 assignment.
