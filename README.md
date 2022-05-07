# 1. Front-end Learning Notes 
A personal learning notes for front-end best practices including basic HTML, CSS, JS, SSAS, REACT, ES6, and JSX. Also, it is a cheat sheet for me when developing. Will update continuously...  
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
  - [5.1. CSS Pseudo-class](#51-css-pseudo-class)
  - [5.2. CSS Pseudo-element](#52-css-pseudo-element)
  - [5.3. Flexbox](#53-flexbox)
  - [5.4. Grid](#54-grid)
  - [5.5. SASS](#55-sass)
- [6. Bootstrap](#6-bootstrap)
- [7. Javascript](#7-javascript)
- [8. JQuery](#8-jquery)
- [9. React](#9-react)
  - [9.1. JSX](#91-jsx)
  - [9.2. Component](#92-component)
- [10. Redux](#10-redux)
- [11. To be continued..](#11-to-be-continued)
- [12. Reference](#12-reference)
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
Cheat sheet: visit https://htmlcheatsheet.com/
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
## 5.1. CSS Pseudo-class
* *To be continued...*
## 5.2. CSS Pseudo-element
* *To be continued...*
## 5.3. Flexbox
* *To be continued...*
## 5.4. Grid
* *To be continued...*
## 5.5. SASS
* *To be continued...*
  
**Must Have** extensions list in VS Code for CSS 
* [*HTML CSS Support*](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) - HTML id and class attribute completion
* [*CSS Peek*](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) - Allow peeking to css ID and class strings as definitions from html files to CSS
* [*Colorize*](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize) - Help visualize css colors in files
 * *To be continued...*
# 6. Bootstrap 
# 7. Javascript
# 8. JQuery
# 9. React
## 9.1. JSX
## 9.2. Component
# 10. Redux
# 11. To be continued..
# 12. Reference

| Name | Description |
| --- | --- |
| Editor | List all new or modified files |
| git diff | Show file differences that haven't been staged |