# JavaScript Questions

JavaScript is an open-source Programming Language. It is designed for creating web-centric applications. It is lightweight and interpreted, which makes it much faster than other languages. JavaScript is integrated with HTML, which makes it easier to implement JavaScript in web applications.

# **JavaScript Interview Questions for Freshers**

Here are some basic JavaScript interview questions and answers for you to prepare during your interviews.

# **1. What do you understand about JavaScript?**

![https://www.simplilearn.com/ice9/free_resources_article_thumb/js-logo.JPG](https://www.simplilearn.com/ice9/free_resources_article_thumb/js-logo.JPG)

JavaScript is a popular web scripting language and is used for client-side and server-side development. The JavaScript code can be inserted into HTML pages that can be understood and executed by web browsers while also supporting object-oriented programming abilities.

# **2. What’s the difference between JavaScript and Java?**

| JavaScript | Java |
| --- | --- |
| JavaScript is an object-oriented scripting language. | Java is an object-oriented programming language. |
| JavaScript applications are meant to run inside a web browser. | Java applications are generally made for use in operating systems and virtual machines. |
| JavaScript does not need compilation before running the application code. | Java source code needs a compiler before it can be ready to run in real time. |

# **3. What are the various data types that exist in JavaScript?**

These are the different types of data that JavaScript supports:

- Boolean - For true and false values
- Null - For empty or unknown values
- Undefined - For variables that are only declared and not defined or initialized
- Number - For integer and floating-point numbers
- String - For characters and alphanumeric values
- Object - For collections or complex values
- Symbols - For unique identifiers for objects

# **4. What are the features of JavaScript?**

These are the features of JavaScript:

- Lightweight, interpreted programming language
- Cross-platform compatible
- Open-source
- Object-oriented
- Integration with other backend and frontend technologies
- Used especially for the development of network-based applications

# **5. What are the advantages of JavaScript over other web technologies?**

These are the advantages of JavaScript:

### **Enhanced Interaction**

JavaScript adds interaction to otherwise static web pages and makes them react to users’ inputs.

### **Quick Feedback**

There is no need for a web page to reload when running JavaScript. For example, form input validation.

### **Rich User Interface**

JavaScript helps in making the UI of web applications look and feel much better.

### **Frameworks**

JavaScript has countless frameworks and libraries that are extensively used for developing web applications and games of all kinds.

# **6. How do you create an object in JavaScript?**

Since JavaScript is essentially an object-oriented scripting language, it supports and encourages the usage of objects while developing web applications.

const student = {

name: 'John',

age: 17

}

# 7. **How do you create an array in JavaScript?**

Here is a very simple way of creating arrays in JavaScript using the array literal:

var a = [];

var b = [‘a’, ‘b’, ‘c’, ‘d’, ‘e’];

# **8. What are some of the built-in methods in JavaScript?**

| Built-in Method | Values |
| --- | --- |
| Date() | Returns the present date and time |
| concat() | Joins two strings and returns the new string |
| push() | Adds an item to an array |
| pop() | Removes and also returns the last element of an array |
| round() | Rounds of the value to the nearest integer and then returns it |
| length() | Returns the length of a string |

# **9. What are the scopes of a variable in JavaScript?**

The scope of a variable implies where the variable has been declared or defined in a JavaScript program. There are two scopes of a variable:

### **Global Scope**

Global variables, having global scope are available everywhere in a JavaScript code.

### **Local Scope**

Local variables are accessible only within a function in which they are defined.

# **10. What is the ‘this’ keyword in JavaScript?**

The [‘this’ keyword in JavaScript](https://www.simplilearn.com/tutorials/javascript-tutorial/javascript-this-keyword) refers to the currently calling object. It is commonly used in constructors to assign values to object properties.

# **11. What are the conventions of naming a variable in JavaScript?**

Following are the naming conventions for a variable in JavaScript:

- Variable names cannot be similar to that of reserved keywords. For example, var, let, const, etc.
- Variable names cannot begin with a numeric value. They must only begin with a letter or an underscore character.
- Variable names are case-sensitive.

# **12. What is Callback in JavaScript?**

In JavaScript, functions are objects and therefore, functions can take other functions as arguments and can also be returned by other functions.

![https://www.simplilearn.com/ice9/free_resources_article_thumb/callback.JPG](https://www.simplilearn.com/ice9/free_resources_article_thumb/callback.JPG)

Fig: Callback function

A [callback](https://www.simplilearn.com/tutorials/javascript-tutorial/callback-function-in-javascript) is a [JavaScript function](https://www.simplilearn.com/tutorials/javascript-tutorial/javascript-functions) that is passed to another function as an argument or a parameter. This function is to be executed whenever the function that it is passed to gets executed.

# **13. How do you debug a JavaScript code?**

All modern web browsers like Chrome, Firefox, etc. have an inbuilt debugger that can be accessed anytime by pressing the relevant key, usually the F12 key. There are several features available to users in the debugging tools.

We can also debug a JavaScript code inside a code editor that we use to develop a JavaScript application—for example, Visual Studio Code, Atom, Sublime Text, etc.

# **14. What is the difference between Function declaration and Function expression?**

| Function declaration | Function expression |
| --- | --- |
| Declared as a separate statement within the main JavaScript code | Created inside an expression or some other construct |
| Can be called before the function is defined | Created when the execution point reaches it; can be used only after that |
| Offers better code readability and better code organization | Used when there is a need for a conditional declaration of a function |
| Example:
function abc() {
    return 5;
} | Example:
var a = function abc() {
    return 5;
} |

# **15. What are the ways of adding JavaScript code in an HTML file?**

There are primarily two ways of embedding JavaScript code:

- We can write JavaScript code within the script tag in the same HTML file; this is suitable when we need just a few lines of scripting within a web page.
- We can import a JavaScript source file into an HTML document; this adds all scripting capabilities to a web page without cluttering the code.

# **Intermediate JavaScript Interview Questions and Answers**

Here are some intermediate level JavaScript interview questions and answers for you to prepare during your interviews.

# **16. What do you understand about cookies?**

![https://www.simplilearn.com/ice9/free_resources_article_thumb/browser-cookies.JPG](https://www.simplilearn.com/ice9/free_resources_article_thumb/browser-cookies.JPG)

A cookie is generally a small data that is sent from a website and stored on the user’s machine by a web browser that was used to access the website. Cookies are used to remember information for later use and also to record the browsing activity on a website.

# **17. How would you create a cookie?**

The simplest way of creating a cookie using JavaScript is as below:

document.cookie = "key1 = value1; key2 = value2; expires = date";

# **18. How would you read a cookie?**

Reading a cookie using JavaScript is also very simple. We can use the document.cookie string that contains the cookies that we just created using that string.

The document.cookie string keeps a list of name-value pairs separated by semicolons, where ‘name’ is the name of the cookie, and ‘value’ is its value. We can also use the split() method to break the cookie value into keys and values.

# **19. How would you delete a cookie?**

To delete a cookie, we can just set an expiration date and time. Specifying the correct path of the cookie that we want to delete is a good practice since some browsers won’t allow the deletion of cookies unless there is a clear path that tells which cookie to delete from the user’s machine.

function delete_cookie(name) {

document.cookie = name + "=; Path=/; Expires=Thu, 01 Jan 1970 00:00:01 GMT;";

}

# **20. What’s the difference between let and var?**

Both let and var are used for variable and method declarations in JavaScript. So there isn’t much of a difference between these two besides that while var keyword is scoped by function, the let keyword is scoped by a block.

# **22. What are Promises in JS ? 
Promises in JavaScript are a mechanism for handling asynchronous operations. They provide a way to work with asynchronous code in a more organized and readable manner, making it easier to manage and coordinate multiple asynchronous tasks.