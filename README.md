Qus -1--><h1>What is node.js ?</h1>
ans--> <p>Node.js is an open-source and cross-platform runtime environment built on Chrome’s V8 JavaScript engine for executing JavaScript code outside of a browser. You need to recollect that NodeJS isn’t a framework, and it’s not a programing language. It provides an event-driven, non-blocking (asynchronous) I/O and cross-platform runtime environment for building highly scalable server-side applications using JavaScript.</p>
<p>Why to learn NodeJS =>

Easy Scalability,
Real time web apps,
Fast Suite,
Easy to learn and code,
Advantage of Caching,
Data Streaming,
Hosting,
Corporate Support.</p>

Qus -2--><h1>What is npm ?</h1>
ans--> <p>NPM (Node Package Manager) is the default package manager for Node.js and is written entirely in Javascript. Developed by Isaac Z. Schlueter, it was initially released in January 12, 2010. NPM manages all the packages and modules for Node.js and consists of command line client npm. It gets installed into the system with installation of Node.js. The required packages and modules in Node project are installed using NPM.
A package contains all the files needed for a module and modules are the JavaScript libraries that can be included in Node project according to the requirement of the project.
NPM can install all the dependencies of a project through the package.json file. It can also update and uninstall packages. In the package.json file, each dependency can specify a range of valid versions using the semantic versioning scheme, allowing developers to auto-update their packages while at the same time avoiding unwanted breaking changes.</p>

Qus -3--><h1>What are the modules in Node.js?</h1>
ans--> <p>In Node.js, Modules are the blocks of encapsulated code that communicates with an external application on the basis of their related functionality. Modules can be a single file or a collection of multiples files/folders. The reason programmers are heavily reliant on modules is because of their re-usability as well as the ability to break down a complex piece of code into manageable chunks.</p>

Modules are of three types:

1.Core Modules
2.local Modules
3.Third-party Modules



Qus -4--><h1>What is the purpose of module.exports in node.js ?</h1>
ans--> <p>The main purpose of module.exports is to achieve modular programming. Modular programming refers to separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality. By not using module.exports it becomes difficult to write a large program without modular/reusable code.
</p>
<p>The module.exports is actually a property of the module object in node.js. module. Exports is the object that is returned to the require() call. By module.exports, we can export functions, objects, and their references from one file and can use them in other files by importing them by require() method.</p>


Qus -5--><h1>Difference between default export and named export?</h1>
ans--> <p>Named Exports: Named exports are useful to export several values. During the import, it is mandatory to use the same name of the corresponding object. 
</p>
 <p>Default Exports: Default exports are useful to export only a single object, function, variable. During the import, we can use any name to import. 
</p>


Qus -6--><h1>How do you import any module in Node.js?</h1>
ans--> <p>To import our own Node JS module. var arthmetic = require("arthmetic");
To import existing Node JS Module Import Node JS “express” module; var arthmetic = require("express"); Import Node JS “mongoose” module; var mongoose = require("mongoose");
</p>

