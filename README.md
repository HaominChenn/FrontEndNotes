# 1. Front-end Learning Notes 
A personal learning notes for front-end best practices including basic HTML, CSS, JS, SSAS, REACT, ES6, and JSX. Also, it is a cheat sheet for me when developing. Will update continuously...

**Collection of Useful Bookmarks** -> [*Go Here*](/bookmarks/bookmarks.md)

FYI: [**Why I'm learning Front-End Development?**](/myjourneyintotech/WhyILearningFrontEndDevelopment.md)

- [1. Front-end Learning Notes](#1-front-end-learning-notes)
- [2. Environment Setup](#2-environment-setup)
  - [2.1. Editor](#21-editor)
    - [2.1.1. Visual Studio Code (Highly Recommend)](#211-visual-studio-code-highly-recommend)
    - [2.1.2. Sublime Text (Recommend)](#212-sublime-text-recommend)
    - [2.1.3. WebStrom IDE (Recommend)](#213-webstrom-ide-recommend)
    - [2.1.4. CodePen(Online editor) (Recommend)](#214-codepenonline-editor-recommend)
  - [2.2. Developer Tools - Chrome DevTools](#22-developer-tools---chrome-devtools)
- [3. Intro to Web Design](#3-intro-to-web-design)
- [4. HTML5](#4-html5)
  - [4.1. Two Type of Elements](#41-two-type-of-elements)
  - [4.2. Attributes - class/id/title](#42-attributes---classidtitle)
- [5. CSS](#5-css)
  - [5.1. Flexbox](#51-flexbox)
  - [5.2. Grid](#52-grid)
  - [5.3. SASS](#53-sass)
- [6. Bootstrap](#6-bootstrap)
- [7. Javascript](#7-javascript)
  - [7.1. JavaScript Where To](#71-javascript-where-to)
  - [7.2. Output - Display data](#72-output---display-data)
  - [7.3. Syntax](#73-syntax)
  - [7.4. Variables (4 ways to declare)](#74-variables-4-ways-to-declare)
  - [7.5. Events](#75-events)
  - [7.6. Strings](#76-strings)
  - [7.7. Numbers](#77-numbers)
  - [7.8. Boolean](#78-boolean)
  - [7.9. Objects](#79-objects)
  - [7.10. Functions](#710-functions)
  - [7.11. Array](#711-array)
  - [7.12. Conditions](#712-conditions)
- [8. React](#8-react)
  - [8.1. Environment Set up](#81-environment-set-up)
  - [8.2. JSX](#82-jsx)
  - [8.3. Component](#83-component)
- [9. Redux](#9-redux)
- [10. To be continued..](#10-to-be-continued)
- [11. Reference](#11-reference)
# 2. Environment Setup
## 2.1. Editor 
### 2.1.1. Visual Studio Code (Highly Recommend)
Github repository: visit https://github.com/microsoft/vscode  
Download link: visit https://code.visualstudio.com/  
* **Free**, lightweight and open-source code editor
* Provide amazing extensions and built-in Git support
* Cross-platform support(Windows, Linux, and macOs)  
  
**Must Have** extensions list in VS Code to improve productivity:  
* [*Project Manager*](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) - Easily switch between projects
* [*Live Server*](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - Immediately see code changes reflected in the browser
* [*Prettier*](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - An opinionated code formatter   
* [*Code Spell Checker*](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - A basic spell checker that works well with camelCase code
* [*Indent-rainbow*](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) - Makes indentation easier to read  
* [*IntelliCode*](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) - AI-assisted development features for Python, TypeScript/JavaScript and Java developers   
* *To be continued...*
  
### 2.1.2. Sublime Text (Recommend)
Download link: visit https://www.sublimetext.com/
* **Not free**, but free indefinite preview
* Lightweight and fast editor
* Goto Anything allows quick file, symbol, or line navigation
* Cross-platform support(Windows, Linux, and macOs)  
### 2.1.3. WebStrom IDE (Recommend)
Download link: visit https://www.jetbrains.com/webstorm/  
* **Not free**, but smartest front-end IDE
* Most features out of the box, no need to install the extensions
* Not lightweight, a bit slower than VS Code
### 2.1.4. CodePen(Online editor) (Recommend)
Online link: visit https://codepen.io/  
* **Free**, online development environment for front end developers
*  Test and showcase HTML, CSS and JavaScript code snippets (pens)
*  Live code collaboration and presentation
## 2.2. Developer Tools - Chrome DevTools
Download link: visit https://www.google.com/intl/en_ca/chrome/  
Documentation: visit https://developer.chrome.com/docs/devtools/
* A set of web developer tools built directly into the Google Chrome browser
* Rapid debugging in the built-in console     

How to use(Two ways to open Chrome DevTools):  
1. Chrome browser –> **Chrome menu** (the three horizontal bars in the top right corner) -> **More Tools** -> **Developer Tools**  
2. Right click on any page and select **Inspect**
# 3. Intro to Web Design
The HTML-CSS-JS trio are the parts of all websites.  
How Do HTML, CSS and JavaScript Work Together? (Below is an example to understand easily) 
* HTML5 - Physical body(Bone)
* CSS - Body's accessories to make it beautiful(Cloth)
* JavaScript - enable the body to talk or move or put accessories on the body(Action)  
  All of these ‘bodily aspects’ need to work together to form a functional, visually appealing, interactive website.
# 4. HTML5
HTML is a markup language that uses a special syntax or notation to describe the structure of a webpage to the browser.  
HTML5 Cheatsheet: visit https://htmlcheatsheet.com/  
Reference Docs: visit https://www.w3schools.com/html/default.asp  
Practice link: visit https://www.freecodecamp.org/learn/responsive-web-design/  
**Must Have** extensions list in VS Code for HTML5  
* [*HTML Snippets*](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Automatically rename paired HTML/XML tag
* [*Auto Rename Tag*](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Automatically rename paired HTML/XML tag
* [*Image preview*](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview) - Shows image preview in the gutter and on hover
 * [*Path Intellisense*](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Autocompletes filenames with a path
 * *To be continued...*
  ## 4.1. Two Type of Elements
 * Inline Elements 
   * **Not** begin on new lines
   * Occupies the space as content needed (Height/Width can **not** be set in CSS)
   * Can **not** set padding/margin for top/bottom (vertically)
   * Do **not** nest block elements inside an inline element (suggestion)  
   * Common Inline Element Tags: ```<a> <span> <img> <label> <textarea> <button> <input> <br>``` etc
* Block Elements
  * Start from a new line each time
  * Occupies the entire space of the container
  * Inline/Block elements can be nested in the block elements except ```<p> <ul> <table> <h>```
  * Common Block Elements Tags: ```<div> <fieldset> <footer> <form> <h1>-<h6> <header> <hr> <li> <main> <nav> <ol> <p> <table> <ul>```
## 4.2. Attributes - class/id/title
* `class` - One class name can be shared with **multiple** HTML elements(tags). Followed by a dot, Ex: `.city`
*  `id` - A **unique** id for an HTML element, must be unique within the HTML document, can not have more than one element with the same id. Followed by a hash, EX: `#fruit`

# 5. CSS 
CSS is to style an HTML document and describes how HTML elements should be displayed.
## 5.1. Flexbox
* *To be continued...*
## 5.2. Grid
* *To be continued...*
## 5.3. SASS
* *To be continued...*
  
**Must Have** extensions list in VS Code for CSS 
* [*HTML CSS Support*](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) - HTML id and class attribute completion
* [*CSS Peek*](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) - Allow peeking to css ID and class strings as definitions from html files to CSS
* [*CSS Flexbox Cheatsheet*](https://marketplace.visualstudio.com/items?itemName=dzhavat.css-flexbox-cheatsheet) -  Lets you open a flexbox cheatsheet directly in the editor.
* [*Colorize*](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize) - Help visualize css colors in files
 * *To be continued...*
# 6. Bootstrap 
# 7. Javascript
JavaScript is one of the core technologies of the web design, along with HTML and CSS, and is supported by all modern browsers. 
## 7.1. JavaScript Where To
* Internal  - In HTML, JavaScript code is inserted between `<script>` and `</script>` tags in `<head>` or `<body>` section. 
Should place at the bottom of the `<body>` element improves the display speed.
* External(Recommend) - Place `<script src="myScript.js"></script>` in `<head>` or `<body>`
## 7.2. Output - Display data
* Writing into an HTML element, using `innerHTML`.  
  Ex: `document.getElementById("id").innerHTML = 5 + 6;`
* Writing into the HTML output using `document.write()`  
  Ex: `document.write(5 + 6);` (Used for testing)  
  ***Caution***:Using document.write() after an HTML document is loaded, will **delete** all existing HTML:
* Writing into an alert box, using `alert()`  
  Ex: `alert(5 + 6);`
* Writing into the browser console, using `console.log()`
  Ex: `console.log(5 + 6);` (Used for debugging)
## 7.3. Syntax
* All JavaScript identifiers are **case sensitive** and follow **camelCase** rule.
* Two types of values: **fixed(or literals)** and **variables**  
  Fixed include **Numbers** (3.14, 100, 1e4) and **String** ('John',"John")
## 7.4. Variables (4 ways to declare)
* Using `var` - can be Redeclare
* Using `let` - 
    * cannot be Redeclared
    * must be Declared before use
    * have Block Scope
    * can be Resignned
* Using `const`(General rule, always declare a variable with `const`) -
  *  have Block Scope
  *  cannot be Redeclared
  *  cannot be Reassigned
* Using nothing
``` 
var length = 16;                          // Number 
let points = x * 10;                      // Number 
var lastName = "Johnson";                 // String 
const cars = ["Saab", "Volvo", "BMW"];    // Array  
cars[0] = "Toyota";
const person = {firstName:"John", 
              lastName:"Doe"};            // Object 
person.firstName = "Alice";
```
## 7.5. Events
* An HTML web page has finished loading
* An HTML input field was changed
* An HTML button was clicked
```
<button onclick="this.innerHTML = Date()">The time is?</button>
<button onclick="displayDate()">The time is?</button>
```
## 7.6. Strings
```
var carName = 'Volvo';
let text = "a,b,c,d,e,f";
var character = carName[0];     //Output V
var x = "John";
var y = new String("John");
typeof x                        // return String
typeof y                        // return Object
```
**Caution**: **Don't** create String object, it will slow the performance.  

| Name | Example | Output |
| --- | --- | ---|
| length | carName.length; | 5 |
| slice(start, end) | carName.slice(2,4) | lv (end not include)|
| slice(start, end) | carName.slice(-4,-2) | ol (negative, count from the end) |
| slice(start) | carName.slice(2) | lvo (count to the end) |
| substring(start, end) | carName.substring(2,4) | lv |
| substr(start, length) | carName.substr(1, 3) | olv |
| replace("string","new String") | carName.replace("o", "t") | Vtlvo (replaces **only the first match**) |
| toUpperCase() | carName.toUpperCase() | VOLVO |
| toLowerCase() | carName.toLowerCase() | volvo |
| concat() | carName."Hello".concat(" ", "World!"); | Volvo World |
| trim() | carName.trim() | Volvo |
| charAt() | carName.charAt(2); | l |
| split() | text.split(",")[0] | a(A string can be converted to an array) |
| indexOf() | carName.indexOf("o") | 1（first occurrence）|
| lastIndexOf() | carName.lastIndexOf("o") | 4（last occurrence） |
| search() | carName.search("o") | 1 |
| match(regexp)) | carName.match(/o/gi) | o,o |
| includes(searchvalue, start) | carName.includes("f", 0) | false |
| startsWith() | carName.startsWith("V") | true |
| endsWith() | carName.endsWith("e") | false |

**Tips**: convert any data to string using "+"
```
var numVal=2;
var boolVal=false;
var nullVal=null;
var undefinedVal=undefined;

var numValPlus=numVal+"";            //2 string
var boolValPlus=boolVal+"";          //false string
var nullPlus=nullVal+"";             //null string
var undefinedPlus=undefinedVal+"";   //undefined string
console.log([1,2,3,4]+"");           //1,2,3,4 string
```
## 7.7. Numbers
```
let number = 5;  
var testNull= null;  
var evalVal = "1 + 2";
```
| Name | Example | Output |
| --- | --- | ---|
| Number() | Number(true); Number(" 11"); Number(null); Number(undefined)| 0 11 0 NaN//number |
| parseInt() | parseInt("120abc"); | 120 //number |
| valueOf() | value("123"); | 123 //number |
| Number() | Number(true); Number(" 10"); | 0 10 //number |
| toString() | number.toString(); | 5 //string |
| String() | String(testNull); | null //string(null/undefined must use String()) |
| Eval() | eval(evalVal); | 3 //number |  
  
* NaN - Not a Number
  * isNaN - false(can convert to number), true(can not covert number)
  * console.log(NaN == NaN)  //false

## 7.8. Boolean
* True - everything with a value
   * Boolean(Object); 
* False - no value  
   * Boolean(0); 
   * Boolean(-0);
   * Boolean(NaN);
   * Boolean("");
   * Boolean(undefined);
   * Boolean(false);
   * Boolean(null);  
  
**Caution**: Comparing two JavaScript objects always return **false**.
## 7.9. Objects
```
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
``` 
* Definition - a collection of named values, mutable
* Declare - `const o = {}` or `const o = new Object()` or const o ={name:"a",age:2} (recommend))
* Accessing Object Properties:    
   * `objectName.property` Ex: `person.age`
   * `objectName["property"]` Ex: `person["age"]`
   * `objectName.methodName()` - Ex: `person.fullName()`
   * add new property - `objectName.newProperty` Ex: `person.gender`
   * delete property - `delete objectName.property` Ex: `delete person.age`
* Print Object(covert Object to string) 
   * loop an object - `for(let v in object){}` Ex: `for(let v in person){ txt +=person(v)}` 
   * Use `Object.values()` Ex:`Object.values(person)`
   * Use `JSON.stringify()` Ex: `JSON.stringify(person)`
* Constructor
```
function Person(first, last, age, eyecolor) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.name = function() {
    return this.firstName + " " + this.lastName;
  };
}
```
  Use **prototype** Add new property to object constructors - `Person.prototype.nationality = "English";`  
* Methods  
   * `hasOwnProperty(prop)` - check if the object has that prop
   * `isPrototypeOf(o)` - check if the object inherit from o
   * `propertyIsEnumerable(prop)` - check the prop can use for-in to loop
   * `call()` - invoke a method with an owner object as an argument 
   * `apply()` - similar to call() but takes arguments as an array
   * `bind()` - borrow a method from another object
## 7.10. Functions
```
function myFunction(parameter1,parameter2) {
    if (parameter1>parameter2)
    {
        return;
    }
    return parameter1 * parameter2;
}
document.getElementById("demo").innerHTML=myFunction(4,3);
//Arrow Functions using ES6
const multiplier = (item, multi) => item * multi;
const multiplier = (item, multi) => {return item * multi;}
multiplier(4, 2); //8
```
## 7.11. Array
const arr = [ 1,2,3 ];
* `push()` - append data to the end of an array Ex: `arr.push(4)` //1,2,3,4
* `pop()` - remove the last element from an array Ex: `arr.pop()` //1,2
* `shift()` - remove the first element from an array Ex: `arr.shift()`  //2,3 
* `unshift()` - add the element at the beginning of the array Ex `arr.unshift(0)` //0,1,2,3
* 
## 7.12. Conditions
* If Else
```
 if (condition1)
{    code
}else if (condition2)
{    code
}else
{  code
}
```
* Switch
```
switch(n) {
    case 1:
        code
        break;
    case 2:
        code
        break;
    default:
        not in case 1 and 2 code
}
```
* Loop
* While
  

# 8. React
React is an Open Source view library created and maintained by Facebook. It's a great tool to render the User Interface (UI) of modern web applications.
## 8.1. Environment Set up
* **Must Have** extensions list in VS Code to improve productivity  
  * [*ES7+ React/Redux/React-Native snippets*](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) - JavaScript and React/Redux snippets in ES7+ with Babel plugin features for VS Code  
  * 
* Create React in VS code(recommend)
  1. Install node.js
  2. Open VS code and and select an folder to store the new app
  3. In the terminal, enter `npm install -g create-react-app`(only first time use react)  
  4. Then, enter command `npx create-react-app [app-name]` (`npx create-react-app ./`)
  5. Run the app using `npm start`
* Add React to an HTML page(not recommend)
```
<!DOCTYPE html>
<html lang="en">
<title>Test React</title>

<!-- Load React API -->
<script src= "https://unpkg.com/react@16/umd/react.production.min.js"></script>
<!-- Load React DOM-->
<script src= "https://unpkg.com/react-dom@16/umd/react-dom.production.min.js"></script>
<!-- Load Babel Compiler -->
<script src="https://unpkg.com/babel-standalone@6.15.0/babel.min.js"></script>

<body>

<div id="mydiv"></div>

<script type="text/babel">
    //  JSX Babel code goes here
     function Hello() {
        return <h1>Hello World!</h1>;
      }

      ReactDOM.render(<Hello />, document.getElementById('mydiv'))
</script>

</body>
</html>
```

## 8.2. JSX
JSX is a syntax extension of JavaScript that allows you to write HTML directly within JavaScript. 
```
// create a JSX element
<script>
const JSX = (
  <div className='myDiv'>
    <h1>Hello, world!</h1>;
    {/* This is a comment */}
    <p>This is a new element.</p>
  </div>
  );

// Render JSX to HTML, using
// ReactDOM.render(componentToRender, targetNode);
ReactDOM.render(
    JSX,
    document.getElementById('example')
);  
</script>
```
JSX Rules:
* Nested JSX is that it must return a single element. Use `<div>` to wrap
* JSX uses **className** keyword to define an HTML class
* JSX use **htmlFor** keyword to define a label
## 8.3. Component
Two ways to create a React component  
* Using a JavaScript function - It creates a **stateless** functional component and receive data then render it, but not track changes.
```
// using JS Function
const DemoComponent = function HelloMessage(props) {
    return <div className='customClass' />;
}

//using ES6 class syntax
class Welcome extends React.Component {
   constructor(props) {
    super(props);
    this.state = {date: new Date()}
  }
  render() {
    return (
      <div>
      <h1>Hello World!</h1>;
        {/* use {} to insert js code*/}
      <h2>{this.state.date.toLocaleTimeString()}</h2>
      </div>
  }
}
ReactDOM.render(<Welcome />, document.getElementById("welcome"));

//a customize component
function HelloMessage(props) {
    return <h1>Hello {props.name}!</h1>;
}
 
const element = <HelloMessage name="abc"/>;
 
ReactDOM.render(
    element,
    document.getElementById('example')
);

//a composition(nested) component
function Navbar(props) {
    return <h1>website：{props.name}</h1>;
}
function Footer(props) {
    return <h1>Copyright：{props.url}</h1>;
}
function App() {
    return (
    <div>
        <Navbar name="myWebsite" />
        <Footer url="http://www.mywebsite.com" />
    </div>
    );
}
 
ReactDOM.render(
     <App />,
    document.getElementById('example')
);

//use join(", ") to pass an array as props
```
* 
Notice: Every React component can be self-closing: `<div />`  
Component name much start with capital letter.

# 9. Redux
# 10. To be continued..
# 11. Reference

