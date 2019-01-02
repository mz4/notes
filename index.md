### React Concepts

from [freeCodeCamp](https://medium.freecodecamp.org/these-are-the-concepts-you-should-know-in-react-js-after-you-learn-the-basics-ee1d2f4b8030)
* Component Lifecycle
* HOC higher-order components
* State and setState
* Context

from [creativebloq](https://www.creativebloq.com/news/5-expert-reactjs-tips-that-you-need-to-know-today)
* Container and presentational components
* Error boundaries
* Portals
* CSS with styled-components
* Using React-specific linting
* Snapshot testing with Jest
* Code splitting
* Server rendering
* Internationalization

```markdown
fdfd
fd
fd
f
dsasa
sa
sa
s
as
as
sasa
sasa
```

### JAVASCRIPT Questions
* What are the different scopes in javascript?
* What is variable hoisting?
* What is the scope chain?
* What is an IIFE and why might you use it?
* What are function closures?
* What does the this keyword mean?
* What do the functions call, bind and apply do?
* What is the prototype chain?
* What is the difference between prototypal and classical inheritance?
* What is the Constructor OO pattern?
* What is the Prototype OO pattern?
* What is CORS? 
* What is JSONP?
* What is the difference between event capturing and bubbling?
* What is the difference between stopPropagation and preventDefault?


--------------------------------------------------------------------------
- What are the different scopes in javascript?

Global Scope, Local Scope, Block Scope (let)
Old school JavaScript
Traditionally, JavaScript really only has two types of scope :
Global Scope : Variables are known throughout the application, from the start of the application
Functional Scope : Variables are known within the function they are declared in, from the start of the function
I will not elaborate on this, since there are already many other answers explaining the difference.
Modern JavaScript
The most recent JavaScript specs now also allow a third scope :
Block Scope : Variables are known within the block they are declared in, from the moment they are declared onwards
How do I create block scope variables?
Traditionally, you create your variables like this :
var myVariable = "Some text";
Block scope variables are created like this :
let myVariable = "Some text";

--------------------------------------------------------------------------
- What is the Difference Between Function and Block Scope in JavaScript?

var is function scope.
let and const are block scope.

Function scope is within the function.
Block scope is within curly brackets.

--------------------------------------------------------------------------
- What is variable hoisting?

Hoisting is JavaScript's default behavior of moving all declarations to the top of the current scope (to the top of the current script or the current function).

- What is scope chain?
JavaScript engine will try to find the value of the variable in the executing code's block scope (your room) and when unable to find the value there, 
it will go to its lexical outer scope (your house) and if not even found there, it will go to it’s outer scope’s outer scope(your colony) until it reaches the global scope, 
let’s say in your case can be the country, which in context of JavaScript will be window, if your working in browser environment.




### GENERAL CONCEPTS
- BOM Browser Object Model
* What Is Browser Object Model (BOM)? 
* Window Object 
* Window Object Timing 
* Screen Object 
* History Object 
* Navigator Object 
* Location Object 
* Cookies 

- DOM (Document Object Model)
* What Is Document Object Model (DOM)? 
* Document Object 
* Accessing Elements & Attributes - Part 01 
* Navigating Between Elements 
* Creating Elements & Attributes 
* Changing Element Content & Attributes Values 
* Modifyig Elements Style 
* Removing Elements & Attributes 
* Document Element Animation 

- Events
* JavaScript Events 
* Adding & Removing Event Handlers 
* Event Object 
* Internet Explorer 8 Event Model 
* Cross Browser Event Handling 
* JavaScript Errors 
* Strict Mode 

### Object-oriented Programming in JavaScript
- Object
* Object Literals
* Factories
* Constructors
* Constructor Property
* Functions are Objects
* Value vs Reference Types
* Adding or Removing Properties
* Enumerating Properties
* Abstraction
* Private Properties and Methods
* Getters and Setters

- Prototypes
* Inheritance
* Prototypes and Prototypical Inheritance
* Multi-level Inheritance
* Property Descriptors
* Constructor Prototypes
* Prototype vs. Instance Members
* Iterating Instance and Prototype Members
* Avoid Extending the Built-in Objects

- Prototypical Inheritance
* Creating Your Own Prototypical Inheritance
* Resetting the Constructor
* Calling the Super Constructor
* Intermediate Function Inheritance
* Method Overriding
* Polymorphism
* When to Use Inheritance

- ES6 Classes
* ES6 Classes
* Hoisting
* Static Methods
* The This Keyword
* Private Members Using Symbols
* Private Members Using WeakMaps
* Getters and Setters
* Inheritance
* Method Riding

- ES6 Modules
* Modules
* CommonJS Modules
* ES6 Modules
* ES6 Tooling
* Babel
* Webpack

### ES6 
- Syntax
* Let & Block Scope 
* Constants with "const" 
* Hoisting in ES6 
* Arrow Functions 
* Arrow Functions and the "this" Keyword 
* Functions and Default Parameters 
* Object Literal Extensions 
* The Rest Operator 
* The Spread Operator 
* The for-of Loop 
* Template Literals 
* Destructuring - Arrays 
* Destructuring - Objects 
* Destructuring - Summary 

- Classes
Alternative Plunker Setup
Modules Setup 
Modules Basics 
Import & Export Syntax 
Modules - Strict Mode and Global Scope 
Class Basics 
Classes & Prototypes 
Inheritance 
Inheritance & Prototypes 
Static Methods 
Classes & Modules 
Getters & Setters 
Extending Built-in Objects 

- Iterators and Generators
Iterator Basics 
Iterators in Action 
Creating a Custom, Iterateable Object 
Generators Basics 
Generators in Action 
Controlling Iterators with throw and return 

- Promises
Creating & Resolving Promises 
Rejecting Promises 
Chaining Promises 
Catching Errors 
Built-in Methods - All and Race 

-Maps and Sets
Maps - Creation & Adding Items 
Maps - Managing Items 
Maps - Looping through Maps 
Maps - Wrap Up 
The WeakMap 
Sets - Creation and Adding Items 
Sets - Managing Items 
Sets - Looping through Sets 


**************************************************************************
* REACT
**************************************************************************
- LINKS
https://react.christmas/