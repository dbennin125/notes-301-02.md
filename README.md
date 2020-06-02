# notes-301-02.md
Reading, Research, and Discussion
In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

Name 3 advantages to Test Driven Development
1. You're able to identify errors and problems quickly

2. informs you if last change to code broke previous code.

3. You will have a reduced amout of bugs.

<h4>In what case would you need to use beforeEach() or afterEach() in a test suite?</h4>
beforeEach() - is run before EACH test in a describe
afterEach() - is run after EACH test in a describe

<h4>What is one downside of Test Driven Development</h4>-A lot of upfront time and energy which can make development feel slow.

<h4>What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?</h4>
Class defines a type which can be instantiated at runtime but prototype is an object. 

<h4>Name a use case for a static method</h4> - In a Web API, a static method is one which is defined by an interface but can be called without instantiating an object of that type first.
source: https://developer.mozilla.org/en-US/docs/Glossary/Static_method

<h4>Write an example of a Higher Order function and describe the use case it solves</h4>

addEventListener('click', () => {
  alert('Why did you click this'); 
});
it solves the issue of handling the click and other function on the page. (this one alerts you with question)

Document the following Vocabulary Terms

functional programming-process of building software by composing pure functions, avoiding shared, mutable data, etc.

pure function-function always returns the same result if same arguements are passed in. (only depends on input arguements)

higher-order function-functions that take in other functions 

immutable state-state that cannot be changed...ever

object-has properties, values, and methods

object-oriented programming (OOP)- computer programming where programmers define the data type of a data structure and types of functions that can be applied to said structure.

class-set of properties and metods that are common to all objects of one type

prototype- mechanisms by which objects inherit features from one another

super- keyword used to access and call functions on an objects parent

inheritance-object child object class will inherit features from their parents class

constructor-special method for creating and initializing an object within class

instance-object created by constructor is an instance of that constructor

context-related to objects within a function being executed

this-functions in a function and maybe different each time function called

Test Driven Development (TDD)-software development process that relies on repetition and very specific test cases(which pass).

Jest-testing library

Continuous Integration (CI)-development practice where developers put code in shared repo which is verified by automatic testing. 

unit test-checks against individual unit. Goal is to check every aspect of function to make sure it works properly. 

Sources: Google, https://devhints.io/jest, https://www.w3schools.com/, 