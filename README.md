
<h1 align="center" id="top">Complete JavaScript Notes</h1>

## Table of Contents

1. [Introduction to JavaScript](#1-introduction-to-javascript)
   1. [What is JavaScript?](#what-is-javascript)
   2. [Why Do We Use JavaScript?](#why-do-we-use-javascript)
   3. [JavaScript History](#javascript-history)
   4. [How Does JavaScript Work?](#how-does-javascript-work)
   5. [JavaScript Features](#javascript-features)

2. [Setting Up JavaScript](#2-setting-up-javascript)
   1. [Installing VS Code](#installing-vs-code)
   2. [Creating a JavaScript File](#creating-a-javascript-file)
   3. [Connecting JavaScript with HTML](#connecting-javascript-with-html)
   4. [Internal JavaScript](#internal-javascript)
   5. [External JavaScript](#external-javascript)
   6. [Script Tag Attributes](#script-tag-attributes)
   7. [Running JavaScript in Browser](#running-javascript-in-browser)

3. [JavaScript Syntax and Comments](#3-javascript-syntax-and-comments)
   1. [JavaScript Syntax](#javascript-syntax)
   2. [Statements](#statements)
   3. [Semicolons](#semicolons)
   4. [Whitespace](#whitespace)
   5. [Case Sensitivity](#case-sensitivity)
   6. [JavaScript Comments](#javascript-comments)
   7. [Strict Mode](#strict-mode)

4. [Variables and Constants](#4-variables-and-constants)
   1. [What are Variables?](#what-are-variables)
   2. [var Keyword](#var-keyword)
   3. [let Keyword](#let-keyword)
   4. [const Keyword](#const-keyword)
   5. [Variable Naming Rules](#variable-naming-rules)
   6. [Declaration and Initialization](#declaration-and-initialization)
   7. [Reassignment](#reassignment)
   8. [Scope of Variables](#scope-of-variables)
   9. [Difference Between var, let and const](#difference-between-var-let-and-const)

5. [JavaScript Data Types](#5-javascript-data-types)
   1. [What are Data Types?](#what-are-data-types)
   2. [Primitive Data Types](#primitive-data-types)
   3. [String](#string)
   4. [Number](#number)
   5. [Boolean](#boolean)
   6. [Undefined](#undefined)
   7. [Null](#null)
   8. [BigInt](#bigint)
   9. [Symbol](#symbol)
   10. [Non-Primitive Data Types](#non-primitive-data-types)
   11. [typeof Operator](#typeof-operator)
   12. [Dynamic Typing](#dynamic-typing)

6. [JavaScript Operators](#6-javascript-operators)
   1. [What are Operators?](#what-are-operators)
   2. [Arithmetic Operators](#arithmetic-operators)
   3. [Assignment Operators](#assignment-operators)
   4. [Comparison Operators](#comparison-operators)
   5. [Logical Operators](#logical-operators)
   6. [Increment and Decrement](#increment-and-decrement)
   7. [String Operators](#string-operators)
   8. [Ternary Operator](#ternary-operator)
   9. [Nullish Coalescing Operator](#nullish-coalescing-operator)
   10. [Optional Chaining Operator](#optional-chaining-operator)
   11. [Operator Precedence](#operator-precedence)

7. [JavaScript Type Conversion](#7-javascript-type-conversion)
   1. [What is Type Conversion?](#what-is-type-conversion)
   2. [String Conversion](#string-conversion)
   3. [Number Conversion](#number-conversion)
   4. [Boolean Conversion](#boolean-conversion)
   5. [Implicit Conversion](#implicit-conversion)
   6. [Explicit Conversion](#explicit-conversion)
   7. [parseInt() Method](#parseint-method)
   8. [parseFloat() Method](#parsefloat-method)
   9. [NaN](#nan)

8. [JavaScript Input and Output](#8-javascript-input-and-output)
   1. [console.log()](#consolelog)
   2. [console.error()](#consoleerror)
   3. [console.warn()](#consolewarn)
   4. [console.table()](#consoletable)
   5. [alert()](#alert)
   6. [prompt()](#prompt)
   7. [confirm()](#confirm)
   8. [document.write()](#documentwrite)

9. [JavaScript Strings](#9-javascript-strings)
   1. [Creating Strings](#creating-strings)
   2. [String Length](#string-length)
   3. [String Indexing](#string-indexing)
   4. [charAt()](#charat)
   5. [at()](#at)
   6. [toUpperCase()](#touppercase)
   7. [toLowerCase()](#tolowercase)
   8. [trim()](#trim)
   9. [includes()](#includes)
   10. [startsWith() and endsWith()](#startswith-and-endswith)
   11. [indexOf() and lastIndexOf()](#indexof-and-lastindexof)
   12. [slice()](#slice)
   13. [substring()](#substring)
   14. [replace() and replaceAll()](#replace-and-replaceall)
   15. [split()](#split)
   16. [repeat()](#repeat)
   17. [Template Literals](#template-literals)

10. [JavaScript Numbers and Math](#10-javascript-numbers-and-math)
    1. [Number Basics](#number-basics)
    2. [Number Methods](#number-methods)
    3. [toFixed()](#tofixed)
    4. [toString()](#tostring)
    5. [Number.isInteger()](#numberisinteger)
    6. [Number.isNaN()](#numberisnan)
    7. [Math Object](#math-object)
    8. [Math.round()](#mathround)
    9. [Math.floor() and Math.ceil()](#mathfloor-and-mathceil)
    10. [Math.random()](#mathrandom)
    11. [Math.max() and Math.min()](#mathmax-and-mathmin)
    12. [Math.abs() and Math.sqrt()](#mathabs-and-mathsqrt)
    13. [Math.pow() and Math.trunc()](#mathpow-and-mathtrunc)

11. [Conditional Statements](#11-conditional-statements)
    1. [What are Conditions?](#what-are-conditions)
    2. [if Statement](#if-statement)
    3. [if-else Statement](#if-else-statement)
    4. [else-if Ladder](#else-if-ladder)
    5. [Nested if Statement](#nested-if-statement)
    6. [switch Statement](#switch-statement)
    7. [Ternary Operator](#ternary-operator-in-conditions)
    8. [Truthy and Falsy Values](#truthy-and-falsy-values)

12. [JavaScript Loops](#12-javascript-loops)
    1. [What are Loops?](#what-are-loops)
    2. [for Loop](#for-loop)
    3. [while Loop](#while-loop)
    4. [do-while Loop](#do-while-loop)
    5. [for...of Loop](#forof-loop)
    6. [for...in Loop](#forin-loop)
    7. [Nested Loops](#nested-loops)
    8. [break Statement](#break-statement)
    9. [continue Statement](#continue-statement)

13. [JavaScript Functions](#13-javascript-functions)
    1. [What are Functions?](#what-are-functions)
    2. [Function Declaration](#function-declaration)
    3. [Function Calling](#function-calling)
    4. [Parameters and Arguments](#parameters-and-arguments)
    5. [Return Statement](#return-statement)
    6. [Default Parameters](#default-parameters)
    7. [Function Expression](#function-expression)
    8. [Arrow Functions](#arrow-functions)
    9. [Anonymous Functions](#anonymous-functions)
    10. [Callback Functions](#callback-functions)
    11. [Scope and Functions](#scope-and-functions)
    12. [Recursion](#recursion)

14. [JavaScript Arrays](#14-javascript-arrays)
    1. [What are Arrays?](#what-are-arrays)
    2. [Creating Arrays](#creating-arrays)
    3. [Accessing Array Elements](#accessing-array-elements)
    4. [Changing Array Elements](#changing-array-elements)
    5. [Array Length](#array-length)
    6. [push() and pop()](#push-and-pop)
    7. [shift() and unshift()](#shift-and-unshift)
    8. [indexOf() and includes()](#array-indexof-and-includes)
    9. [slice() and splice()](#slice-and-splice)
    10. [concat()](#concat)
    11. [join()](#join)
    12. [reverse() and sort()](#reverse-and-sort)
    13. [forEach()](#foreach)
    14. [map()](#map)
    15. [filter()](#filter)
    16. [find() and findIndex()](#find-and-findindex)
    17. [reduce()](#reduce)
    18. [some() and every()](#some-and-every)
    19. [Array Destructuring](#array-destructuring)

15. [JavaScript Objects](#15-javascript-objects)
    1. [What are Objects?](#what-are-objects)
    2. [Creating Objects](#creating-objects)
    3. [Object Properties](#object-properties)
    4. [Accessing Object Properties](#accessing-object-properties)
    5. [Adding and Updating Properties](#adding-and-updating-properties)
    6. [Deleting Properties](#deleting-properties)
    7. [Object Methods](#object-methods)
    8. [this Keyword](#this-keyword)
    9. [Object.keys()](#objectkeys)
    10. [Object.values()](#objectvalues)
    11. [Object.entries()](#objectentries)
    12. [Object Destructuring](#object-destructuring)
    13. [Spread Operator](#spread-operator)
    14. [Optional Chaining](#optional-chaining)

16. [DOM Manipulation](#16-dom-manipulation)
17. [JavaScript Events](#17-javascript-events)
18. [Advanced Functions and Scope](#18-advanced-functions-and-scope)
19. [ES6+ Features](#19-es6-features)
20. [JavaScript Date and Time](#20-javascript-date-and-time)
21. [JavaScript Error Handling](#21-javascript-error-handling)
22. [JavaScript JSON](#22-javascript-json)
23. [JavaScript Asynchronous Programming](#23-javascript-asynchronous-programming)
24. [Promises and Async/Await](#24-promises-and-asyncawait)
25. [JavaScript Browser APIs](#25-javascript-browser-apis)
26. [JavaScript Modules](#26-javascript-modules)
27. [JavaScript Storage](#27-javascript-storage)
28. [JavaScript Best Practices](#28-javascript-best-practices)
29. [JavaScript Practical Projects](#29-javascript-practical-projects)
30. [Quick Revision, Practice and Resources](#30-quick-revision-practice-and-resources)

---

# 1. Introduction to JavaScript

<a id="what-is-javascript"></a>

## What is JavaScript?

JavaScript ek high-level programming language hai jiska use websites ko interactive aur dynamic banane ke liye hota hai.

HTML webpage ka structure create karta hai, CSS webpage ko design karta hai aur JavaScript webpage mein functionality add karta hai.

JavaScript ki help se hum button click, form validation, image slider, dropdown menu, calculator aur bahut saare interactive features create kar sakte hain.

**Example:**

```javascript
console.log("Hello World!");
```

**Explanation:**

- `console` browser ke developer tools ka console object hai.
- `log()` console par information display karne ka method hai.
- `"Hello World!"` ek string value hai.

**Output:**

```text
Hello World!
```

**Output:**

[Add your browser console output screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="why-do-we-use-javascript"></a>

## Why Do We Use JavaScript?

JavaScript ka use website aur applications mein functionality add karne ke liye hota hai.

- Button click par action perform karna.
- Form validation karna.
- Dropdown menu create karna.
- Image slider banana.
- Calculator create karna.
- Dynamic content display karna.
- API se data receive karna.
- Web applications develop karna.
- Backend development karna.

<a id="javascript-history"></a>

## JavaScript History

JavaScript ko Brendan Eich ne 1995 mein develop kiya tha.

| Year | Development |
|---|---|
| 1995 | JavaScript developed |
| 1996 | JavaScript ko ECMAScript standardization ke liye submit kiya gaya |
| 1997 | ECMAScript 1 release hua |
| 2009 | ECMAScript 5 release hua |
| 2015 | ECMAScript 2015 (ES6) release hua |
| 2016 onwards | ECMAScript ke regular yearly updates |

**Important:** JavaScript language ka standard ECMAScript ke naam se jaana jaata hai.

<a id="how-does-javascript-work"></a>

## How Does JavaScript Work?

JavaScript browser ke JavaScript engine ke through execute hoti hai.

1. Developer JavaScript code likhta hai.
2. Browser JavaScript file load karta hai.
3. JavaScript engine code ko process karta hai.
4. Instructions execute hoti hain.
5. Result browser mein display ho sakta hai.

**Examples of JavaScript Engines:**

- V8 — Google Chrome aur Node.js.
- SpiderMonkey — Firefox.
- JavaScriptCore — Safari.

<a id="javascript-features"></a>

## JavaScript Features

| Feature | Description |
|---|---|
| High-level | Developer-friendly language |
| Dynamic | Variable ka type runtime par change ho sakta hai |
| Interpreted/JIT | Modern engines code ko efficiently execute karte hain |
| Single-threaded execution | JavaScript code generally ek main thread par execute hota hai |
| Event-driven | Events ke according actions perform kar sakti hai |
| Object-based | Objects aur prototypes support karti hai |
| Cross-platform | Different platforms par run ho sakti hai |

---

# 2. Setting Up JavaScript

<a id="installing-vs-code"></a>

## Installing VS Code

Visual Studio Code ek code editor hai jisme HTML, CSS aur JavaScript likh sakte hain.

JavaScript run karne ke liye VS Code compulsory nahi hai. Browser ke console mein bhi JavaScript execute kar sakte hain.

<a id="creating-a-javascript-file"></a>

## Creating a JavaScript File

JavaScript file create karne ke liye `.js` extension use kiya jaata hai.

**Example Folder Structure:**

```text
javascript-project/
│
├── index.html
│
├── style.css
│
└── script.js
```

- `index.html` — HTML structure.
- `style.css` — CSS styling.
- `script.js` — JavaScript code.

<a id="connecting-javascript-with-html"></a>

## Connecting JavaScript with HTML

JavaScript ko HTML document ke saath connect karne ke liye `<script>` tag use hota hai.

**Example:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>JavaScript Connection</title>
</head>
<body>

    <h1>Learning JavaScript</h1>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
console.log("JavaScript Connected Successfully!");
```

**Output:**

```text
JavaScript Connected Successfully!
```

**Output Screenshot:**

[Add your browser console output screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="internal-javascript"></a>

## Internal JavaScript

Jab JavaScript code directly HTML file ke andar `<script>` tag mein likha jaata hai, use Internal JavaScript kehte hain.

**Example:**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Internal JavaScript</title>
</head>
<body>

    <h1>My Website</h1>

    <script>
        console.log("Hello from Internal JavaScript!");
    </script>

</body>
</html>
```

**Output:**

```text
Hello from Internal JavaScript!
```

<a id="external-javascript"></a>

## External JavaScript

Jab JavaScript code separate `.js` file mein likha jaata hai aur HTML se connect kiya jaata hai, use External JavaScript kehte hain.

**index.html**

```html
<!DOCTYPE html>
<html>
<head>
    <title>External JavaScript</title>
</head>
<body>

    <h1>External JavaScript</h1>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
console.log("External JavaScript Connected!");
```

**Advantages:**

- HTML aur JavaScript separate rehte hain.
- Code manage karna easy hota hai.
- Same JavaScript file multiple HTML pages mein use kar sakte hain.

<a id="script-tag-attributes"></a>

## Script Tag Attributes

`<script>` tag mein JavaScript loading aur execution control karne ke liye kuch important attributes use hote hain.

| Attribute | Purpose |
|---|---|
| src | External JavaScript file ka path |
| defer | HTML parsing complete hone ke baad script execute karta hai |
| async | Script download hote hi execute ho sakta hai |
| type | Script ka type define karta hai |
| nomodule | Module-supporting browsers mein script skip karta hai |

**defer Example:**

```html
<script src="script.js" defer></script>
```

**async Example:**

```html
<script src="analytics.js" async></script>
```

**Important:**

- `defer` scripts document order mein execute hote hain.
- `async` scripts download complete hone par execute hote hain; order guaranteed nahi hota.
- Normal classic script ko `</body>` se pehle rakhna bhi ek common approach hai.

<a id="running-javascript-in-browser"></a>

## Running JavaScript in Browser

JavaScript ko browser mein run karne ke liye:

1. Browser open karo.
2. Kisi webpage par right-click karo.
3. Inspect select karo.
4. Console tab open karo.
5. JavaScript code type karo.
6. Enter press karo.

**Example:**

```javascript
console.log("Hello JavaScript");
```

**Output:**

```text
Hello JavaScript
```

**Output Screenshot:**

[Add your browser developer console screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

---

# 3. JavaScript Syntax and Comments

<a id="javascript-syntax"></a>

## JavaScript Syntax

JavaScript syntax ka matlab hai code likhne ke rules aur structure.

**Example:**

```javascript
let name = "Sumit";

console.log(name);
```

Explanation:

- `let` — Variable declare karne ka keyword.
- `name` — Variable ka naam.
- `=` — Assignment operator.
- `"Sumit"` — String value.
- `console.log()` — Output display karne ka method.

**Output:**

```text
Sumit
```

<a id="statements"></a>

## Statements

JavaScript statement ek instruction hota hai jo browser ya JavaScript engine execute karta hai.

**Example:**

```javascript
let age = 19;

let city = "Delhi";

console.log(age);

console.log(city);
```

Yahan har line ek JavaScript statement hai.

**Output:**

```text
19
Delhi
```

<a id="semicolons"></a>

## Semicolons

Semicolon (`;`) JavaScript statement ke end ko mark karne ke liye use hota hai.

**Example:**

```javascript
let a = 10;

let b = 20;

console.log(a + b);
```

JavaScript mein semicolon kai situations mein optional hota hai, lekin consistency ke liye use karna achhi practice hai.

<a id="whitespace"></a>

## Whitespace

Whitespace ka matlab spaces, tabs aur line breaks hota hai.

JavaScript generally extra whitespace ko ignore karta hai.

**Example:**

```javascript
let name = "Sumit";

console.log(name);
```

Is code ko multiple lines ya spaces ke saath likhne par bhi iska result same rahega.

<a id="case-sensitivity"></a>

## Case Sensitivity

JavaScript case-sensitive language hai.

Iska matlab uppercase aur lowercase letters ko alag maana jaata hai.

**Example:**

```javascript
let name = "Sumit";

let Name = "Rahul";

console.log(name);

console.log(Name);
```

**Output:**

```text
Sumit
Rahul
```

`name` aur `Name` do different variables hain.

<a id="javascript-comments"></a>

## JavaScript Comments

Comments ka use code mein notes aur explanations likhne ke liye hota hai.

Comments execute nahi hote.

**1. Single-Line Comment**

Single-line comment ke liye `//` use hota hai.

```javascript
// This is a single-line comment

console.log("Hello World");
```

**2. Multi-Line Comment**

Multi-line comment ke liye `/* */` use hota hai.

```javascript
/*
This is a multi-line comment.
We can write multiple lines here.
*/

console.log("Learning JavaScript");
```

**Output:**

```text
Hello World
Learning JavaScript
```

<a id="strict-mode"></a>

## Strict Mode

Strict Mode JavaScript ke kuch unsafe ya error-prone behaviours ko restrict karta hai.

Strict Mode activate karne ke liye `"use strict"` likhte hain.

```javascript
"use strict";

let name = "Sumit";

console.log(name);
```

Strict Mode mein undeclared variables create karne par error aata hai.

```javascript
"use strict";

age = 19;
```

**Output:**

```text
ReferenceError
```

**Important:** Strict Mode ko function ke andar bhi activate kiya ja sakta hai.

---

# 4. Variables and Constants

<a id="what-are-variables"></a>

## What are Variables?

Variable ek named storage location ki tarah hota hai jisme data store kiya ja sakta hai.

JavaScript mein variables declare karne ke liye `var`, `let` aur `const` keywords use hote hain.

**Example:**

```javascript
let name = "Sumit";

let age = 19;

console.log(name);

console.log(age);
```

**Output:**

```text
Sumit
19
```

<a id="var-keyword"></a>

## var Keyword

`var` JavaScript mein variable declare karne ka older keyword hai.

Ismein variable ko dobara declare aur reassign kar sakte hain.

```javascript
var name = "Sumit";

var name = "Rahul";

name = "Aman";

console.log(name);
```

**Output:**

```text
Aman
```

`var` function-scoped hota hai aur block scope follow nahi karta.

<a id="let-keyword"></a>

## let Keyword

`let` se declare kiya gaya variable reassign ho sakta hai, lekin same scope mein dobara declare nahi kar sakte.

```javascript
let age = 19;

age = 20;

console.log(age);
```

**Output:**

```text
20
```

<a id="const-keyword"></a>

## const Keyword

`const` ka use constant binding declare karne ke liye hota hai.

Ismein variable ko dobara assign nahi kar sakte.

```javascript
const country = "India";

console.log(country);
```

**Output:**

```text
India
```

Reassignment karne par error aayega.

```javascript
const age = 19;

age = 20;
```

**Output:**

```text
TypeError
```

<a id="variable-naming-rules"></a>

## Variable Naming Rules

JavaScript variables ke naam rakhne ke kuch rules hote hain.

**Rules:**

1. Variable name letter, underscore (`_`) ya dollar sign (`$`) se start ho sakta hai.
2. Variable name number se start nahi ho sakta.
3. Spaces allowed nahi hote.
4. JavaScript keywords ko variable name nahi bana sakte.
5. Variable names case-sensitive hote hain.

**Valid Names:**

```javascript
let name = "Sumit";

let userAge = 19;

let _price = 500;

let $amount = 1000;
```

**Invalid Names:**

```javascript
// let 1name = "Sumit";

// let user name = "Sumit";

// let let = 100;
```

**Naming Convention:**

JavaScript mein camelCase commonly use hota hai.

```javascript
let firstName = "Sumit";

let totalPrice = 500;

let userEmailAddress = "user@example.com";
```

<a id="declaration-and-initialization"></a>

## Declaration and Initialization

**Declaration:** Variable create karna.

**Initialization:** Variable ko first value assign karna.

```javascript
let age;

age = 19;

console.log(age);
```

**Output:**

```text
19
```

<a id="reassignment"></a>

## Reassignment

Variable ki existing value ko change karna reassignment kehlata hai.

```javascript
let price = 500;

price = 800;

console.log(price);
```

**Output:**

```text
800
```

<a id="scope-of-variables"></a>

## Scope of Variables

Scope decide karta hai ki variable code ke kis part mein accessible hoga.

JavaScript mein important scopes:

1. Global Scope
2. Function Scope
3. Block Scope

**Global Scope:**

```javascript
let name = "Sumit";

function showName() {
    console.log(name);
}

showName();
```

**Output:**

```text
Sumit
```

**Function Scope:**

```javascript
function showAge() {
    let age = 19;

    console.log(age);
}

showAge();
```

**Output:**

```text
19
```

**Block Scope:**

```javascript
{
    let city = "Delhi";

    console.log(city);
}
```

**Output:**

```text
Delhi
```

<a id="difference-between-var-let-and-const"></a>

## Difference Between var, let and const

| Feature | var | let | const |
|---|---|---|---|
| Reassignment | Yes | Yes | No |
| Redeclaration in same scope | Yes | No | No |
| Scope | Function | Block | Block |
| Hoisting | Yes, initialized as undefined | Yes, but TDZ | Yes, but TDZ |
| Initialization required at declaration | No | No | Yes |

**Best Practice:**

- Default `const` use karo.
- Jab value change karni ho tab `let` use karo.
- Modern JavaScript mein generally `var` avoid karo.

---

# 5. JavaScript Data Types

<a id="what-are-data-types"></a>

## What are Data Types?

Data Type batata hai ki variable mein kis type ka data store hai.

JavaScript mein data types do broad categories mein divide hote hain:

1. Primitive Data Types
2. Non-Primitive Data Types

<a id="primitive-data-types"></a>

## Primitive Data Types

JavaScript ke seven primitive data types hain.

| Data Type | Description |
|---|---|
| String | Text data |
| Number | Numeric values |
| Boolean | true or false |
| Undefined | Value assign nahi hui |
| Null | Intentionally empty value |
| BigInt | Large integer values |
| Symbol | Unique identifiers |

<a id="string"></a>

## String

String ka use text store karne ke liye hota hai.

String ko single quotes, double quotes ya backticks mein likh sakte hain.

```javascript
let firstName = "Sumit";

let city = 'Delhi';

let message = `Hello World`;

console.log(firstName);

console.log(city);

console.log(message);
```

**Output:**

```text
Sumit
Delhi
Hello World
```

<a id="number"></a>

## Number

Number data type integers aur decimal values dono ko represent karta hai.

```javascript
let age = 19;

let price = 499.99;

console.log(age);

console.log(price);
```

**Output:**

```text
19
499.99
```

<a id="boolean"></a>

## Boolean

Boolean data type mein sirf do values hoti hain:

- `true`
- `false`

```javascript
let isStudent = true;

let isLoggedIn = false;

console.log(isStudent);

console.log(isLoggedIn);
```

**Output:**

```text
true
false
```

<a id="undefined"></a>

## Undefined

Jab variable declare kiya jaata hai lekin usko value assign nahi hoti, toh uski value `undefined` hoti hai.

```javascript
let age;

console.log(age);
```

**Output:**

```text
undefined
```

<a id="null"></a>

## Null

`null` ka use intentionally empty ya absent value represent karne ke liye hota hai.

```javascript
let selectedUser = null;

console.log(selectedUser);
```

**Output:**

```text
null
```

**Important:** `typeof null` ka result `"object"` aata hai. Yeh JavaScript ka historical behaviour hai.

<a id="bigint"></a>

## BigInt

BigInt ka use bahut bade integers ko represent karne ke liye hota hai.

Number ki safe integer limit se bade integer ke liye BigInt useful hai.

```javascript
let bigNumber = 12345678901234567890n;

console.log(bigNumber);
```

**Output:**

```text
12345678901234567890n
```

<a id="symbol"></a>

## Symbol

Symbol ek unique primitive value create karta hai.

```javascript
let id1 = Symbol("id");

let id2 = Symbol("id");

console.log(id1 === id2);
```

**Output:**

```text
false
```

<a id="non-primitive-data-types"></a>

## Non-Primitive Data Types

Non-primitive values mein objects aur unke related structures aate hain.

Common examples:

- Object
- Array
- Function
- Date

**Example:**

```javascript
let student = {
    name: "Sumit",
    age: 19
};

let skills = ["HTML", "CSS", "JavaScript"];

console.log(student);

console.log(skills);
```

**Output:**

```text
{ name: "Sumit", age: 19 }

["HTML", "CSS", "JavaScript"]
```

<a id="typeof-operator"></a>

## typeof Operator

`typeof` operator kisi value ka type check karne ke liye use hota hai.

**Example:**

```javascript
let name = "Sumit";

let age = 19;

let isStudent = true;

console.log(typeof name);

console.log(typeof age);

console.log(typeof isStudent);
```

**Output:**

```text
string
number
boolean
```

<a id="dynamic-typing"></a>

## Dynamic Typing

JavaScript dynamically typed language hai.

Iska matlab variable mein alag-alag time par different data types ki values store ho sakti hain.

```javascript
let value = 100;

console.log(typeof value);

value = "Hello";

console.log(typeof value);

value = true;

console.log(typeof value);
```

**Output:**

```text
number
string
boolean
```

---

# 6. JavaScript Operators

<a id="what-are-operators"></a>

## What are Operators?

Operators special symbols ya keywords hote hain jo values aur variables par operations perform karte hain.

Example:

```javascript
let a = 10;

let b = 5;

console.log(a + b);
```

**Output:**

```text
15
```

<a id="arithmetic-operators"></a>

## Arithmetic Operators

Arithmetic operators mathematical calculations perform karte hain.

| Operator | Name | Example | Result |
|---|---|---|---|
| + | Addition | 10 + 5 | 15 |
| - | Subtraction | 10 - 5 | 5 |
| * | Multiplication | 10 * 5 | 50 |
| / | Division | 10 / 5 | 2 |
| % | Modulus | 10 % 3 | 1 |
| ** | Exponentiation | 2 ** 3 | 8 |

**Example:**

```javascript
let a = 10;

let b = 3;

console.log(a + b);

console.log(a - b);

console.log(a * b);

console.log(a / b);

console.log(a % b);

console.log(a ** b);
```

**Output:**

```text
13
7
30
3.3333333333333335
1
1000
```

**Output Screenshot:**

[Add your browser console output screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="assignment-operators"></a>

## Assignment Operators

Assignment operators variables ko values assign ya update karne ke liye use hote hain.

| Operator | Example | Equivalent |
|---|---|---|
| = | x = 10 | x = 10 |
| += | x += 5 | x = x + 5 |
| -= | x -= 5 | x = x - 5 |
| *= | x *= 5 | x = x * 5 |
| /= | x /= 5 | x = x / 5 |
| %= | x %= 5 | x = x % 5 |
| **= | x **= 2 | x = x ** 2 |

**Example:**

```javascript
let price = 100;

price += 50;

console.log(price);
```

**Output:**

```text
150
```

<a id="comparison-operators"></a>

## Comparison Operators

Comparison operators do values ko compare karte hain aur Boolean result return karte hain.

| Operator | Meaning | Example |
|---|---|---|
| == | Equal value | 5 == "5" |
| === | Equal value and type | 5 === "5" |
| != | Not equal value | 5 != 3 |
| !== | Not equal value or type | 5 !== "5" |
| > | Greater than | 10 > 5 |
| < | Less than | 5 < 10 |
| >= | Greater than or equal | 10 >= 10 |
| <= | Less than or equal | 5 <= 10 |

**Example:**

```javascript
console.log(10 > 5);

console.log(10 < 5);

console.log(5 == "5");

console.log(5 === "5");
```

**Output:**

```text
true
false
true
false
```

**Important:**

- `==` comparison se pehle type conversion kar sakta hai.
- `===` value aur type dono compare karta hai.
- Generally `===` aur `!==` use karna better hai.

<a id="logical-operators"></a>

## Logical Operators

Logical operators multiple conditions ko combine karte hain.

| Operator | Name | Meaning |
|---|---|---|
| && | AND | Dono conditions true honi chahiye |
| || | OR | Kam se kam ek condition true honi chahiye |
| ! | NOT | Result ko reverse karta hai |

**AND Example:**

```javascript
let age = 20;

let hasID = true;

console.log(age >= 18 && hasID);
```

**Output:**

```text
true
```

**OR Example:**

```javascript
let isStudent = false;

let hasDiscount = true;

console.log(isStudent || hasDiscount);
```

**Output:**

```text
true
```

**NOT Example:**

```javascript
let isLoggedIn = true;

console.log(!isLoggedIn);
```

**Output:**

```text
false
```

<a id="increment-and-decrement"></a>

## Increment and Decrement

Increment operator value ko 1 se increase karta hai.

Decrement operator value ko 1 se decrease karta hai.

| Operator | Meaning |
|---|---|
| ++ | Increment |
| -- | Decrement |

**Increment Example:**

```javascript
let count = 5;

count++;

console.log(count);
```

**Output:**

```text
6
```

**Decrement Example:**

```javascript
let count = 5;

count--;

console.log(count);
```

**Output:**

```text
4
```

**Pre-Increment and Post-Increment:**

```javascript
let a = 5;

console.log(++a);
```

Output: `6`

```javascript
let b = 5;

console.log(b++);
```

Output: `5`

Post-increment mein pehle current value use hoti hai, phir value increase hoti hai.

<a id="string-operators"></a>

## String Operators

`+` operator strings ko join karne ke liye use hota hai.

Is process ko concatenation kehte hain.

```javascript
let firstName = "Sumit";

let lastName = "Kumar";

let fullName = firstName + " " + lastName;

console.log(fullName);
```

**Output:**

```text
Sumit Kumar
```

<a id="ternary-operator"></a>

## Ternary Operator

Ternary operator short conditional expression likhne ke liye use hota hai.

**Syntax:**

```javascript
condition ? valueIfTrue : valueIfFalse;
```

**Example:**

```javascript
let age = 20;

let result = age >= 18 ? "Eligible" : "Not Eligible";

console.log(result);
```

**Output:**

```text
Eligible
```

<a id="nullish-coalescing-operator"></a>

## Nullish Coalescing Operator

Nullish Coalescing Operator (`??`) tab right-side value return karta hai jab left-side value `null` ya `undefined` ho.

**Example:**

```javascript
let username = null;

let result = username ?? "Guest";

console.log(result);
```

**Output:**

```text
Guest
```

<a id="optional-chaining-operator"></a>

## Optional Chaining Operator

Optional Chaining (`?.`) object ki nested property safely access karne ke liye use hota hai.

Agar property `null` ya `undefined` ho toh error ki jagah `undefined` return hota hai.

**Example:**

```javascript
let user = {
    name: "Sumit",
    address: {
        city: "Delhi"
    }
};

console.log(user.address?.city);

console.log(user.contact?.phone);
```

**Output:**

```text
Delhi
undefined
```

<a id="operator-precedence"></a>

## Operator Precedence

Operator Precedence decide karta hai ki ek expression mein kaunsa operator pehle execute hoga.

**Example:**

```javascript
let result = 10 + 5 * 2;

console.log(result);
```

**Output:**

```text
20
```

Multiplication pehle execute hota hai, phir addition.

Parentheses use karke order change kar sakte hain.

```javascript
let result = (10 + 5) * 2;

console.log(result);
```

**Output:**

```text
30
```

---

# 7. JavaScript Type Conversion

<a id="what-is-type-conversion"></a>

## What is Type Conversion?

Type Conversion ka matlab ek data type ko doosre data type mein convert karna hai.

Example: String ko Number mein convert karna.

```javascript
let value = "100";

let result = Number(value);

console.log(result);

console.log(typeof result);
```

**Output:**

```text
100
number
```

<a id="string-conversion"></a>

## String Conversion

`String()` function kisi value ko string mein convert karta hai.

```javascript
let age = 19;

let result = String(age);

console.log(result);

console.log(typeof result);
```

**Output:**

```text
19
string
```

<a id="number-conversion"></a>

## Number Conversion

`Number()` function value ko number mein convert karne ki koshish karta hai.

```javascript
let value = "250";

let result = Number(value);

console.log(result);

console.log(typeof result);
```

**Output:**

```text
250
number
```

Invalid numeric text convert karne par `NaN` mil sakta hai.

```javascript
console.log(Number("Hello"));
```

**Output:**

```text
NaN
```

<a id="boolean-conversion"></a>

## Boolean Conversion

`Boolean()` function value ko true ya false mein convert karta hai.

```javascript
console.log(Boolean(1));

console.log(Boolean(0));

console.log(Boolean("Hello"));

console.log(Boolean(""));
```

**Output:**

```text
true
false
true
false
```

<a id="implicit-conversion"></a>

## Implicit Conversion

Jab JavaScript automatically ek data type ko doosre type mein convert karta hai, use Implicit Conversion ya Type Coercion kehte hain.

**Example:**

```javascript
let result = "10" + 5;

console.log(result);
```

**Output:**

```text
105
```

Yahan number `5` string mein convert ho gaya.

<a id="explicit-conversion"></a>

## Explicit Conversion

Jab developer manually type conversion karta hai, use Explicit Conversion kehte hain.

**Example:**

```javascript
let value = "10";

let result = Number(value);

console.log(result + 5);
```

**Output:**

```text
15
```

<a id="parseint-method"></a>

## parseInt() Method

`parseInt()` string se integer number parse karta hai.

```javascript
let value = "250px";

let result = parseInt(value);

console.log(result);
```

**Output:**

```text
250
```

<a id="parsefloat-method"></a>

## parseFloat() Method

`parseFloat()` string se decimal number parse karta hai.

```javascript
let value = "99.50";

let result = parseFloat(value);

console.log(result);
```

**Output:**

```text
99.5
```

<a id="nan"></a>

## NaN

NaN ka full form Not-a-Number hai.

Jab numeric operation valid number produce nahi karta, toh `NaN` mil sakta hai.

```javascript
let result = Number("Hello");

console.log(result);

console.log(Number.isNaN(result));
```

**Output:**

```text
NaN
true
```

---

# 8. JavaScript Input and Output

<a id="consolelog"></a>

## console.log()

`console.log()` console mein output display karne ke liye use hota hai.

```javascript
console.log("Hello World");

console.log(100);

console.log(10 + 20);
```

**Output:**

```text
Hello World
100
30
```

<a id="consoleerror"></a>

## console.error()

`console.error()` console mein error message display karta hai.

```javascript
console.error("Something went wrong!");
```

**Output:**

```text
Something went wrong!
```

<a id="consolewarn"></a>

## console.warn()

`console.warn()` console mein warning message display karta hai.

```javascript
console.warn("This is a warning!");
```

**Output:**

```text
This is a warning!
```

<a id="consoletable"></a>

## console.table()

`console.table()` array ya object data ko table format mein display karta hai.

```javascript
let student = [
    { name: "Sumit", age: 19 },
    { name: "Rahul", age: 20 }
];

console.table(student);
```

**Output:**

```text
┌─────────┬─────────┬─────┐
│ (index) │ name    │ age │
├─────────┼─────────┼─────┤
│ 0       │ Sumit   │ 19  │
│ 1       │ Rahul   │ 20  │
└─────────┴─────────┴─────┘
```

<a id="alert"></a>

## alert()

`alert()` browser mein message popup display karta hai.

```javascript
alert("Welcome to JavaScript!");
```

**Output:**

```text
Browser popup:

Welcome to JavaScript!
```

**Output Screenshot:**

[Add your browser alert popup screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="prompt"></a>

## prompt()

`prompt()` user se input receive karne ke liye popup open karta hai.

Yeh generally entered value ko string ke form mein return karta hai.

```javascript
let name = prompt("Enter your name:");

console.log(name);
```

**Example Output:**

```text
Sumit
```

<a id="confirm"></a>

## confirm()

`confirm()` user ko OK aur Cancel options wala popup display karta hai.

- OK select karne par `true`.
- Cancel select karne par `false`.

```javascript
let result = confirm("Do you want to continue?");

console.log(result);
```

**Output:**

```text
true
```

<a id="documentwrite"></a>

## document.write()

`document.write()` HTML document mein text ya HTML output write karta hai.

```javascript
document.write("<h1>Hello JavaScript</h1>");

document.write("<p>Learning Web Development</p>");
```

**Output:**

```text
Hello JavaScript

Learning Web Development
```

**Important:** Page load hone ke baad `document.write()` call karne se existing document content replace ho sakta hai. Modern development mein DOM methods prefer kiye jaate hain.

---

# 9. JavaScript Strings

<a id="creating-strings"></a>

## Creating Strings

String text data ko represent karti hai.

JavaScript mein strings create karne ke three common methods hain:

```javascript
let name1 = "Sumit";

let name2 = 'Rahul';

let name3 = `Aman`;

console.log(name1);

console.log(name2);

console.log(name3);
```

**Output:**

```text
Sumit
Rahul
Aman
```

<a id="string-length"></a>

## String Length

`.length` property string ke total characters count karti hai.

```javascript
let name = "JavaScript";

console.log(name.length);
```

**Output:**

```text
10
```

<a id="string-indexing"></a>

## String Indexing

String mein har character ka ek index number hota hai.

Index `0` se start hota hai.

```javascript
let name = "Sumit";

console.log(name[0]);

console.log(name[1]);

console.log(name[2]);
```

**Output:**

```text
S
u
m
```

<a id="charat"></a>

## charAt()

`charAt()` method given index par available character return karta hai.

```javascript
let name = "JavaScript";

console.log(name.charAt(0));

console.log(name.charAt(4));
```

**Output:**

```text
J
S
```

<a id="at"></a>

## at()

`at()` method given index ka character return karta hai. Negative index bhi support karta hai.

```javascript
let name = "JavaScript";

console.log(name.at(0));

console.log(name.at(-1));
```

**Output:**

```text
J
t
```

<a id="touppercase"></a>

## toUpperCase()

`toUpperCase()` string ke letters ko uppercase mein convert karta hai.

```javascript
let name = "javascript";

console.log(name.toUpperCase());
```

**Output:**

```text
JAVASCRIPT
```

<a id="tolowercase"></a>

## toLowerCase()

`toLowerCase()` string ke letters ko lowercase mein convert karta hai.

```javascript
let name = "JAVASCRIPT";

console.log(name.toLowerCase());
```

**Output:**

```text
javascript
```

<a id="trim"></a>

## trim()

`trim()` string ke start aur end se extra whitespace remove karta hai.

```javascript
let name = "   Sumit   ";

console.log(name.trim());
```

**Output:**

```text
Sumit
```

<a id="includes"></a>

## includes()

`includes()` check karta hai ki string mein given text present hai ya nahi.

Result Boolean mein milta hai.

```javascript
let message = "I am learning JavaScript";

console.log(message.includes("JavaScript"));

console.log(message.includes("Python"));
```

**Output:**

```text
true
false
```

<a id="startswith-and-endswith"></a>

## startsWith() and endsWith()

`startsWith()` check karta hai ki string kisi text se start hoti hai ya nahi.

`endsWith()` check karta hai ki string kisi text par end hoti hai ya nahi.

```javascript
let name = "JavaScript";

console.log(name.startsWith("Java"));

console.log(name.endsWith("Script"));
```

**Output:**

```text
true
true
```

<a id="indexof-and-lastindexof"></a>

## indexOf() and lastIndexOf()

`indexOf()` first matching text ka index return karta hai.

`lastIndexOf()` last matching text ka index return karta hai.

```javascript
let text = "Hello JavaScript Hello";

console.log(text.indexOf("Hello"));

console.log(text.lastIndexOf("Hello"));
```

**Output:**

```text
0
18
```

<a id="slice"></a>

## slice()

`slice()` string ka selected portion return karta hai.

**Syntax:**

```javascript
string.slice(start, end);
```

End index include nahi hota.

```javascript
let language = "JavaScript";

console.log(language.slice(0, 4));

console.log(language.slice(4));
```

**Output:**

```text
Java
Script
```

<a id="substring"></a>

## substring()

`substring()` string ka selected portion return karta hai.

```javascript
let language = "JavaScript";

console.log(language.substring(0, 4));
```

**Output:**

```text
Java
```

**Difference:**

- `slice()` negative indexes support karta hai.
- `substring()` negative indexes ko `0` treat karta hai.

<a id="replace-and-replaceall"></a>

## replace() and replaceAll()

`replace()` matching text ka first occurrence replace karta hai.

`replaceAll()` matching text ke saare occurrences replace karta hai.

```javascript
let text = "Hello World World";

console.log(text.replace("World", "JavaScript"));

console.log(text.replaceAll("World", "JavaScript"));
```

**Output:**

```text
Hello JavaScript World

Hello JavaScript JavaScript
```

<a id="split"></a>

## split()

`split()` string ko specified separator ke according array mein convert karta hai.

```javascript
let skills = "HTML,CSS,JavaScript";

console.log(skills.split(","));
```

**Output:**

```text
["HTML", "CSS", "JavaScript"]
```

<a id="repeat"></a>

## repeat()

`repeat()` string ko specified number of times repeat karta hai.

```javascript
let text = "Hello ";

console.log(text.repeat(3));
```

**Output:**

```text
Hello Hello Hello
```

<a id="template-literals"></a>

## Template Literals

Template literals backticks (`` ` ``) ka use karke create hote hain.

Inmein variables aur expressions insert karne ke liye `${}` use hota hai.

```javascript
let name = "Sumit";

let age = 19;

console.log(`My name is ${name} and I am ${age} years old.`);
```

**Output:**

```text
My name is Sumit and I am 19 years old.
```

**Important:** Template literals multiple lines aur dynamic strings create karne mein useful hain.

---

# 10. JavaScript Numbers and Math

<a id="number-basics"></a>

## Number Basics

JavaScript mein Number data type integer aur decimal numbers dono ko represent karta hai.

```javascript
let price = 500;

let discount = 50.5;

console.log(price);

console.log(discount);
```

**Output:**

```text
500
50.5
```

<a id="number-methods"></a>

## Number Methods

JavaScript mein numbers ke saath kaam karne ke liye Number methods available hain.

Common methods:

| Method | Purpose |
|---|---|
| toFixed() | Decimal places fix karna |
| toString() | Number ko string banana |
| Number.isInteger() | Integer check karna |
| Number.isNaN() | NaN check karna |
| Number.isFinite() | Finite number check karna |
| Number.isSafeInteger() | Safe integer check karna |
| Number.parseInt() | Integer parse karna |
| Number.parseFloat() | Decimal parse karna |

<a id="tofixed"></a>

## toFixed()

`toFixed()` decimal places ko specified number tak format karta hai.

Yeh string return karta hai.

```javascript
let price = 99.5678;

console.log(price.toFixed(2));
```

**Output:**

```text
99.57
```

<a id="tostring"></a>

## toString()

`toString()` number ko string mein convert karta hai.

```javascript
let number = 100;

let result = number.toString();

console.log(result);

console.log(typeof result);
```

**Output:**

```text
100
string
```

<a id="numberisinteger"></a>

## Number.isInteger()

`Number.isInteger()` check karta hai ki value integer hai ya nahi.

```javascript
console.log(Number.isInteger(10));

console.log(Number.isInteger(10.5));
```

**Output:**

```text
true
false
```

<a id="numberisnan"></a>

## Number.isNaN()

`Number.isNaN()` check karta hai ki value actual NaN hai ya nahi.

```javascript
console.log(Number.isNaN(NaN));

console.log(Number.isNaN("Hello"));
```

**Output:**

```text
true
false
```

<a id="math-object"></a>

## Math Object

JavaScript ka `Math` object mathematical calculations ke liye properties aur methods provide karta hai.

Common Math methods:

| Method | Purpose |
|---|---|
| Math.round() | Nearest integer |
| Math.floor() | Neeche round |
| Math.ceil() | Upar round |
| Math.trunc() | Decimal part remove |
| Math.random() | Random number |
| Math.max() | Maximum value |
| Math.min() | Minimum value |
| Math.abs() | Absolute value |
| Math.sqrt() | Square root |
| Math.pow() | Power |

<a id="mathround"></a>

## Math.round()

`Math.round()` number ko nearest integer mein round karta hai.

```javascript
console.log(Math.round(4.4));

console.log(Math.round(4.7));
```

**Output:**

```text
4
5
```

<a id="mathfloor-and-mathceil"></a>

## Math.floor() and Math.ceil()

`Math.floor()` number ko lower integer tak round karta hai.

`Math.ceil()` number ko upper integer tak round karta hai.

```javascript
console.log(Math.floor(4.9));

console.log(Math.ceil(4.1));
```

**Output:**

```text
4
5
```

<a id="mathrandom"></a>

## Math.random()

`Math.random()` 0 se lekar 1 se chhota random decimal number return karta hai.

```javascript
console.log(Math.random());
```

**Example Output:**

```text
0.5847362
```

**Random number between 1 and 10:**

```javascript
let number = Math.floor(Math.random() * 10) + 1;

console.log(number);
```

**Possible Output:**

```text
7
```

<a id="mathmax-and-mathmin"></a>

## Math.max() and Math.min()

`Math.max()` given numbers mein sabse badi value return karta hai.

`Math.min()` given numbers mein sabse chhoti value return karta hai.

```javascript
console.log(Math.max(10, 20, 30, 40));

console.log(Math.min(10, 20, 30, 40));
```

**Output:**

```text
40
10
```

<a id="mathabs-and-mathsqrt"></a>

## Math.abs() and Math.sqrt()

`Math.abs()` absolute value return karta hai.

`Math.sqrt()` square root calculate karta hai.

```javascript
console.log(Math.abs(-25));

console.log(Math.sqrt(64));
```

**Output:**

```text
25
8
```

<a id="mathpow-and-mathtrunc"></a>

## Math.pow() and Math.trunc()

`Math.pow()` number ki power calculate karta hai.

`Math.trunc()` decimal part remove karta hai.

```javascript
console.log(Math.pow(2, 3));

console.log(Math.trunc(9.85));
```

**Output:**

```text
8
9
```

---

# 11. Conditional Statements

<a id="what-are-conditions"></a>

## What are Conditions?

Conditions ka use different situations ke according code execute karne ke liye hota hai.

Example:

Agar user ki age 18 ya usse zyada hai, toh user eligible hai.

<a id="if-statement"></a>

## if Statement

`if` statement tab code execute karta hai jab condition true hoti hai.

**Syntax:**

```javascript
if (condition) {
    // Code
}
```

**Example:**

```javascript
let age = 20;

if (age >= 18) {
    console.log("You are eligible.");
}
```

**Output:**

```text
You are eligible.
```

<a id="if-else-statement"></a>

## if-else Statement

`if-else` ka use do possible situations mein se ek choose karne ke liye hota hai.

```javascript
let age = 16;

if (age >= 18) {
    console.log("You are eligible.");
} else {
    console.log("You are not eligible.");
}
```

**Output:**

```text
You are not eligible.
```

<a id="else-if-ladder"></a>

## else-if Ladder

Multiple conditions check karne ke liye `else if` use hota hai.

```javascript
let marks = 75;

if (marks >= 90) {
    console.log("Grade A");
} else if (marks >= 75) {
    console.log("Grade B");
} else if (marks >= 50) {
    console.log("Grade C");
} else {
    console.log("Fail");
}
```

**Output:**

```text
Grade B
```

<a id="nested-if-statement"></a>

## Nested if Statement

Jab ek `if` statement ke andar doosra `if` statement likha jaata hai, use Nested if kehte hain.

```javascript
let age = 20;

let hasID = true;

if (age >= 18) {

    if (hasID) {
        console.log("Entry Allowed");
    }

}
```

**Output:**

```text
Entry Allowed
```

<a id="switch-statement"></a>

## switch Statement

`switch` statement ek expression ki value ke according different cases execute karta hai.

**Syntax:**

```javascript
switch (expression) {

    case value1:
        // Code
        break;

    case value2:
        // Code
        break;

    default:
        // Default code
}
```

**Example:**

```javascript
let day = 2;

switch (day) {

    case 1:
        console.log("Monday");
        break;

    case 2:
        console.log("Tuesday");
        break;

    case 3:
        console.log("Wednesday");
        break;

    default:
        console.log("Invalid Day");
}
```

**Output:**

```text
Tuesday
```

**Important:**

- `case` possible value define karta hai.
- `break` switch execution ko stop karta hai.
- `default` tab execute hota hai jab matching case nahi milta.

<a id="ternary-operator-in-conditions"></a>

## Ternary Operator

Ternary operator ek short conditional expression hai.

```javascript
let age = 20;

let result = age >= 18 ? "Adult" : "Minor";

console.log(result);
```

**Output:**

```text
Adult
```

<a id="truthy-and-falsy-values"></a>

## Truthy and Falsy Values

JavaScript mein values ko Boolean context mein true ya false treat kiya ja sakta hai.

**Falsy Values:**

- false
- 0
- -0
- 0n
- ""
- null
- undefined
- NaN

Inke alawa generally values truthy hoti hain, including empty arrays aur empty objects.

**Example:**

```javascript
console.log(Boolean(0));

console.log(Boolean("Hello"));

console.log(Boolean([]));

console.log(Boolean({}));
```

**Output:**

```text
false
true
true
true
```

---

# 12. JavaScript Loops

<a id="what-are-loops"></a>

## What are Loops?

Loops ka use kisi code ko baar-baar execute karne ke liye hota hai.

Agar humein same task multiple times perform karna ho, toh loop use kar sakte hain.

<a id="for-loop"></a>

## for Loop

`for` loop tab useful hota hai jab humein iterations ki count ya range pata ho.

**Syntax:**

```javascript
for (initialization; condition; update) {
    // Code
}
```

**Example:**

```javascript
for (let i = 1; i <= 5; i++) {
    console.log(i);
}
```

**Output:**

```text
1
2
3
4
5
```

<a id="while-loop"></a>

## while Loop

`while` loop tab tak execute hota hai jab tak condition true hoti hai.

**Syntax:**

```javascript
while (condition) {
    // Code
}
```

**Example:**

```javascript
let i = 1;

while (i <= 5) {
    console.log(i);

    i++;
}
```

**Output:**

```text
1
2
3
4
5
```

<a id="do-while-loop"></a>

## do-while Loop

`do-while` loop mein code pehle execute hota hai aur condition baad mein check hoti hai.

Isliye yeh kam se kam ek baar execute hota hai.

**Syntax:**

```javascript
do {
    // Code
} while (condition);
```

**Example:**

```javascript
let i = 1;

do {
    console.log(i);

    i++;
} while (i <= 5);
```

**Output:**

```text
1
2
3
4
5
```

<a id="forof-loop"></a>

## for...of Loop

`for...of` iterable values ke elements ko access karne ke liye use hota hai.

Example: Arrays aur strings.

```javascript
let skills = ["HTML", "CSS", "JavaScript"];

for (let skill of skills) {
    console.log(skill);
}
```

**Output:**

```text
HTML
CSS
JavaScript
```

<a id="forin-loop"></a>

## for...in Loop

`for...in` object ki enumerable property keys ko access karta hai.

```javascript
let student = {
    name: "Sumit",
    age: 19,
    city: "Delhi"
};

for (let key in student) {
    console.log(key);
}
```

**Output:**

```text
name
age
city
```

<a id="nested-loops"></a>

## Nested Loops

Jab ek loop ke andar doosra loop use hota hai, use Nested Loop kehte hain.

```javascript
for (let i = 1; i <= 3; i++) {

    for (let j = 1; j <= 2; j++) {

        console.log(i, j);

    }

}
```

**Output:**

```text
1 1
1 2
2 1
2 2
3 1
3 2
```

<a id="break-statement"></a>

## break Statement

`break` statement loop ko immediately stop kar deta hai.

```javascript
for (let i = 1; i <= 10; i++) {

    if (i === 5) {
        break;
    }

    console.log(i);
}
```

**Output:**

```text
1
2
3
4
```

<a id="continue-statement"></a>

## continue Statement

`continue` statement current iteration ko skip karke next iteration par chala jaata hai.

```javascript
for (let i = 1; i <= 5; i++) {

    if (i === 3) {
        continue;
    }

    console.log(i);
}
```

**Output:**

```text
1
2
4
5
```

---

# 13. JavaScript Functions

<a id="what-are-functions"></a>

## What are Functions?

Function reusable code ka block hota hai jo kisi particular task ko perform karta hai.

Ek function ko multiple times call kiya ja sakta hai.

**Example:**

```javascript
function greet() {
    console.log("Hello Sumit!");
}

greet();
```

**Output:**

```text
Hello Sumit!
```

<a id="function-declaration"></a>

## Function Declaration

Function declaration mein `function` keyword ka use karke function define kiya jaata hai.

**Syntax:**

```javascript
function functionName() {
    // Code
}
```

**Example:**

```javascript
function welcome() {
    console.log("Welcome to JavaScript!");
}
```

<a id="function-calling"></a>

## Function Calling

Function ko execute karne ke liye uske naam ke baad parentheses `()` lagate hain.

```javascript
function welcome() {
    console.log("Welcome!");
}

welcome();
```

**Output:**

```text
Welcome!
```

<a id="parameters-and-arguments"></a>

## Parameters and Arguments

Parameters function definition mein declare kiye gaye variables hote hain.

Arguments function call karte waqt pass ki gayi actual values hoti hain.

```javascript
function greet(name) {
    console.log("Hello " + name);
}

greet("Sumit");
```

**Output:**

```text
Hello Sumit
```

Yahan:

- `name` parameter hai.
- `"Sumit"` argument hai.

<a id="return-statement"></a>

## Return Statement

`return` function se value wapas bhejne ke liye use hota hai.

```javascript
function add(a, b) {

    return a + b;

}

let result = add(10, 20);

console.log(result);
```

**Output:**

```text
30
```

<a id="default-parameters"></a>

## Default Parameters

Agar function call ke waqt argument provide na ho, toh default parameter value use ho sakti hai.

```javascript
function greet(name = "Guest") {

    console.log("Hello " + name);

}

greet();

greet("Sumit");
```

**Output:**

```text
Hello Guest
Hello Sumit
```

<a id="function-expression"></a>

## Function Expression

Jab function ko variable mein assign kiya jaata hai, use Function Expression kehte hain.

```javascript
const greet = function() {

    console.log("Hello World!");

};

greet();
```

**Output:**

```text
Hello World!
```

<a id="arrow-functions"></a>

## Arrow Functions

Arrow Function JavaScript mein function likhne ka shorter syntax hai.

Ismein `=>` arrow operator use hota hai.

**Example:**

```javascript
const greet = () => {
    console.log("Hello JavaScript!");
};

greet();
```

**Output:**

```text
Hello JavaScript!
```

**Short Arrow Function:**

```javascript
const add = (a, b) => a + b;

console.log(add(10, 20));
```

**Output:**

```text
30
```

<a id="anonymous-functions"></a>

## Anonymous Functions

Anonymous Function woh function hota hai jiska apna naam nahi hota.

```javascript
setTimeout(function() {

    console.log("Hello!");

}, 1000);
```

**Output:**

```text
Hello!
```

<a id="callback-functions"></a>

## Callback Functions

Jab ek function ko doosre function ke argument ke roop mein pass kiya jaata hai, use Callback Function kehte hain.

```javascript
function greet(name, callback) {

    console.log("Hello " + name);

    callback();

}

function message() {

    console.log("Welcome!");

}

greet("Sumit", message);
```

**Output:**

```text
Hello Sumit
Welcome!
```

<a id="scope-and-functions"></a>

## Scope and Functions

Function ke andar declare kiye gaye local variables generally sirf us function ke andar accessible hote hain.

```javascript
function showMessage() {

    let message = "Hello World";

    console.log(message);

}

showMessage();
```

**Output:**

```text
Hello World
```

<a id="recursion"></a>

## Recursion

Jab function apne aap ko call karta hai, use Recursion kehte hain.

```javascript
function countDown(number) {

    if (number === 0) {
        return;
    }

    console.log(number);

    countDown(number - 1);

}

countDown(5);
```

**Output:**

```text
5
4
3
2
1
```

**Important:** Recursion mein stopping condition hona zaroori hai, warna function repeatedly call hota rahega.

---

# 14. JavaScript Arrays

<a id="what-are-arrays"></a>

## What are Arrays?

Array ek data structure hai jisme multiple values ko ek single variable mein store kar sakte hain.

Array mein values different data types ki bhi ho sakti hain.

<a id="creating-arrays"></a>

## Creating Arrays

Array create karne ke liye square brackets `[]` use hote hain.

```javascript
let skills = ["HTML", "CSS", "JavaScript"];

console.log(skills);
```

**Output:**

```text
["HTML", "CSS", "JavaScript"]
```

<a id="accessing-array-elements"></a>

## Accessing Array Elements

Array elements ko index ke through access kiya jaata hai.

Index `0` se start hota hai.

```javascript
let fruits = ["Apple", "Banana", "Mango"];

console.log(fruits[0]);

console.log(fruits[1]);

console.log(fruits[2]);
```

**Output:**

```text
Apple
Banana
Mango
```

<a id="changing-array-elements"></a>

## Changing Array Elements

Array ke kisi element ki value ko index ke through update kar sakte hain.

```javascript
let fruits = ["Apple", "Banana", "Mango"];

fruits[1] = "Orange";

console.log(fruits);
```

**Output:**

```text
["Apple", "Orange", "Mango"]
```

<a id="array-length"></a>

## Array Length

`.length` property array ke total elements count karti hai.

```javascript
let skills = ["HTML", "CSS", "JavaScript"];

console.log(skills.length);
```

**Output:**

```text
3
```

<a id="push-and-pop"></a>

## push() and pop()

`push()` array ke end mein element add karta hai.

`pop()` array ke end se element remove karta hai.

```javascript
let fruits = ["Apple", "Banana"];

fruits.push("Mango");

console.log(fruits);

fruits.pop();

console.log(fruits);
```

**Output:**

```text
["Apple", "Banana", "Mango"]

["Apple", "Banana"]
```

<a id="shift-and-unshift"></a>

## shift() and unshift()

`shift()` array ke beginning se element remove karta hai.

`unshift()` array ke beginning mein element add karta hai.

```javascript
let fruits = ["Apple", "Banana"];

fruits.unshift("Mango");

console.log(fruits);

fruits.shift();

console.log(fruits);
```

**Output:**

```text
["Mango", "Apple", "Banana"]

["Apple", "Banana"]
```

<a id="array-indexof-and-includes"></a>

## indexOf() and includes()

`indexOf()` element ka first matching index return karta hai.

`includes()` check karta hai ki element array mein present hai ya nahi.

```javascript
let fruits = ["Apple", "Banana", "Mango"];

console.log(fruits.indexOf("Banana"));

console.log(fruits.includes("Mango"));
```

**Output:**

```text
1
true
```

<a id="slice-and-splice"></a>

## slice() and splice()

`slice()` array ka selected portion return karta hai aur original array ko change nahi karta.

`splice()` array mein elements add, remove ya replace kar sakta hai.

**slice() Example:**

```javascript
let numbers = [10, 20, 30, 40, 50];

let result = numbers.slice(1, 4);

console.log(result);

console.log(numbers);
```

**Output:**

```text
[20, 30, 40]

[10, 20, 30, 40, 50]
```

**splice() Example:**

```javascript
let numbers = [10, 20, 30, 40];

numbers.splice(1, 2);

console.log(numbers);
```

**Output:**

```text
[10, 40]
```

<a id="concat"></a>

## concat()

`concat()` do ya more arrays ko combine karta hai aur new array return karta hai.

```javascript
let frontend = ["HTML", "CSS"];

let backend = ["Node.js", "Express"];

let skills = frontend.concat(backend);

console.log(skills);
```

**Output:**

```text
["HTML", "CSS", "Node.js", "Express"]
```

<a id="join"></a>

## join()

`join()` array ke elements ko string mein combine karta hai.

```javascript
let skills = ["HTML", "CSS", "JavaScript"];

console.log(skills.join(", "));
```

**Output:**

```text
HTML, CSS, JavaScript
```

<a id="reverse-and-sort"></a>

## reverse() and sort()

`reverse()` array ke elements ka order reverse karta hai.

`sort()` array ke elements ko sort karta hai.

```javascript
let fruits = ["Mango", "Apple", "Banana"];

fruits.sort();

console.log(fruits);

fruits.reverse();

console.log(fruits);
```

**Output:**

```text
["Apple", "Banana", "Mango"]

["Mango", "Banana", "Apple"]
```

**Important:** Default `sort()` values ko string ke according compare karta hai. Numbers ko ascending order mein sort karne ke liye:

```javascript
let numbers = [40, 5, 100, 20];

numbers.sort((a, b) => a - b);

console.log(numbers);
```

**Output:**

```text
[5, 20, 40, 100]
```

<a id="foreach"></a>

## forEach()

`forEach()` array ke har element par callback function execute karta hai.

```javascript
let fruits = ["Apple", "Banana", "Mango"];

fruits.forEach(function(fruit) {

    console.log(fruit);

});
```

**Output:**

```text
Apple
Banana
Mango
```

<a id="map"></a>

## map()

`map()` array ke har element par callback execute karke new array create karta hai.

```javascript
let numbers = [1, 2, 3, 4];

let result = numbers.map(function(number) {

    return number * 2;

});

console.log(result);
```

**Output:**

```text
[2, 4, 6, 8]
```

<a id="filter"></a>

## filter()

`filter()` condition match karne wale elements ka new array return karta hai.

```javascript
let numbers = [10, 15, 20, 25, 30];

let result = numbers.filter(function(number) {

    return number >= 20;

});

console.log(result);
```

**Output:**

```text
[20, 25, 30]
```

<a id="find-and-findindex"></a>

## find() and findIndex()

`find()` condition match karne wala first element return karta hai.

`findIndex()` us element ka index return karta hai.

```javascript
let numbers = [10, 20, 30, 40];

console.log(numbers.find(number => number > 20));

console.log(numbers.findIndex(number => number > 20));
```

**Output:**

```text
30
2
```

<a id="reduce"></a>

## reduce()

`reduce()` array ke elements ko process karke ek single result produce karta hai.

```javascript
let numbers = [10, 20, 30];

let total = numbers.reduce((sum, number) => {

    return sum + number;

}, 0);

console.log(total);
```

**Output:**

```text
60
```

<a id="some-and-every"></a>

## some() and every()

`some()` check karta hai ki kam se kam ek element condition match karta hai ya nahi.

`every()` check karta hai ki saare elements condition match karte hain ya nahi.

```javascript
let numbers = [10, 20, 30, 40];

console.log(numbers.some(number => number > 30));

console.log(numbers.every(number => number > 5));
```

**Output:**

```text
true
true
```

<a id="array-destructuring"></a>

## Array Destructuring

Array Destructuring se array elements ko separate variables mein assign kar sakte hain.

```javascript
let skills = ["HTML", "CSS", "JavaScript"];

let [first, second, third] = skills;

console.log(first);

console.log(second);

console.log(third);
```

**Output:**

```text
HTML
CSS
JavaScript
```

---

# 15. JavaScript Objects

<a id="what-are-objects"></a>

## What are Objects?

Object JavaScript mein related data aur functionality ko ek jagah store karne ka tarika hai.

Object data ko key-value pairs ke form mein store karta hai.

**Example:**

```javascript
let student = {
    name: "Sumit",
    age: 19,
    city: "Delhi"
};

console.log(student);
```

**Output:**

```text
{
    name: "Sumit",
    age: 19,
    city: "Delhi"
}
```

<a id="creating-objects"></a>

## Creating Objects

Object create karne ke liye curly brackets `{}` use hote hain.

```javascript
let product = {
    name: "Laptop",
    price: 50000,
    brand: "Dell"
};

console.log(product);
```

**Output:**

```text
{
    name: "Laptop",
    price: 50000,
    brand: "Dell"
}
```

<a id="object-properties"></a>

## Object Properties

Object ke andar key-value pairs ko properties kehte hain.

```javascript
let student = {
    name: "Sumit",
    age: 19,
    course: "Web Development"
};
```

Yahan:

- `name`, `age`, `course` — Keys.
- `"Sumit"`, `19`, `"Web Development"` — Values.

<a id="accessing-object-properties"></a>

## Accessing Object Properties

Object properties ko access karne ke two common methods hain.

**1. Dot Notation**

```javascript
let student = {
    name: "Sumit",
    age: 19
};

console.log(student.name);
```

**Output:**

```text
Sumit
```

**2. Bracket Notation**

```javascript
let student = {
    name: "Sumit",
    age: 19
};

console.log(student["age"]);
```

**Output:**

```text
19
```

<a id="adding-and-updating-properties"></a>

## Adding and Updating Properties

Object mein new property add kar sakte hain aur existing property update bhi kar sakte hain.

```javascript
let student = {
    name: "Sumit",
    age: 19
};

// Add Property
student.city = "Delhi";

// Update Property
student.age = 20;

console.log(student);
```

**Output:**

```text
{
    name: "Sumit",
    age: 20,
    city: "Delhi"
}
```

<a id="deleting-properties"></a>

## Deleting Properties

`delete` operator ka use object ki property remove karne ke liye hota hai.

```javascript
let student = {
    name: "Sumit",
    age: 19,
    city: "Delhi"
};

delete student.city;

console.log(student);
```

**Output:**

```text
{
    name: "Sumit",
    age: 19
}
```

<a id="object-methods"></a>

## Object Methods

Jab object ki property mein function store hota hai, use commonly object method kehte hain.

```javascript
let student = {

    name: "Sumit",

    greet: function() {

        console.log("Hello " + this.name);

    }

};

student.greet();
```

**Output:**

```text
Hello Sumit
```

<a id="this-keyword"></a>

## this Keyword

`this` keyword current execution context ke according kisi object ya context ko refer karta hai.

Object method mein `this` commonly us object ko refer karta hai jiske through method call hua hai.

```javascript
let student = {

    name: "Sumit",

    showName: function() {

        console.log(this.name);

    }

};

student.showName();
```

**Output:**

```text
Sumit
```

**Important:** Arrow functions ka apna `this` nahi hota. Yeh surrounding scope se `this` inherit karte hain.

<a id="objectkeys"></a>

## Object.keys()

`Object.keys()` object ki enumerable property keys ka array return karta hai.

```javascript
let student = {
    name: "Sumit",
    age: 19,
    city: "Delhi"
};

console.log(Object.keys(student));
```

**Output:**

```text
["name", "age", "city"]
```

<a id="objectvalues"></a>

## Object.values()

`Object.values()` object ki enumerable property values ka array return karta hai.

```javascript
let student = {
    name: "Sumit",
    age: 19,
    city: "Delhi"
};

console.log(Object.values(student));
```

**Output:**

```text
["Sumit", 19, "Delhi"]
```

<a id="objectentries"></a>

## Object.entries()

`Object.entries()` object ki key-value pairs ko nested arrays ke form mein return karta hai.

```javascript
let student = {
    name: "Sumit",
    age: 19
};

console.log(Object.entries(student));
```

**Output:**

```text
[
    ["name", "Sumit"],
    ["age", 19]
]
```

<a id="object-destructuring"></a>

## Object Destructuring

Object Destructuring se object properties ko separate variables mein assign kar sakte hain.

```javascript
let student = {
    name: "Sumit",
    age: 19,
    city: "Delhi"
};

let { name, age, city } = student;

console.log(name);

console.log(age);

console.log(city);
```

**Output:**

```text
Sumit
19
Delhi
```

<a id="spread-operator"></a>

## Spread Operator

Spread Operator (`...`) iterable ya object ki values ko expand karne ke liye use hota hai.

**Array Example:**

```javascript
let first = [10, 20];

let second = [30, 40];

let result = [...first, ...second];

console.log(result);
```

**Output:**

```text
[10, 20, 30, 40]
```

**Object Example:**

```javascript
let user = {
    name: "Sumit",
    age: 19
};

let updatedUser = {
    ...user,
    city: "Delhi"
};

console.log(updatedUser);
```

**Output:**

```text
{
    name: "Sumit",
    age: 19,
    city: "Delhi"
}
```

<a id="optional-chaining"></a>

## Optional Chaining

Optional Chaining (`?.`) nested object properties ko safely access karne ke liye use hota hai.

```javascript
let user = {
    name: "Sumit",
    address: {
        city: "Delhi"
    }
};

console.log(user.address?.city);

console.log(user.contact?.phone);
```

**Output:**

```text
Delhi
undefined
```

---

## Important JavaScript Keywords

| Keyword | Purpose |
|---|---|
| var | Variable declaration |
| let | Block-scoped variable |
| const | Block-scoped constant binding |
| function | Function declaration |
| return | Function se value return |
| if | Condition check |
| else | Alternative condition |
| switch | Multiple cases |
| case | Switch case |
| break | Execution stop |
| continue | Current iteration skip |
| for | Loop |
| while | Condition-based loop |
| do | do-while loop |
| try | Error handling block |
| catch | Error handle |
| finally | Cleanup block |
| throw | Error throw |
| class | Class declaration |
| new | Object instance create |
| this | Current context reference |
| typeof | Data type check |
| delete | Object property delete |
| in | Property check |
| instanceof | Instance check |
| import | Module import |
| export | Module export |
| await | Promise result wait |
| async | Async function |
| yield | Generator pause |
| debugger | Debugger breakpoint |

## Important JavaScript Methods and Functions

| Method / Function | Purpose |
|---|---|
| console.log() | Console output |
| alert() | Popup message |
| prompt() | User input |
| confirm() | User confirmation |
| Number() | Convert to number |
| String() | Convert to string |
| Boolean() | Convert to Boolean |
| parseInt() | Parse integer |
| parseFloat() | Parse decimal |
| isNaN() | NaN check |
| setTimeout() | Delayed execution |
| setInterval() | Repeated execution |
| clearTimeout() | Timeout cancel |
| clearInterval() | Interval cancel |
| Math.random() | Random number |
| Math.round() | Round number |
| JSON.stringify() | Object to JSON string |
| JSON.parse() | JSON string to value |


# 16. DOM Manipulation

<a id="what-is-dom"></a>

## What is DOM?

DOM stands for Document Object Model.

DOM ek programming interface hai jo HTML document ko objects aur nodes ke tree structure mein represent karta hai.

JavaScript DOM ki help se HTML elements ko select, change, add aur remove kar sakti hai.

**Example:**

```html
<h1 id="heading">Hello World</h1>
```

```javascript
document.getElementById("heading").textContent = "Hello JavaScript";
```

**Output:**

```text
Hello JavaScript
```

**Output Screenshot:**

[Add your browser output screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="dom-tree"></a>

## DOM Tree

DOM Tree HTML document ka hierarchical structure hota hai.

Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>
<body>
    <h1>Hello</h1>
    <p>Welcome</p>
</body>
</html>
```

DOM Tree ka basic structure:

```text
Document
   |
   HTML
   |
   |--- HEAD
   |      |
   |      |--- TITLE
   |
   |--- BODY
          |
          |--- H1
          |
          |--- P
```

**Important Terms:**

| Term | Meaning |
|---|---|
| Document | Complete HTML document |
| Element | HTML element |
| Node | DOM tree ka individual part |
| Parent | Kisi doosre node ka parent |
| Child | Parent ke andar node |
| Sibling | Same parent ke nodes |

<a id="selecting-html-elements"></a>

## Selecting HTML Elements

JavaScript mein HTML elements select karne ke liye `document` object ke methods use hote hain.

Common methods:

| Method | Purpose |
|---|---|
| getElementById() | ID se element select |
| getElementsByClassName() | Class se elements select |
| getElementsByTagName() | Tag name se elements select |
| querySelector() | First matching element select |
| querySelectorAll() | All matching elements select |

<a id="getelementbyid"></a>

## getElementById()

`getElementById()` kisi element ko uski unique ID ke through select karta hai.

**index.html**

```html
<!DOCTYPE html>
<html>
<head>
    <title>getElementById</title>
</head>
<body>

    <h1 id="heading">Hello World</h1>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let heading = document.getElementById("heading");

console.log(heading);
```

**Output:**

```text
<h1 id="heading">Hello World</h1>
```

**Output Screenshot:**

[Add your browser console screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="getelementsbyclassname"></a>

## getElementsByClassName()

`getElementsByClassName()` given class name wale elements ka live HTMLCollection return karta hai.

**index.html**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Class Selector</title>
</head>
<body>

    <p class="text">First Paragraph</p>
    <p class="text">Second Paragraph</p>
    <p class="text">Third Paragraph</p>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let elements = document.getElementsByClassName("text");

console.log(elements);
```

**Output:**

```text
HTMLCollection
```

<a id="getelementsbytagname"></a>

## getElementsByTagName()

`getElementsByTagName()` specified HTML tag ke elements ka live HTMLCollection return karta hai.

```javascript
let paragraphs = document.getElementsByTagName("p");

console.log(paragraphs);
```

**Output:**

```text
HTMLCollection
```

<a id="queryselector"></a>

## querySelector()

`querySelector()` CSS selector ke according first matching element return karta hai.

```html
<h1 id="heading">Hello World</h1>

<p class="text">Learning JavaScript</p>
```

```javascript
let heading = document.querySelector("#heading");

let paragraph = document.querySelector(".text");

console.log(heading);

console.log(paragraph);
```

**Output:**

```text
<h1 id="heading">Hello World</h1>

<p class="text">Learning JavaScript</p>
```

<a id="queryselectorall"></a>

## querySelectorAll()

`querySelectorAll()` CSS selector se match hone wale sabhi elements ka static NodeList return karta hai.

```html
<p class="text">HTML</p>

<p class="text">CSS</p>

<p class="text">JavaScript</p>
```

```javascript
let elements = document.querySelectorAll(".text");

console.log(elements);
```

**Output:**

```text
NodeList(3)
```

**Difference:**

| Method | Return |
|---|---|
| querySelector() | First matching element |
| querySelectorAll() | Static NodeList |
| getElementsByClassName() | Live HTMLCollection |
| getElementsByTagName() | Live HTMLCollection |

<a id="changing-html-content"></a>

## Changing HTML Content

JavaScript ki help se HTML elements ka content change kar sakte hain.

```html
<h1 id="heading">Old Heading</h1>
```

```javascript
let heading = document.getElementById("heading");

heading.textContent = "New Heading";
```

**Output:**

```text
New Heading
```

**Output Screenshot:**

[Add your webpage output screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 200 px -->

<a id="innerhtml-and-textcontent"></a>

## innerHTML and textContent

`innerHTML` element ke andar HTML markup read ya set karta hai.

`textContent` element ka text content read ya set karta hai.

**innerHTML Example:**

```html
<div id="box"></div>
```

```javascript
let box = document.getElementById("box");

box.innerHTML = "<h2>Hello JavaScript</h2>";
```

**Output:**

```text
Hello JavaScript
```

**textContent Example:**

```javascript
let box = document.getElementById("box");

box.textContent = "<h2>Hello JavaScript</h2>";
```

**Output:**

```text
<h2>Hello JavaScript</h2>
```

Yahan HTML markup text ki tarah display hoga.

**Important:** Untrusted user input ko `innerHTML` mein directly insert nahi karna chahiye. Isse Cross-Site Scripting (XSS) ka risk ho sakta hai.

<a id="changing-css-with-javascript"></a>

## Changing CSS with JavaScript

JavaScript ki help se HTML elements ki CSS styling change kar sakte hain.

`style` property ka use hota hai.

**index.html**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Change CSS</title>
</head>
<body>

    <h1 id="heading">Hello World</h1>

    <button id="btn">Change Color</button>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let heading = document.getElementById("heading");

let button = document.getElementById("btn");

button.addEventListener("click", function() {

    heading.style.color = "blue";

    heading.style.fontSize = "40px";

});
```

**Output:**

Button click karne par heading blue ho jayegi aur font size 40px ho jayega.

**Output Screenshot:**

[Add your webpage output screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="changing-attributes"></a>

## Changing Attributes

JavaScript se HTML elements ke attributes ko read, add, update aur remove kar sakte hain.

Common methods:

| Method | Purpose |
|---|---|
| getAttribute() | Attribute value read |
| setAttribute() | Attribute add/update |
| removeAttribute() | Attribute remove |
| hasAttribute() | Attribute present check |

**Example:**

```html
<img id="photo" src="old.jpg" alt="Old Image">
```

```javascript
let image = document.getElementById("photo");

image.setAttribute("src", "new.jpg");

image.setAttribute("alt", "New Image");

console.log(image.getAttribute("src"));
```

**Output:**

```text
new.jpg
```

<a id="creating-html-elements"></a>

## Creating HTML Elements

`document.createElement()` ka use new HTML element create karne ke liye hota hai.

```javascript
let heading = document.createElement("h1");

heading.textContent = "Welcome to JavaScript";

console.log(heading);
```

**Output:**

```text
<h1>Welcome to JavaScript</h1>
```

**Note:** Element create karne se woh automatically webpage par display nahi hota. Use DOM mein insert karna padta hai.

<a id="append-and-appendchild"></a>

## append() and appendChild()

`append()` parent element ke end mein text ya nodes add kar sakta hai.

`appendChild()` parent element ke end mein ek Node add karta hai.

**append() Example:**

```html
<div id="box"></div>
```

```javascript
let box = document.getElementById("box");

let heading = document.createElement("h2");

heading.textContent = "Hello World";

box.append(heading);
```

**appendChild() Example:**

```javascript
let paragraph = document.createElement("p");

paragraph.textContent = "Learning DOM";

box.appendChild(paragraph);
```

**Output:**

```text
Hello World

Learning DOM
```

<a id="remove-and-removechild"></a>

## remove() and removeChild()

`remove()` element ko DOM se remove karta hai.

`removeChild()` parent ke specified child node ko remove karta hai.

**remove() Example:**

```html
<p id="text">Hello World</p>
```

```javascript
let paragraph = document.getElementById("text");

paragraph.remove();
```

**removeChild() Example:**

```html
<div id="box">
    <p id="text">Hello World</p>
</div>
```

```javascript
let box = document.getElementById("box");

let paragraph = document.getElementById("text");

box.removeChild(paragraph);
```

**Output:**

Paragraph webpage se remove ho jayega.

<a id="classlist-methods"></a>

## classList Methods

`classList` element ki CSS classes ko manage karne ke liye use hota hai.

| Method | Purpose |
|---|---|
| add() | Class add |
| remove() | Class remove |
| toggle() | Class add/remove |
| contains() | Class check |
| replace() | Class replace |

**Example:**

```html
<h1 id="heading">Hello World</h1>
```

```javascript
let heading = document.getElementById("heading");

heading.classList.add("active");

heading.classList.remove("active");

heading.classList.toggle("active");

console.log(heading.classList.contains("active"));
```

**Output:**

```text
true
```

<a id="dom-traversing"></a>

## DOM Traversing

DOM Traversing ka matlab DOM tree mein parent, child aur sibling elements ke beech move karna hai.

Important properties:

| Property | Purpose |
|---|---|
| parentElement | Parent element |
| children | Child elements |
| firstElementChild | First child element |
| lastElementChild | Last child element |
| nextElementSibling | Next sibling element |
| previousElementSibling | Previous sibling element |
| parentNode | Parent node |
| childNodes | All child nodes |

**Example:**

```html
<div id="parent">

    <h2>Heading</h2>

    <p>Paragraph</p>

</div>
```

```javascript
let parent = document.getElementById("parent");

console.log(parent.children);

console.log(parent.firstElementChild);

console.log(parent.lastElementChild);
```

**Output:**

```text
HTMLCollection(2)

<h2>Heading</h2>

<p>Paragraph</p>
```

---

# 17. JavaScript Events

<a id="what-are-events"></a>

## What are Events?

Events browser mein hone wale actions ya occurrences hote hain.

Examples:

- Button click.
- Mouse move.
- Keyboard press.
- Form submit.
- Input change.
- Page load.

JavaScript events ke through user actions par response de sakti hai.

<a id="onclick-event"></a>

## onclick Event

`onclick` event tab trigger hota hai jab user element par click karta hai.

**index.html**

```html
<!DOCTYPE html>
<html>
<head>
    <title>Click Event</title>
</head>
<body>

    <button onclick="showMessage()">Click Me</button>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
function showMessage() {

    alert("Button Clicked!");

}
```

**Output:**

Button click karne par popup display hoga.

**Output Screenshot:**

[Add your button click output screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="addeventlistener"></a>

## addEventListener()

`addEventListener()` kisi HTML element par event listener attach karta hai.

**Syntax:**

```javascript
element.addEventListener("event", function);
```

**Example:**

```html
<button id="btn">Click Me</button>
```

```javascript
let button = document.getElementById("btn");

button.addEventListener("click", function() {

    console.log("Button Clicked!");

});
```

**Output:**

```text
Button Clicked!
```

**Important:** `addEventListener()` use karna generally inline event attributes se better practice hai.

<a id="mouse-events"></a>

## Mouse Events

Mouse events mouse ke actions ke according trigger hote hain.

| Event | Purpose |
|---|---|
| click | Element click |
| dblclick | Double click |
| mousedown | Mouse button press |
| mouseup | Mouse button release |
| mousemove | Mouse movement |
| mouseenter | Element ke andar enter |
| mouseleave | Element se leave |
| mouseover | Element ya descendant par pointer enter |
| mouseout | Element ya descendant se pointer leave |
| contextmenu | Context menu event |

**Example:**

```html
<button id="btn">Hover Me</button>
```

```javascript
let button = document.getElementById("btn");

button.addEventListener("mouseenter", function() {

    button.style.backgroundColor = "blue";

    button.style.color = "white";

});

button.addEventListener("mouseleave", function() {

    button.style.backgroundColor = "lightgray";

    button.style.color = "black";

});
```

**Output:**

Mouse button par le jaane par background blue ho jayega. Mouse hatane par original styling aa jayegi.

**Output Screenshot:**

[Add your hover effect screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="keyboard-events"></a>

## Keyboard Events

Keyboard events keyboard actions ke according trigger hote hain.

| Event | Purpose |
|---|---|
| keydown | Key press |
| keyup | Key release |

**Example:**

```html
<input type="text" id="name" placeholder="Type something">
```

```javascript
let input = document.getElementById("name");

input.addEventListener("keydown", function(event) {

    console.log("Key Pressed:", event.key);

});
```

**Example Output:**

```text
Key Pressed: A
Key Pressed: Enter
```

<a id="input-events"></a>

## Input Events

`input` event tab trigger hota hai jab input field ki value user ke action se change hoti hai.

```html
<input type="text" id="username" placeholder="Enter your name">

<p id="result"></p>
```

```javascript
let input = document.getElementById("username");

let result = document.getElementById("result");

input.addEventListener("input", function() {

    result.textContent = input.value;

});
```

**Output:**

User jo bhi type karega, woh paragraph mein display hoga.

**Output Screenshot:**

[Add your input event screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="form-events"></a>

## Form Events

Forms par different events trigger ho sakte hain.

| Event | Purpose |
|---|---|
| input | Input value change |
| change | Value commit/change |
| submit | Form submission |
| reset | Form reset |
| focus | Element focused |
| blur | Element focus lose |

**Example:**

```html
<input type="text" id="username" placeholder="Enter name">
```

```javascript
let input = document.getElementById("username");

input.addEventListener("focus", function() {

    console.log("Input Focused");

});

input.addEventListener("blur", function() {

    console.log("Input Focus Removed");

});
```

<a id="submit-event"></a>

## Submit Event

`submit` event form submit hone par trigger hota hai.

```html
<form id="myForm">

    <input type="text" id="username" required>

    <button type="submit">Submit</button>

</form>
```

```javascript
let form = document.getElementById("myForm");

form.addEventListener("submit", function(event) {

    event.preventDefault();

    console.log("Form Submitted!");

});
```

**Output:**

```text
Form Submitted!
```

<a id="event-object"></a>

## Event Object

Event listener ke callback ko event object mil sakta hai.

Ismein event ke baare mein information hoti hai.

Common properties:

| Property | Purpose |
|---|---|
| event.type | Event name |
| event.target | Actual event target |
| event.currentTarget | Current listener element |
| event.key | Pressed keyboard key |
| event.clientX | Mouse X coordinate |
| event.clientY | Mouse Y coordinate |

**Example:**

```html
<button id="btn">Click Me</button>
```

```javascript
let button = document.getElementById("btn");

button.addEventListener("click", function(event) {

    console.log(event.type);

    console.log(event.target);

});
```

**Output:**

```text
click

<button id="btn">Click Me</button>
```

<a id="event-bubbling"></a>

## Event Bubbling

Event Bubbling mein event inner element se start hokar uske parent elements tak propagate karta hai.

**Example:**

```html
<div id="parent">

    <button id="child">Click Me</button>

</div>
```

```javascript
let parent = document.getElementById("parent");

let child = document.getElementById("child");

parent.addEventListener("click", function() {

    console.log("Parent Clicked");

});

child.addEventListener("click", function() {

    console.log("Child Clicked");

});
```

**Output:**

```text
Child Clicked

Parent Clicked
```

<a id="event-capturing"></a>

## Event Capturing

Event Capturing mein event outer parent se inner target ki taraf propagate karta hai.

Capturing activate karne ke liye `addEventListener()` ka third argument `true` set kar sakte hain.

```html
<div id="parent">

    <button id="child">Click Me</button>

</div>
```

```javascript
let parent = document.getElementById("parent");

let child = document.getElementById("child");

parent.addEventListener("click", function() {

    console.log("Parent Capturing");

}, true);

child.addEventListener("click", function() {

    console.log("Child Clicked");

});
```

**Output:**

```text
Parent Capturing

Child Clicked
```

<a id="preventdefault"></a>

## preventDefault()

`preventDefault()` event ki default browser action ko prevent karta hai.

Example: Link open hone ya form submit hone ko prevent karna.

```html
<a href="https://google.com" id="link">Visit Google</a>
```

```javascript
let link = document.getElementById("link");

link.addEventListener("click", function(event) {

    event.preventDefault();

    console.log("Default Action Prevented");

});
```

**Output:**

```text
Default Action Prevented
```

<a id="stoppropagation"></a>

## stopPropagation()

`stopPropagation()` event ko parent ya doosre propagation stages tak jaane se rokta hai.

```html
<div id="parent">

    <button id="child">Click Me</button>

</div>
```

```javascript
let parent = document.getElementById("parent");

let child = document.getElementById("child");

parent.addEventListener("click", function() {

    console.log("Parent Clicked");

});

child.addEventListener("click", function(event) {

    event.stopPropagation();

    console.log("Child Clicked");

});
```

**Output:**

```text
Child Clicked
```

<a id="event-delegation"></a>

## Event Delegation

Event Delegation mein parent element par ek listener lagakar child elements ke events handle kiye jaate hain.

```html
<ul id="list">

    <li>HTML</li>

    <li>CSS</li>

    <li>JavaScript</li>

</ul>
```

```javascript
let list = document.getElementById("list");

list.addEventListener("click", function(event) {

    if (event.target.tagName === "LI") {

        console.log(event.target.textContent);

    }

});
```

**Output:**

List item click karne par uska text console mein display hoga.

**Output Screenshot:**

[Add your event delegation screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

---

# 18. Advanced Functions and Scope

<a id="global-and-local-scope"></a>

## Global and Local Scope

Scope decide karta hai ki variable code ke kis part mein accessible hai.

**Global Scope:**

```javascript
let name = "Sumit";

function showName() {

    console.log(name);

}

showName();
```

**Output:**

```text
Sumit
```

**Local Scope:**

```javascript
function showAge() {

    let age = 19;

    console.log(age);

}

showAge();
```

**Output:**

```text
19
```

<a id="block-scope"></a>

## Block Scope

Block scope `{}` ke andar declare kiye gaye `let` aur `const` variables ko block tak limit karta hai.

```javascript
{

    let age = 19;

    const city = "Delhi";

    console.log(age);

    console.log(city);

}
```

**Output:**

```text
19
Delhi
```

<a id="lexical-scope"></a>

## Lexical Scope

Lexical Scope ka matlab inner function apne outer function ke variables access kar sakta hai.

```javascript
function outer() {

    let name = "Sumit";

    function inner() {

        console.log(name);

    }

    inner();

}

outer();
```

**Output:**

```text
Sumit
```

<a id="closures"></a>

## Closures

Closure tab create hota hai jab inner function apne outer function ke variables ko outer function execute hone ke baad bhi access kar sakta hai.

**Example:**

```javascript
function outer() {

    let count = 0;

    return function() {

        count++;

        console.log(count);

    };

}

let counter = outer();

counter();

counter();

counter();
```

**Output:**

```text
1
2
3
```

**Use Cases:**

- Private variables.
- Counter functions.
- Data encapsulation.
- Function factories.

<a id="higher-order-functions"></a>

## Higher-Order Functions

Higher-Order Function woh function hota hai jo kisi function ko argument ke roop mein receive karta hai ya function return karta hai.

**Example:**

```javascript
function calculate(a, b, operation) {

    return operation(a, b);

}

function add(x, y) {

    return x + y;

}

console.log(calculate(10, 20, add));
```

**Output:**

```text
30
```

<a id="callback-functions"></a>

## Callback Functions

Callback ek function hota hai jo kisi doosre function ko argument ke roop mein pass kiya jaata hai.

```javascript
function greet(name, callback) {

    console.log("Hello " + name);

    callback();

}

function welcome() {

    console.log("Welcome!");

}

greet("Sumit", welcome);
```

**Output:**

```text
Hello Sumit
Welcome!
```

<a id="function-hoisting"></a>

## Function Hoisting

Function Declaration ko uski declaration se pehle call kiya ja sakta hai.

```javascript
greet();

function greet() {

    console.log("Hello World");

}
```

**Output:**

```text
Hello World
```

**Important:** Function expressions aur arrow functions ko variable initialization se pehle call nahi karna chahiye.

<a id="variable-hoisting"></a>

## Variable Hoisting

JavaScript variable declarations ko scope ke top par process karta hai. Is behaviour ko Hoisting kehte hain.

**var Example:**

```javascript
console.log(age);

var age = 19;
```

**Output:**

```text
undefined
```

**let Example:**

```javascript
console.log(age);

let age = 19;
```

**Output:**

```text
ReferenceError
```

`let` aur `const` declarations Temporal Dead Zone mein rehti hain jab tak declaration execute nahi hoti.

<a id="call"></a>

## call()

`call()` kisi function ko specified `this` value aur individual arguments ke saath call karta hai.

```javascript
function greet(city) {

    console.log(this.name + " lives in " + city);

}

let user = {
    name: "Sumit"
};

greet.call(user, "Delhi");
```

**Output:**

```text
Sumit lives in Delhi
```

<a id="apply"></a>

## apply()

`apply()` bhi function ko specified `this` value ke saath call karta hai, lekin arguments array-like form mein pass karta hai.

```javascript
function add(a, b) {

    console.log(a + b);

}

add.apply(null, [10, 20]);
```

**Output:**

```text
30
```

<a id="bind"></a>

## bind()

`bind()` ek new function return karta hai jisme `this` value aur optionally kuch arguments fix kiye ja sakte hain.

```javascript
let user = {
    name: "Sumit"
};

function greet() {

    console.log("Hello " + this.name);

}

let newFunction = greet.bind(user);

newFunction();
```

**Output:**

```text
Hello Sumit
```

<a id="iife"></a>

## IIFE

IIFE ka full form Immediately Invoked Function Expression hai.

Yeh function define hote hi immediately execute ho jaata hai.

```javascript
(function() {

    console.log("IIFE Executed");

})();
```

**Output:**

```text
IIFE Executed
```

<a id="pure-functions"></a>

## Pure Functions

Pure Function same input ke liye same output return karta hai aur external state ko modify nahi karta.

```javascript
function add(a, b) {

    return a + b;

}

console.log(add(10, 20));

console.log(add(10, 20));
```

**Output:**

```text
30
30
```

<a id="recursion-revision"></a>

## Recursion Revision

Recursion mein function apne aap ko call karta hai.

```javascript
function factorial(number) {

    if (number <= 1) {

        return 1;

    }

    return number * factorial(number - 1);

}

console.log(factorial(5));
```

**Output:**

```text
120
```

---

# 19. ES6+ Features

<a id="what-is-es6"></a>

## What is ES6?

ES6 ka full form ECMAScript 2015 hai.

ES6 JavaScript ka major update tha jisme modern JavaScript features introduce hue.

Important ES6 features:

- let and const.
- Arrow Functions.
- Template Literals.
- Destructuring.
- Spread Operator.
- Rest Parameters.
- Classes.
- Modules.
- Promises.
- Map and Set.

<a id="let-and-const"></a>

## let and const

`let` aur `const` modern JavaScript mein variables declare karne ke liye use hote hain.

```javascript
let age = 19;

age = 20;

const country = "India";

console.log(age);

console.log(country);
```

**Output:**

```text
20
India
```

<a id="arrow-functions"></a>

## Arrow Functions

Arrow Functions shorter function syntax provide karte hain.

```javascript
const add = (a, b) => a + b;

console.log(add(10, 20));
```

**Output:**

```text
30
```

<a id="template-literals"></a>

## Template Literals

Template Literals backticks ke through strings create karte hain.

```javascript
let name = "Sumit";

let age = 19;

console.log(`My name is ${name}. My age is ${age}.`);
```

**Output:**

```text
My name is Sumit. My age is 19.
```

<a id="default-parameters"></a>

## Default Parameters

Function mein default values provide karne ke liye use hote hain.

```javascript
function greet(name = "Guest") {

    console.log("Hello " + name);

}

greet();

greet("Sumit");
```

**Output:**

```text
Hello Guest
Hello Sumit
```

<a id="destructuring"></a>

## Destructuring

Destructuring arrays aur objects ki values ko separate variables mein extract karta hai.

**Array Destructuring:**

```javascript
let colors = ["Red", "Green", "Blue"];

let [first, second, third] = colors;

console.log(first);

console.log(second);
```

**Output:**

```text
Red
Green
```

**Object Destructuring:**

```javascript
let user = {
    name: "Sumit",
    age: 19
};

let { name, age } = user;

console.log(name);

console.log(age);
```

**Output:**

```text
Sumit
19
```

<a id="spread-operator"></a>

## Spread Operator

Spread Operator (`...`) array ya object ki values ko expand karta hai.

```javascript
let first = [10, 20];

let second = [30, 40];

let result = [...first, ...second];

console.log(result);
```

**Output:**

```text
[10, 20, 30, 40]
```

<a id="rest-parameters"></a>

## Rest Parameters

Rest Parameter (`...`) multiple arguments ko ek array mein collect karta hai.

```javascript
function add(...numbers) {

    return numbers.reduce((total, number) => total + number, 0);

}

console.log(add(10, 20, 30, 40));
```

**Output:**

```text
100
```

**Difference:**

| Spread | Rest |
|---|---|
| Values expand karta hai | Values collect karta hai |
| Array/object values spread | Arguments array mein collect |

<a id="enhanced-object-literals"></a>

## Enhanced Object Literals

Object Literals mein shorthand property aur method syntax use kar sakte hain.

```javascript
let name = "Sumit";

let age = 19;

let user = {

    name,

    age,

    greet() {

        console.log("Hello " + this.name);

    }

};

user.greet();
```

**Output:**

```text
Hello Sumit
```

<a id="forof"></a>

## for...of

`for...of` iterable values ko one by one access karta hai.

```javascript
let skills = ["HTML", "CSS", "JavaScript"];

for (let skill of skills) {

    console.log(skill);

}
```

**Output:**

```text
HTML
CSS
JavaScript
```

<a id="map"></a>

## Map

Map ek collection hai jo key-value pairs store karta hai.

Map mein keys kisi bhi data type ki ho sakti hain.

**Methods:**

| Method | Purpose |
|---|---|
| set() | Key-value add |
| get() | Value access |
| has() | Key check |
| delete() | Entry remove |
| clear() | All entries remove |
| size | Total entries |

**Example:**

```javascript
let student = new Map();

student.set("name", "Sumit");

student.set("age", 19);

console.log(student.get("name"));

console.log(student.size);
```

**Output:**

```text
Sumit
2
```

<a id="set"></a>

## Set

Set unique values ka collection hota hai. Duplicate values automatically ignore hoti hain.

**Methods:**

| Method | Purpose |
|---|---|
| add() | Value add |
| has() | Value check |
| delete() | Value remove |
| clear() | All values remove |
| size | Total values |

**Example:**

```javascript
let numbers = new Set();

numbers.add(10);

numbers.add(20);

numbers.add(10);

console.log(numbers);
```

**Output:**

```text
Set(2) {10, 20}
```

<a id="symbol"></a>

## Symbol

Symbol unique primitive value create karta hai.

```javascript
let id1 = Symbol("id");

let id2 = Symbol("id");

console.log(id1 === id2);
```

**Output:**

```text
false
```

<a id="classes"></a>

## Classes

Class objects create karne ke liye ek template provide karti hai.

```javascript
class Student {

    constructor(name, age) {

        this.name = name;

        this.age = age;

    }

    greet() {

        console.log("Hello " + this.name);

    }

}

let student1 = new Student("Sumit", 19);

student1.greet();
```

**Output:**

```text
Hello Sumit
```

<a id="inheritance"></a>

## Inheritance

Inheritance mein ek class doosri class ki properties aur methods inherit kar sakti hai.

`extends` keyword inheritance ke liye use hota hai.

```javascript
class Animal {

    speak() {

        console.log("Animal makes a sound");

    }

}

class Dog extends Animal {

    bark() {

        console.log("Dog barks");

    }

}

let dog = new Dog();

dog.speak();

dog.bark();
```

**Output:**

```text
Animal makes a sound
Dog barks
```

<a id="getters-and-setters"></a>

## Getters and Setters

Getter property ko read karne ke liye aur Setter property ko update karne ke liye use hota hai.

```javascript
class Student {

    constructor(name) {

        this._name = name;

    }

    get name() {

        return this._name;

    }

    set name(value) {

        this._name = value;

    }

}

let student = new Student("Sumit");

console.log(student.name);

student.name = "Rahul";

console.log(student.name);
```

**Output:**

```text
Sumit
Rahul
```

<a id="optional-chaining"></a>

## Optional Chaining

`?.` nested properties ko safely access karta hai.

```javascript
let user = {};

console.log(user.address?.city);
```

**Output:**

```text
undefined
```

<a id="nullish-coalescing"></a>

## Nullish Coalescing

`??` right-side value tab return karta hai jab left-side value `null` ya `undefined` ho.

```javascript
let username = null;

console.log(username ?? "Guest");
```

**Output:**

```text
Guest
```

---

# 20. JavaScript Date and Time

<a id="date-object"></a>

## Date Object

JavaScript ka Date object date aur time ke saath work karne ke liye use hota hai.

<a id="creating-dates"></a>

## Creating Dates

Date object create karne ke liye `new Date()` use hota hai.

```javascript
let today = new Date();

console.log(today);
```

**Output:**

```text
Current date and time
```

<a id="getdate"></a>

## getDate()

`getDate()` month ki date return karta hai, generally 1 se 31 ke beech.

```javascript
let today = new Date();

console.log(today.getDate());
```

**Output:**

Current month ki date.

<a id="getday"></a>

## getDay()

`getDay()` week ka day number return karta hai.

| Number | Day |
|---|---|
| 0 | Sunday |
| 1 | Monday |
| 2 | Tuesday |
| 3 | Wednesday |
| 4 | Thursday |
| 5 | Friday |
| 6 | Saturday |

```javascript
let today = new Date();

console.log(today.getDay());
```

<a id="getmonth"></a>

## getMonth()

`getMonth()` month ka index return karta hai.

January = 0 aur December = 11.

```javascript
let today = new Date();

console.log(today.getMonth());
```

<a id="getfullyear"></a>

## getFullYear()

`getFullYear()` complete year return karta hai.

```javascript
let today = new Date();

console.log(today.getFullYear());
```

**Output Example:**

```text
2026
```

<a id="gethours-and-getminutes"></a>

## getHours() and getMinutes()

`getHours()` current hour return karta hai.

`getMinutes()` current minutes return karta hai.

```javascript
let today = new Date();

console.log(today.getHours());

console.log(today.getMinutes());
```

**Output:**

Current local hour and minutes.

<a id="setdate-and-setmonth"></a>

## setDate() and setMonth()

`setDate()` Date object ki day-of-month value update karta hai.

`setMonth()` month update karta hai.

```javascript
let date = new Date();

date.setDate(15);

date.setMonth(5);

console.log(date);
```

**Output:**

Date object ka month June aur date 15 set ho jayegi, year aur time preserve rahenge.

<a id="date-formatting"></a>

## Date Formatting

Date ko readable format mein display karne ke liye different methods available hain.

| Method | Purpose |
|---|---|
| toDateString() | Readable date |
| toTimeString() | Readable time |
| toISOString() | ISO date format |
| toLocaleDateString() | Local date format |
| toLocaleTimeString() | Local time format |
| toLocaleString() | Local date and time |

**Example:**

```javascript
let today = new Date();

console.log(today.toDateString());

console.log(today.toLocaleDateString("en-IN"));

console.log(today.toLocaleTimeString("en-IN"));
```

**Output:**

Current date aur local time ke according output milega.

<a id="datenow"></a>

## Date.now()

`Date.now()` current time ko milliseconds mein return karta hai, Unix Epoch se.

```javascript
console.log(Date.now());
```

**Output Example:**

```text
1795500000000
```

---

# 21. JavaScript Error Handling

<a id="what-are-errors"></a>

## What are Errors?

Errors woh problems hoti hain jo code ke execution ko affect karti hain.

Error handling ki help se errors ko handle karke application ko properly manage kar sakte hain.

<a id="syntax-errors"></a>

## Syntax Errors

Jab code JavaScript syntax rules follow nahi karta, toh Syntax Error aa sakta hai.

```javascript
// Incorrect Syntax

if (true {
    console.log("Hello");
}
```

**Output:**

```text
SyntaxError
```

<a id="reference-errors"></a>

## Reference Errors

Jab kisi unavailable ya undeclared variable ko access kiya jaata hai, ReferenceError aa sakta hai.

```javascript
console.log(userName);
```

**Output:**

```text
ReferenceError
```

<a id="type-errors"></a>

## Type Errors

Jab operation kisi value ke liye valid nahi hota, TypeError aa sakta hai.

```javascript
let user = null;

console.log(user.name);
```

**Output:**

```text
TypeError
```

<a id="try-catch"></a>

## try...catch

`try...catch` ka use errors handle karne ke liye hota hai.

- `try` mein risky code likhte hain.
- `catch` mein error handle karte hain.

```javascript
try {

    let result = userName;

    console.log(result);

} catch (error) {

    console.log("An error occurred");

}
```

**Output:**

```text
An error occurred
```

<a id="finally"></a>

## finally

`finally` block try ya catch ke baad execute hota hai.

```javascript
try {

    console.log("Try Block");

} catch (error) {

    console.log("Catch Block");

} finally {

    console.log("Finally Block");

}
```

**Output:**

```text
Try Block
Finally Block
```

<a id="throw"></a>

## throw

`throw` keyword custom error throw karne ke liye use hota hai.

```javascript
let age = 15;

if (age < 18) {

    throw new Error("You are not eligible");

}
```

**Output:**

```text
Error: You are not eligible
```

<a id="custom-errors"></a>

## Custom Errors

Custom error ka use apne according error message create karne ke liye hota hai.

```javascript
function checkAge(age) {

    if (age < 18) {

        throw new Error("Age must be 18 or above");

    }

    return "Eligible";

}

try {

    console.log(checkAge(15));

} catch (error) {

    console.log(error.message);

}
```

**Output:**

```text
Age must be 18 or above
```

<a id="error-object"></a>

## Error Object

Error object error ki information provide karta hai.

Common properties:

| Property | Purpose |
|---|---|
| name | Error name |
| message | Error message |
| stack | Stack trace |

```javascript
try {

    throw new Error("Something went wrong");

} catch (error) {

    console.log(error.name);

    console.log(error.message);

}
```

**Output:**

```text
Error
Something went wrong
```

---

# 22. JavaScript JSON

<a id="what-is-json"></a>

## What is JSON?

JSON ka full form JavaScript Object Notation hai.

JSON ek lightweight data format hai jo data exchange aur storage ke liye use hota hai.

JSON ka use frontend aur backend ke beech data transfer karne mein common hai.

<a id="json-syntax"></a>

## JSON Syntax

JSON data key-value pairs ke form mein hota hai.

**Example:**

```json
{
    "name": "Sumit",
    "age": 19,
    "city": "Delhi"
}
```

**Important JSON Rules:**

- Keys double quotes mein hoti hain.
- String values double quotes mein hoti hain.
- JSON mein comments allowed nahi hain.
- Trailing commas allowed nahi hain.
- JSON mein functions allowed nahi hain.

<a id="json-stringify"></a>

## JSON.stringify()

`JSON.stringify()` JavaScript value ko JSON string mein convert karta hai.

```javascript
let student = {

    name: "Sumit",

    age: 19

};

let result = JSON.stringify(student);

console.log(result);

console.log(typeof result);
```

**Output:**

```text
{"name":"Sumit","age":19}

string
```

<a id="json-parse"></a>

## JSON.parse()

`JSON.parse()` valid JSON string ko JavaScript value mein convert karta hai.

```javascript
let data = '{"name":"Sumit","age":19}';

let student = JSON.parse(data);

console.log(student.name);

console.log(student.age);
```

**Output:**

```text
Sumit
19
```

<a id="json-and-javascript-objects"></a>

## JSON and JavaScript Objects

| JavaScript Object | JSON |
|---|---|
| Keys quotes ke bina bhi ho sakti hain | Keys double quotes mein hoti hain |
| Functions allowed hain | Functions allowed nahi hain |
| Undefined values possible hain | Undefined supported nahi hai |
| JavaScript runtime value | Text-based data format |

<a id="json-data-types"></a>

## JSON Data Types

JSON supported data types:

- String
- Number
- Boolean
- Object
- Array
- Null

**Example:**

```json
{
    "name": "Sumit",
    "age": 19,
    "isStudent": true,
    "skills": ["HTML", "CSS", "JavaScript"],
    "address": null
}
```

<a id="json-limitations"></a>

## JSON Limitations

- JSON comments support nahi karta.
- JSON functions store nahi karta.
- JSON undefined value support nahi karta.
- JSON mein circular references directly represent nahi kiye ja sakte.

---

# 23. JavaScript Asynchronous Programming

<a id="synchronous-javascript"></a>

## Synchronous JavaScript

Synchronous JavaScript mein instructions generally one by one execute hoti hain.

Ek task complete hone ke baad next task execute hota hai.

```javascript
console.log("First");

console.log("Second");

console.log("Third");
```

**Output:**

```text
First
Second
Third
```

<a id="asynchronous-javascript"></a>

## Asynchronous JavaScript

Asynchronous JavaScript ki help se kuch tasks complete hone ka wait kiye bina doosra code execute ho sakta hai.

Examples:

- Timer.
- Network requests.
- File operations in supported environments.
- User events.

```javascript
console.log("First");

setTimeout(function() {

    console.log("Second");

}, 2000);

console.log("Third");
```

**Output:**

```text
First
Third
Second
```

<a id="call-stack"></a>

## Call Stack

Call Stack ek mechanism hai jo function execution ko manage karta hai.

JavaScript jab function call karti hai, toh function ka execution context stack mein add hota hai.

```javascript
function first() {

    second();

}

function second() {

    console.log("Second Function");

}

first();
```

**Output:**

```text
Second Function
```

<a id="web-apis"></a>

## Web APIs

Web APIs browser ki taraf se provide ki jaane wali capabilities hain.

Examples:

- setTimeout()
- DOM APIs
- Fetch API
- Geolocation API
- Local Storage API

JavaScript engine in APIs ke through browser environment ke saath interact karta hai.

<a id="callback-queue"></a>

## Callback Queue

Callback Queue mein asynchronous callbacks wait kar sakte hain jab tak Call Stack empty nahi ho jaata.

Example: `setTimeout()` ka callback timer complete hone ke baad task queue mein schedule ho sakta hai.

<a id="event-loop"></a>

## Event Loop

Event Loop Call Stack aur queued tasks ke beech coordination karta hai.

Yeh check karta hai ki Call Stack empty hai ya nahi aur eligible queued callbacks ko execute hone deta hai.

**Basic Flow:**

```text
JavaScript Code
      |
      v
  Call Stack
      |
      v
 Browser APIs
      |
      v
 Task Queue
      |
      v
  Event Loop
      |
      v
  Call Stack
```

**Important:** Promise callbacks jaise microtasks generally timer callbacks jaise tasks se pehle process hote hain jab current JavaScript execution complete hota hai.

<a id="settimeout"></a>

## setTimeout()

`setTimeout()` specified delay ke baad callback ko schedule karta hai.

```javascript
setTimeout(function() {

    console.log("Hello after 2 seconds");

}, 2000);
```

**Output:**

```text
Hello after 2 seconds
```

<a id="setinterval"></a>

## setInterval()

`setInterval()` specified interval ke baad callback ko repeatedly schedule karta hai.

```javascript
let count = 1;

let timer = setInterval(function() {

    console.log(count);

    count++;

}, 1000);
```

**Output:**

```text
1
2
3
4
...
```

<a id="cleartimeout"></a>

## clearTimeout()

`clearTimeout()` pending timeout ko cancel karta hai.

```javascript
let timer = setTimeout(function() {

    console.log("Hello");

}, 3000);

clearTimeout(timer);
```

**Output:**

```text
No output
```

<a id="clearinterval"></a>

## clearInterval()

`clearInterval()` interval ko stop karta hai.

```javascript
let count = 1;

let timer = setInterval(function() {

    console.log(count);

    count++;

    if (count > 5) {

        clearInterval(timer);

    }

}, 1000);
```

**Output:**

```text
1
2
3
4
5
```

---

# 24. Promises and Async/Await

<a id="what-are-promises"></a>

## What are Promises?

Promise JavaScript object hai jo asynchronous operation ke eventual result ko represent karta hai.

Promise future mein successful result ya failure provide kar sakta hai.

<a id="promise-states"></a>

## Promise States

Promise ki three states hoti hain.

| State | Meaning |
|---|---|
| Pending | Operation complete nahi hua |
| Fulfilled | Operation successful |
| Rejected | Operation failed |

<a id="creating-a-promise"></a>

## Creating a Promise

Promise create karne ke liye `new Promise()` use hota hai.

Ismein executor function ko `resolve` aur `reject` parameters milte hain.

```javascript
let promise = new Promise(function(resolve, reject) {

    let success = true;

    if (success) {

        resolve("Task Completed");

    } else {

        reject("Task Failed");

    }

});
```

<a id="then"></a>

## then()

`then()` fulfilled Promise ke result ko handle karta hai.

```javascript
let promise = Promise.resolve("Success!");

promise.then(function(result) {

    console.log(result);

});
```

**Output:**

```text
Success!
```

<a id="catch"></a>

## catch()

`catch()` rejected Promise ke error ko handle karta hai.

```javascript
let promise = Promise.reject("Something went wrong");

promise.catch(function(error) {

    console.log(error);

});
```

**Output:**

```text
Something went wrong
```

<a id="finally"></a>

## finally()

`finally()` Promise settle hone ke baad execute hota hai, chahe fulfilled ho ya rejected.

```javascript
Promise.resolve("Success")

    .then(result => console.log(result))

    .finally(() => console.log("Process Finished"));
```

**Output:**

```text
Success
Process Finished
```

<a id="promise-chaining"></a>

## Promise Chaining

Ek Promise ke result ko next `.then()` mein pass karna Promise Chaining kehlata hai.

```javascript
Promise.resolve(10)

    .then(number => number * 2)

    .then(number => number + 5)

    .then(result => console.log(result));
```

**Output:**

```text
25
```

<a id="promise-all"></a>

## Promise.all()

`Promise.all()` multiple Promises ko combine karta hai.

Saare Promises fulfilled hone par results ka array return karta hai. Kisi Promise ke reject hone par combined Promise reject ho jaata hai.

```javascript
let promise1 = Promise.resolve("HTML");

let promise2 = Promise.resolve("CSS");

let promise3 = Promise.resolve("JavaScript");

Promise.all([promise1, promise2, promise3])

    .then(result => console.log(result))

    .catch(error => console.log(error));
```

**Output:**

```text
["HTML", "CSS", "JavaScript"]
```

<a id="promise-allsettled"></a>

## Promise.allSettled()

`Promise.allSettled()` saare Promises settle hone ka wait karta hai aur har Promise ka status aur result return karta hai.

```javascript
let promises = [

    Promise.resolve("Success"),

    Promise.reject("Failed")

];

Promise.allSettled(promises).then(result => {

    console.log(result);

});
```

**Output:**

```text
[
    { status: "fulfilled", value: "Success" },
    { status: "rejected", reason: "Failed" }
]
```

<a id="promise-race"></a>

## Promise.race()

`Promise.race()` sabse pehle settle hone wale Promise ka result return karta hai.

```javascript
let promise1 = new Promise(resolve => {

    setTimeout(() => resolve("First"), 1000);

});

let promise2 = new Promise(resolve => {

    setTimeout(() => resolve("Second"), 2000);

});

Promise.race([promise1, promise2])

    .then(result => console.log(result));
```

**Output:**

```text
First
```

<a id="promise-any"></a>

## Promise.any()

`Promise.any()` first fulfilled Promise ka result return karta hai.

```javascript
let promises = [

    Promise.reject("Error"),

    Promise.resolve("Success"),

    Promise.resolve("Another Success")

];

Promise.any(promises).then(result => {

    console.log(result);

});
```

**Output:**

```text
Success
```

<a id="async-keyword"></a>

## async Keyword

`async` keyword function ko Async Function banata hai.

Async Function hamesha Promise return karta hai.

```javascript
async function greet() {

    return "Hello JavaScript";

}

greet().then(result => console.log(result));
```

**Output:**

```text
Hello JavaScript
```

<a id="await-keyword"></a>

## await Keyword

`await` kisi Promise ke settle hone tak async function ke execution ko pause karta hai.

```javascript
async function getData() {

    let result = await Promise.resolve("Data Received");

    console.log(result);

}

getData();
```

**Output:**

```text
Data Received
```

<a id="error-handling-with-async-await"></a>

## Error Handling with Async/Await

Async/Await ke saath errors handle karne ke liye `try...catch` use karte hain.

```javascript
async function getData() {

    try {

        let result = await Promise.reject("Request Failed");

        console.log(result);

    } catch (error) {

        console.log(error);

    }

}

getData();
```

**Output:**

```text
Request Failed
```

---

# 25. JavaScript Browser APIs

<a id="what-are-browser-apis"></a>

## What are Browser APIs?

Browser APIs browser environment ki taraf se provide ki jaane wali functionalities hain.

JavaScript in APIs ki help se browser features access kar sakti hai.

Examples:

- Window API.
- Geolocation API.
- Clipboard API.
- Fetch API.
- History API.
- Storage API.

<a id="window-object"></a>

## Window Object

`window` browser ke current window ya tab ko represent karta hai.

Common properties and methods:

| Property / Method | Purpose |
|---|---|
| innerWidth | Viewport width |
| innerHeight | Viewport height |
| location | Current URL information |
| history | Browser history |
| alert() | Alert popup |
| confirm() | Confirmation popup |
| setTimeout() | Delayed callback |
| setInterval() | Repeated callback |
| open() | New browsing context open karne ki request |

**Example:**

```javascript
console.log(window.innerWidth);

console.log(window.innerHeight);
```

**Output:**

Browser viewport ki width aur height.

<a id="navigator-object"></a>

## Navigator Object

`navigator` browser environment ke baare mein information aur capabilities provide karta hai.

```javascript
console.log(navigator.language);

console.log(navigator.onLine);
```

**Output:**

Browser language aur online status.

**Important:** User-Agent information ko exact browser identification ya security decision ke liye reliable proof nahi maana jaana chahiye.

<a id="location-object"></a>

## Location Object

`location` current webpage ke URL ke baare mein information provide karta hai.

| Property / Method | Purpose |
|---|---|
| href | Complete URL |
| hostname | Domain name |
| pathname | URL path |
| protocol | URL protocol |
| search | Query string |
| hash | URL fragment |
| assign() | New URL par navigate |
| reload() | Page reload |
| replace() | Current history entry replace |

**Example:**

```javascript
console.log(location.href);

console.log(location.hostname);

console.log(location.pathname);
```

<a id="history-object"></a>

## History Object

`history` browser session ki navigation history ke saath work karta hai.

| Method | Purpose |
|---|---|
| back() | Previous page |
| forward() | Next page |
| go() | History mein move |
| pushState() | History entry add |
| replaceState() | Current entry replace |

**Example:**

```javascript
history.back();
```

**Output:**

Browser previous page par navigate karega.

<a id="screen-object"></a>

## Screen Object

`screen` object display screen ki information provide karta hai.

```javascript
console.log(screen.width);

console.log(screen.height);

console.log(screen.availWidth);

console.log(screen.availHeight);
```

**Output:**

Screen width aur height information.

<a id="geolocation-api"></a>

## Geolocation API

Geolocation API user ki permission ke baad device location access karne ki facility provide karti hai.

```javascript
navigator.geolocation.getCurrentPosition(

    function(position) {

        console.log(position.coords.latitude);

        console.log(position.coords.longitude);

    },

    function(error) {

        console.log(error.message);

    }

);
```

**Output:**

User permission allow karne par latitude aur longitude mil sakte hain.

**Important:** Geolocation ke liye permission aur secure context (generally HTTPS ya localhost) required hota hai.

<a id="clipboard-api"></a>

## Clipboard API

Clipboard API text ko clipboard mein copy karne ke liye use hoti hai.

```javascript
async function copyText() {

    try {

        await navigator.clipboard.writeText("Hello JavaScript");

        console.log("Text Copied!");

    } catch (error) {

        console.log("Copy Failed");

    }

}

copyText();
```

**Output:**

```text
Text Copied!
```

**Important:** Clipboard access browser permission aur secure context par depend karta hai.

<a id="fetch-api"></a>

## Fetch API

Fetch API network requests send karne aur server se data receive karne ke liye use hoti hai.

```javascript
fetch("https://jsonplaceholder.typicode.com/users/1")

    .then(response => {

        if (!response.ok) {

            throw new Error("Request Failed");

        }

        return response.json();

    })

    .then(data => {

        console.log(data);

    })

    .catch(error => {

        console.log(error.message);

    });
```

**Example Output:**

```text
{
    id: 1,
    name: "Leanne Graham",
    username: "Bret",
    email: "..."
}
```

**Important:**

- `fetch()` Promise return karta hai.
- `response.json()` response body ko parse karta hai.
- HTTP error status (jaise 404) par Fetch Promise automatically reject nahi hota. `response.ok` check karna chahiye.

<a id="url-api"></a>

## URL API

URL API URL ko parse aur modify karne ke liye use hoti hai.

```javascript
let url = new URL("https://example.com/products?id=10");

console.log(url.hostname);

console.log(url.pathname);

console.log(url.searchParams.get("id"));
```

**Output:**

```text
example.com
/products
10
```

---

# 26. JavaScript Modules

<a id="what-are-modules"></a>

## What are Modules?

JavaScript Modules code ko separate files mein organize karne ka system provide karte hain.

Modules ki help se code ko reuse aur maintain karna easy hota hai.

<a id="export"></a>

## Export

`export` keyword ka use kisi variable, function ya class ko doosri module file ke liye available karne ke liye hota hai.

**math.js**

```javascript
export const pi = 3.14;
```

<a id="named-export"></a>

## Named Export

Named Export mein multiple values ko export kar sakte hain.

**math.js**

```javascript
export const add = (a, b) => a + b;

export const subtract = (a, b) => a - b;
```

<a id="default-export"></a>

## Default Export

Ek module mein ek default export ho sakta hai.

**greet.js**

```javascript
export default function greet() {

    console.log("Hello JavaScript");

}
```

<a id="import"></a>

## Import

`import` keyword exported values ko doosri file mein use karne ke liye hota hai.

**math.js**

```javascript
export function add(a, b) {

    return a + b;

}
```

**script.js**

```javascript
import { add } from "./math.js";

console.log(add(10, 20));
```

**Output:**

```text
30
```

<a id="import-renaming"></a>

## Import Renaming

`as` keyword ke through imported name change kar sakte hain.

```javascript
import { add as sum } from "./math.js";

console.log(sum(10, 20));
```

**Output:**

```text
30
```

<a id="import-all"></a>

## Import All

`* as` ka use karke module ke named exports ko ek namespace object mein import kar sakte hain.

```javascript
import * as math from "./math.js";

console.log(math.add(10, 20));
```

**Output:**

```text
30
```

<a id="dynamic-import"></a>

## Dynamic Import

`import()` function ke through module ko dynamically load kar sakte hain.

```javascript
async function loadModule() {

    const module = await import("./math.js");

    console.log(module.add(10, 20));

}

loadModule();
```

**Output:**

```text
30
```

<a id="module-script"></a>

## Module Script

Browser mein JavaScript module use karne ke liye script tag mein `type="module"` use karte hain.

**index.html**

```html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript Modules</title>
</head>
<body>

    <h1>JavaScript Modules</h1>

    <script type="module" src="script.js"></script>

</body>
</html>
```

**Important:**

- Modules automatically strict mode mein run hote hain.
- Modules apna separate scope rakhte hain.
- Browser modules ko generally HTTP server ya localhost se run karna chahiye.

---

# 27. JavaScript Storage

<a id="what-is-browser-storage"></a>

## What is Browser Storage?

Browser Storage ka use browser mein data store karne ke liye hota hai.

JavaScript mein commonly:

1. localStorage
2. sessionStorage
3. Cookies

<a id="localstorage"></a>

## localStorage

`localStorage` browser mein key-value data store karta hai.

Data browser sessions ke baad bhi generally available rehta hai jab tak remove na kiya jaaye.

<a id="setitem"></a>

## setItem()

`setItem()` localStorage mein data store karta hai.

```javascript
localStorage.setItem("username", "Sumit");
```

**Output:**

```text
Data stored in localStorage.
```

<a id="getitem"></a>

## getItem()

`getItem()` stored data retrieve karta hai.

```javascript
let name = localStorage.getItem("username");

console.log(name);
```

**Output:**

```text
Sumit
```

<a id="removeitem"></a>

## removeItem()

`removeItem()` specified key ka data remove karta hai.

```javascript
localStorage.removeItem("username");
```

**Output:**

```text
username removed.
```

<a id="clear"></a>

## clear()

`clear()` current origin ke localStorage ke saare entries remove karta hai.

```javascript
localStorage.clear();
```

**Output:**

```text
All localStorage data cleared.
```

<a id="sessionstorage"></a>

## sessionStorage

`sessionStorage` data ko current tab ki page session ke liye store karta hai.

```javascript
sessionStorage.setItem("user", "Sumit");

let user = sessionStorage.getItem("user");

console.log(user);
```

**Output:**

```text
Sumit
```

<a id="cookies"></a>

## Cookies

Cookies small data values hoti hain jo browser website ke liye store kar sakta hai.

Cookies ko JavaScript se `document.cookie` ke through read aur set kar sakte hain, subject to cookie restrictions.

**Example:**

```javascript
document.cookie = "username=Sumit; max-age=3600; path=/";
```

**Output:**

```text
Cookie stored.
```

**Important:**

- Cookies server requests ke saath send ho sakti hain.
- HttpOnly cookies ko JavaScript se access nahi kiya ja sakta.
- Sensitive information ko plain text cookie ya localStorage mein store nahi karna chahiye.

<a id="storing-objects-in-storage"></a>

## Storing Objects in Storage

localStorage aur sessionStorage string values store karte hain.

Objects ko store karne ke liye `JSON.stringify()` use karte hain.

**Example:**

```javascript
let user = {

    name: "Sumit",

    age: 19

};

localStorage.setItem("user", JSON.stringify(user));

let storedUser = JSON.parse(localStorage.getItem("user"));

console.log(storedUser.name);
```

**Output:**

```text
Sumit
```

---

# 28. JavaScript Best Practices

<a id="clean-code"></a>

## Clean Code

Clean Code ka matlab readable, understandable aur maintainable code likhna hai.

**Bad Example:**

```javascript
let x = 100;

let y = 200;

let z = x + y;
```

**Better Example:**

```javascript
let productPrice = 100;

let deliveryCharge = 200;

let totalAmount = productPrice + deliveryCharge;
```

<a id="variable-naming"></a>

## Variable Naming

Meaningful variable names use karne chahiye.

**Good Examples:**

```javascript
let firstName = "Sumit";

let totalPrice = 500;

let isLoggedIn = true;
```

<a id="use-const-and-let"></a>

## Use const and let

Modern JavaScript mein `const` aur `let` prefer karo.

```javascript
const country = "India";

let age = 19;

age = 20;
```

<a id="strict-equality"></a>

## Strict Equality

Comparison ke liye generally `===` aur `!==` use karo.

```javascript
console.log(5 === "5");

console.log(10 !== 20);
```

**Output:**

```text
false
true
```

<a id="avoid-global-variables"></a>

## Avoid Global Variables

Unnecessary global variables avoid karne chahiye.

Variables ko required scope ke andar declare karo.

```javascript
function calculate() {

    const price = 100;

    const quantity = 2;

    return price * quantity;

}

console.log(calculate());
```

**Output:**

```text
200
```

<a id="error-handling"></a>

## Error Handling

Important operations ke liye proper error handling use karo.

```javascript
try {

    let data = JSON.parse('{"name":"Sumit"}');

    console.log(data.name);

} catch (error) {

    console.log("Invalid JSON");

}
```

**Output:**

```text
Sumit
```

<a id="code-reusability"></a>

## Code Reusability

Repeated code ko functions mein organize karo.

```javascript
function calculateTotal(price, quantity) {

    return price * quantity;

}

console.log(calculateTotal(100, 2));

console.log(calculateTotal(200, 3));
```

**Output:**

```text
200
600
```

<a id="performance"></a>

## Performance

Performance improve karne ke liye:

- Unnecessary DOM updates avoid karo.
- Repeated calculations ko optimize karo.
- Large lists mein event delegation use karo.
- Unnecessary timers avoid karo.
- Large tasks ko efficiently manage karo.

<a id="security"></a>

## Security

JavaScript applications mein security important hai.

- User input validate karo.
- Untrusted HTML ko `innerHTML` mein directly insert mat karo.
- Sensitive information expose mat karo.
- API keys ko frontend code mein secret mat samjho.
- Server-side validation bhi karo.
- HTTPS use karo.

<a id="debugging"></a>

## Debugging

Debugging ka matlab code mein errors identify aur fix karna hai.

Useful tools:

| Tool | Purpose |
|---|---|
| console.log() | Values check |
| console.table() | Tabular output |
| console.error() | Error display |
| debugger | Execution pause |
| Breakpoints | Specific line par pause |
| DevTools | Browser debugging |

**Example:**

```javascript
let price = 500;

debugger;

let quantity = 2;

console.log(price * quantity);
```

**Output:**

```text
1000
```

---

# 29. JavaScript Practical Projects

Is section mein HTML, CSS aur JavaScript ko combine karke practical projects banaye jayenge.

<a id="counter-app"></a>

## Practical Project 1 — Counter App

**Project Purpose:**

Counter App mein number increase, decrease aur reset kar sakte hain.

**Folder Structure:**

```text
counter-app/
│
├── index.html
├── style.css
└── script.js
```

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Counter App</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">

        <h1>Counter App</h1>

        <h2 id="count">0</h2>

        <button id="decrease">Decrease</button>

        <button id="reset">Reset</button>

        <button id="increase">Increase</button>

    </div>

    <script src="script.js"></script>

</body>
</html>
```

**style.css**

```css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f2f2f2;
}

.container {
    margin-top: 100px;
}

h2 {
    font-size: 50px;
}

button {
    padding: 12px 20px;
    margin: 5px;
    cursor: pointer;
}
```

**script.js**

```javascript
let count = 0;

let display = document.getElementById("count");

document.getElementById("increase").addEventListener("click", function() {

    count++;

    display.textContent = count;

});

document.getElementById("decrease").addEventListener("click", function() {

    count--;

    display.textContent = count;

});

document.getElementById("reset").addEventListener("click", function() {

    count = 0;

    display.textContent = count;

});
```

**Output:**

Counter increase, decrease aur reset hoga.

**Output Screenshot:**

[Add your Counter App screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 300 px -->

<a id="digital-clock"></a>

## Practical Project 2 — Digital Clock

**Project Purpose:**

Current time display karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Digital Clock</title>
</head>
<body>

    <h1>Digital Clock</h1>

    <h2 id="clock"></h2>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
function updateClock() {

    let now = new Date();

    let time = now.toLocaleTimeString();

    document.getElementById("clock").textContent = time;

}

updateClock();

setInterval(updateClock, 1000);
```

**Output:**

```text
Digital Clock

02:30:15 PM
```

**Output Screenshot:**

[Add your Digital Clock screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="calculator"></a>

## Practical Project 3 — Calculator

**Project Purpose:**

Basic mathematical calculations perform karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Simple Calculator</title>
</head>
<body>

    <h1>Simple Calculator</h1>

    <input type="number" id="num1" placeholder="First Number">

    <input type="number" id="num2" placeholder="Second Number">

    <button id="add">Add</button>

    <button id="subtract">Subtract</button>

    <button id="multiply">Multiply</button>

    <button id="divide">Divide</button>

    <h2 id="result">Result: 0</h2>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let num1 = document.getElementById("num1");

let num2 = document.getElementById("num2");

let result = document.getElementById("result");

function calculate(operation) {

    let a = Number(num1.value);

    let b = Number(num2.value);

    let answer;

    if (operation === "add") {

        answer = a + b;

    } else if (operation === "subtract") {

        answer = a - b;

    } else if (operation === "multiply") {

        answer = a * b;

    } else if (operation === "divide") {

        answer = b === 0 ? "Cannot divide by zero" : a / b;

    }

    result.textContent = "Result: " + answer;

}

document.getElementById("add").addEventListener("click", () => calculate("add"));

document.getElementById("subtract").addEventListener("click", () => calculate("subtract"));

document.getElementById("multiply").addEventListener("click", () => calculate("multiply"));

document.getElementById("divide").addEventListener("click", () => calculate("divide"));
```

**Output:**

User two numbers enter karke mathematical operations perform kar sakta hai.

**Output Screenshot:**

[Add your Calculator screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 300 px -->

<a id="to-do-list"></a>

## Practical Project 4 — To-Do List

**Project Purpose:**

Tasks add aur delete karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>To Do List</title>
</head>
<body>

    <h1>My To-Do List</h1>

    <input type="text" id="taskInput" placeholder="Enter task">

    <button id="addTask">Add Task</button>

    <ul id="taskList"></ul>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let input = document.getElementById("taskInput");

let button = document.getElementById("addTask");

let list = document.getElementById("taskList");

button.addEventListener("click", function() {

    let task = input.value.trim();

    if (task === "") {

        return;

    }

    let item = document.createElement("li");

    let deleteButton = document.createElement("button");

    item.textContent = task + " ";

    deleteButton.textContent = "Delete";

    deleteButton.addEventListener("click", function() {

        item.remove();

    });

    item.append(deleteButton);

    list.append(item);

    input.value = "";

});
```

**Output:**

User task add aur delete kar sakta hai.

**Output Screenshot:**

[Add your To-Do List screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 300 px -->

<a id="password-show-and-hide"></a>

## Practical Project 5 — Password Show and Hide

**Project Purpose:**

Password ko visible aur hidden karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Password Toggle</title>
</head>
<body>

    <h1>Password Field</h1>

    <input type="password" id="password" placeholder="Enter password">

    <button id="toggle">Show</button>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let password = document.getElementById("password");

let button = document.getElementById("toggle");

button.addEventListener("click", function() {

    if (password.type === "password") {

        password.type = "text";

        button.textContent = "Hide";

    } else {

        password.type = "password";

        button.textContent = "Show";

    }

});
```

**Output:**

Show button click karne par password visible aur Hide click karne par hidden ho jayega.

**Output Screenshot:**

[Add your Password Toggle screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="character-counter"></a>

## Practical Project 6 — Character Counter

**Project Purpose:**

Textarea mein entered characters count karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Character Counter</title>
</head>
<body>

    <h1>Character Counter</h1>

    <textarea id="message" maxlength="100" placeholder="Write something"></textarea>

    <p>Characters: <span id="count">0</span>/100</p>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let message = document.getElementById("message");

let count = document.getElementById("count");

message.addEventListener("input", function() {

    count.textContent = message.value.length;

});
```

**Output:**

User jitne characters type karega, counter update hota rahega.

**Output Screenshot:**

[Add your Character Counter screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="background-color-changer"></a>

## Practical Project 7 — Background Color Changer

**Project Purpose:**

Button click karne par webpage ka background color change karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Background Changer</title>
</head>
<body>

    <h1>Background Color Changer</h1>

    <button id="red">Red</button>

    <button id="blue">Blue</button>

    <button id="green">Green</button>

    <button id="reset">Reset</button>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
document.getElementById("red").addEventListener("click", function() {

    document.body.style.backgroundColor = "red";

});

document.getElementById("blue").addEventListener("click", function() {

    document.body.style.backgroundColor = "blue";

});

document.getElementById("green").addEventListener("click", function() {

    document.body.style.backgroundColor = "green";

});

document.getElementById("reset").addEventListener("click", function() {

    document.body.style.backgroundColor = "white";

});
```

**Output:**

Different buttons click karne par background color change hoga.

**Output Screenshot:**

[Add your Background Changer screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="form-validation"></a>

## Practical Project 8 — Form Validation

**Project Purpose:**

User ke form data ko validate karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Form Validation</title>
</head>
<body>

    <h1>Registration Form</h1>

    <form id="myForm">

        <input type="text" id="username" placeholder="Enter Name">

        <input type="email" id="email" placeholder="Enter Email">

        <button type="submit">Register</button>

    </form>

    <p id="message"></p>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let form = document.getElementById("myForm");

let username = document.getElementById("username");

let email = document.getElementById("email");

let message = document.getElementById("message");

form.addEventListener("submit", function(event) {

    event.preventDefault();

    if (username.value.trim() === "" || email.value.trim() === "") {

        message.textContent = "Please fill all fields.";

        return;

    }

    if (!email.validity.valid) {

        message.textContent = "Enter a valid email.";

        return;

    }

    message.textContent = "Registration Successful!";

});
```

**Output:**

Empty fields submit karne par error message display hoga.

**Output Screenshot:**

[Add your Form Validation screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 300 px -->

<a id="random-number-generator"></a>

## Practical Project 9 — Random Number Generator

**Project Purpose:**

Random number generate karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Random Number</title>
</head>
<body>

    <h1>Random Number Generator</h1>

    <button id="generate">Generate Number</button>

    <h2 id="result">0</h2>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let button = document.getElementById("generate");

let result = document.getElementById("result");

button.addEventListener("click", function() {

    let number = Math.floor(Math.random() * 100) + 1;

    result.textContent = number;

});
```

**Output:**

Button click karne par 1 se 100 ke beech random integer display hoga.

**Output Screenshot:**

[Add your Random Number Generator screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 250 px -->

<a id="notes-app"></a>

## Practical Project 10 — Notes App

**Project Purpose:**

Notes create aur browser storage mein save karna.

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Notes App</title>
</head>
<body>

    <h1>My Notes</h1>

    <textarea id="noteInput" placeholder="Write your note"></textarea>

    <button id="saveNote">Save Note</button>

    <ul id="notesList"></ul>

    <script src="script.js"></script>

</body>
</html>
```

**script.js**

```javascript
let input = document.getElementById("noteInput");

let button = document.getElementById("saveNote");

let list = document.getElementById("notesList");

let notes = JSON.parse(localStorage.getItem("notes")) || [];

function displayNotes() {

    list.innerHTML = "";

    notes.forEach(function(note, index) {

        let item = document.createElement("li");

        let deleteButton = document.createElement("button");

        item.textContent = note + " ";

        deleteButton.textContent = "Delete";

        deleteButton.addEventListener("click", function() {

            notes.splice(index, 1);

            saveNotes();

        });

        item.append(deleteButton);

        list.append(item);

    });

}

function saveNotes() {

    localStorage.setItem("notes", JSON.stringify(notes));

    displayNotes();

}

button.addEventListener("click", function() {

    let note = input.value.trim();

    if (note === "") {

        return;

    }

    notes.push(note);

    input.value = "";

    saveNotes();

});

displayNotes();
```

**Output:**

User notes add aur delete kar sakta hai. Notes browser ke localStorage mein save rahenge.

**Output Screenshot:**

[Add your Notes App screenshot here.]

<!-- Add your output screenshot here. Recommended size: 600 × 300 px -->

---

<a id="important-keywords"></a>

## Important Keywords

| Keyword | Purpose |
|---|---|
| let | Variable declaration |
| const | Constant binding |
| var | Older variable declaration |
| function | Function declaration |
| return | Value return |
| if | Condition |
| else | Alternative condition |
| switch | Multiple cases |
| for | Loop |
| while | Condition-based loop |
| break | Stop loop or switch |
| continue | Skip current iteration |
| try | Error handling |
| catch | Handle error |
| finally | Final execution block |
| throw | Throw error |
| class | Class declaration |
| extends | Inheritance |
| super | Parent class constructor/method |
| new | Create object instance |
| this | Current context |
| typeof | Type check |
| delete | Delete property |
| in | Property check |
| instanceof | Instance check |
| import | Import module |
| export | Export module |
| async | Async function |
| await | Wait for Promise |
| yield | Generator pause |
| debugger | Debug execution |

<a id="important-dom-methods"></a>

## Important DOM Methods

| Method / Property | Purpose |
|---|---|
| getElementById() | Select by ID |
| getElementsByClassName() | Select by class |
| getElementsByTagName() | Select by tag |
| querySelector() | First CSS selector match |
| querySelectorAll() | All CSS selector matches |
| createElement() | Create element |
| append() | Add node or text |
| appendChild() | Add child node |
| remove() | Remove element |
| removeChild() | Remove child node |
| setAttribute() | Set attribute |
| getAttribute() | Get attribute |
| removeAttribute() | Remove attribute |
| addEventListener() | Add event listener |
| classList.add() | Add class |
| classList.remove() | Remove class |
| classList.toggle() | Toggle class |
| classList.contains() | Check class |
| closest() | Find nearest matching ancestor |
| matches() | Check selector match |

<a id="important-event-methods"></a>

## Important Event Methods

| Event / Method | Purpose |
|---|---|
| click | Click event |
| dblclick | Double click |
| mouseenter | Mouse enter |
| mouseleave | Mouse leave |
| mousemove | Mouse move |
| keydown | Keyboard press |
| keyup | Keyboard release |
| input | Input change |
| change | Value change |
| submit | Form submission |
| focus | Focus event |
| blur | Focus lost |
| preventDefault() | Default action stop |
| stopPropagation() | Event propagation stop |

<a id="important-array-methods"></a>

## Important Array Methods

| Method | Purpose |
|---|---|
| push() | Add at end |
| pop() | Remove from end |
| shift() | Remove from start |
| unshift() | Add at start |
| slice() | Extract portion |
| splice() | Add/remove elements |
| concat() | Combine arrays |
| join() | Convert to string |
| indexOf() | Find index |
| includes() | Check value |
| find() | First matching value |
| findIndex() | First matching index |
| forEach() | Iterate elements |
| map() | Transform elements |
| filter() | Filter elements |
| reduce() | Single accumulated result |
| some() | At least one match |
| every() | All elements match |
| sort() | Sort elements |
| reverse() | Reverse elements |

<a id="important-string-methods"></a>

## Important String Methods

| Method / Property | Purpose |
|---|---|
| length | String length |
| charAt() | Character at index |
| at() | Character at index |
| includes() | Search text |
| indexOf() | First matching index |
| lastIndexOf() | Last matching index |
| slice() | Extract portion |
| substring() | Extract portion |
| replace() | Replace first match |
| replaceAll() | Replace all matches |
| split() | Convert to array |
| trim() | Remove edge whitespace |
| repeat() | Repeat string |
| toUpperCase() | Uppercase |
| toLowerCase() | Lowercase |
| startsWith() | Check starting text |
| endsWith() | Check ending text |

<a id="important-browser-apis"></a>

## Important Browser APIs

| API | Purpose |
|---|---|
| DOM API | HTML document manipulation |
| Fetch API | Network requests |
| Geolocation API | Device location |
| Clipboard API | Clipboard operations |
| Storage API | Browser data storage |
| History API | Browser navigation history |
| URL API | URL parsing and modification |
| Notification API | Browser notifications |
| Canvas API | Drawing graphics |
| Web Storage API | localStorage and sessionStorage |

<a id="practice-questions"></a>

## JavaScript Practice Questions

**Basic Level**

1. JavaScript kya hai?
2. JavaScript aur Java mein kya difference hai?
3. var, let aur const mein kya difference hai?
4. JavaScript ke primitive data types kaun se hain?
5. `typeof` operator ka use kya hai?
6. `==` aur `===` mein kya difference hai?
7. Function kya hota hai?
8. Array kya hota hai?
9. Object kya hota hai?
10. Loop kya hota hai?

**Intermediate Level**

11. Arrow Function kya hota hai?
12. Callback Function kya hota hai?
13. Higher-Order Function kya hota hai?
14. map() aur forEach() mein kya difference hai?
15. filter() aur find() mein kya difference hai?
16. Spread aur Rest Operator mein kya difference hai?
17. DOM kya hota hai?
18. querySelector() aur querySelectorAll() mein kya difference hai?
19. Event Bubbling kya hai?
20. Event Delegation kya hai?

**Advanced Level**

21. Closure kya hota hai?
22. Hoisting kya hoti hai?
23. Event Loop kya hai?
24. Promise kya hota hai?
25. async aur await kya hain?
26. JSON kya hai?
27. Fetch API kya hai?
28. localStorage aur sessionStorage mein kya difference hai?
29. JavaScript Modules kya hain?
30. Error Handling kya hoti hai?

<a id="javascript-learning-checklist"></a>

## JavaScript Learning Checklist

- [ ] JavaScript Fundamentals
- [ ] Variables and Data Types
- [ ] Operators
- [ ] Type Conversion
- [ ] Conditions
- [ ] Loops
- [ ] Functions
- [ ] Arrays
- [ ] Objects
- [ ] DOM Manipulation
- [ ] Events
- [ ] Scope and Closures
- [ ] ES6+ Features
- [ ] Date and Time
- [ ] Error Handling
- [ ] JSON
- [ ] Asynchronous JavaScript
- [ ] Promises
- [ ] Async/Await
- [ ] Browser APIs
- [ ] JavaScript Modules
- [ ] Browser Storage
- [ ] Practical Projects

<a id="useful-resources"></a>

## Useful Resources

| Resource | Purpose |
|---|---|
| MDN JavaScript Guide | Complete JavaScript documentation |
| MDN JavaScript Reference | Keywords, methods and APIs |
| JavaScript.info | Detailed JavaScript tutorials |
| W3Schools | Beginner-friendly examples |
| freeCodeCamp | Practical coding exercises |
| ECMAScript Specification | Official language specification |

## Useful Links:

- MDN Guide: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
- MDN Reference: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference
- JavaScript.info: https://javascript.info/
- W3Schools: https://www.w3schools.com/js/
- freeCodeCamp: https://www.freecodecamp.org/
- ECMAScript: https://tc39.es/ecma262/

---

<p align="center">
    <a href="#top">↑ Back to Top</a>
</p>