# *JavaScript(JS):
JS is a programming language (scripting language for Web pages) .JavaScript frameworks are an essential for modern **front-end web development**, it provides developers with proven tools for building scalable, interactive web applications.

**Java Script** runs on the client side of the web, which can be used to design / program how the web pages behave on the occurrence of an event. JavaScript is an easy to learn and also powerful scripting language, widely used for controlling web page behavior.

JavaScript is not "Interpreted Java". In a nutshell, JavaScript is a dynamic scripting language supporting prototype based object construction. The basic syntax is similar to both *Java and C++* to reduce the number of new concepts required to learn the language
Language constructs, such as if statements, for and while loops, and switch and try ... catch blocks function the same as in these languages (or nearly so). example:
let foo = 42;    // foo is now a number
foo     = 'bar'; // foo is now a string
foo     = true;  // foo is now a boolean

## JavaScript data types and data structures
JavaScript is a loosely typed and dynamic language. Variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned (and re-assigned) values of all types.

JavaScript provides three different value-comparison operations: 

* strict equality using ===
*  loose equality using ==
* the Object.is() method.
### Data and Structure types:
*Six Data Types* that are primitives, checked by typeof operator:

1. undefined : typeof instance === "undefined"

2. Boolean : typeof instance === "boolean"

3. Number : typeof instance === "number"

4. String : typeof instance === "string"

5. BigInt : typeof instance === "bigint"

6. Symbol : typeof instance === "symbol"

>Vist [developer.mozillat](https://developer.mozilla.org/en-US/docs/Web/JavaScript) for more information.

## *Input Output in plain JavaScript:

to get input from the user, we do this: 

-<html>

-<head>

  -<title>Hello World</title>

-</head>

-<body>
 

-First name: <input id="first_name">

-Last name: <input id="last_name">
<button id="say">Say hi!</button>
 
-<hr>
-<div id="result"></div>
 
-<script>

-function say_hi() {
    var fname = document.getElementById('first_name').value;
    var lname = document.getElementById('last_name').value;
 
    var html = 'Hello <b>' + fname + '</b> ' + lname;
 
    document.getElementById('result').innerHTML = html;
}
 

document.getElementById('say').addEventListener('click', say_hi);

-</script>
 

-</body>

-</html>
 
  
If you click on the Try link, you'll see two input boxes and a button:

![out put](https://replit.com/@naziha1986/reading-notesmd#nnnn.png)

 >For more information visit [code-maven](https://code-maven.com/input-output-in-plain-javascript)