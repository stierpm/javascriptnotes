# Javascript Notes

### Values
Javascript defines two types of values. Fixed values are called "literals", while variable values are called "variables". Numbers and static strings are literal values while variables can be changing values of stored data.

### Variables
Variables store information and are declared by starting your statement with 'var', 'const', or 'let', followed by a space and the name of the variable.
- **var** is a general variable declaration
- **const** declares a constant variable who's value cannot change
- **let** much like 'var', these variables can be reassigned if necessary

### Primitive Data Types
- **Strings** *example* "The brown fox ran"
- **Numbers** *example* 30
- **Booleans** *example* true
- **Null** *example* null
- **Undefined** undefined variables are variables without a given value but has space to create a value

### Math Operators
- **Add:** + (can also be used to concatenate strings)
- **Subtract:** -
- **Multiply:** *
- **Divide:** /
- **Modulus:** % (division remainder)

### Assignment Operators
- **+=** would add to a variable *example x += 2* (also can be used to concatenate strings)
- **-=** would subtract from a variable *example x -= 2*
- **(asterisk)=** would multiply a variable *example x (asterisk)= 2*
- **++** would add to a variable an increment of one *example x++*
- **--** would subtract from a variable a decrement of one *example x--*

### Comparison Operators
- **==** equal to
- **===** equal value and equal type
- **!=** not equal
- **!==** not equal value or not equal type
- **>** greater than
- **<** less than
- **>=** greater than or equal to
- **<=** less than or equal to
- **?** ternary operator

### Logical Operators
- **&&** logical and
- **||** logical or
- **!** logical not

### Type Operators
- **typeof** returns the type of a variable
- **instanceof** returns true if an object is an instance of an object type

### Escape Characters
Escapes turn special characters into strings in a string.
- **\'** single quote
- **\"** double quote
- **\\** backslash
- **\b** backspace
- **\f** form feed
- **\n** new line
- **\r** carriage return
- **\t** horizontal tabulator
- **\v** vertical tabulator

### Properties
Each piece of data has additional information attached to it, known as properties. Append the data with a period, followed by the property.
- [Javascript properties index](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Properties_Index#A)

### Objects
Objects are similar to arrays, however they are written in curly braces and involve key/value pairs, separated by commas. Objects are variables too, but objects contain many name:value/key:value pairs.
- Objects are like cars. They have properties but different values, and they all have methods but they are performed at different times.
- The name:value pairs in an object are called properties
- You can access object properties either by objectName.propertyName, or objectName["propertyName"]
- When a JavaScript variable is declared with the keyword, "new" the variable is created as an object
- Do not create strings as object because it slows down execution speed
- Comparing two objects will always return false

Global objects, or libraries are methods that are called without an instance. Objects are called by first declaring the library name, followed by a period, followed by the name of the method and then an opening and closing parentheses.
- [Javascript global objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)

### Methods
Methods are actions that can be performed on objects and are stored in object properties as function definitions.
- "this" keyword in a function definition refers to the owner of the function, or the name of the object
- You can call an object method the same as you would access object properties, but only with objectName.methodName()
Each piece of data has the ability to calculate new information and output that information, using methods. Append the data with a period, the name of the method and opening and closing parentheses.
- [Javascript methods index](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Methods_Index)

### Conditional Statements
Also known as control flow, conditional statements determine a path for your program to take if a set of conditions are met or not. Even non-boolean data types can be rendered as true or false. However, there are values that will determine a false statement:
- false = false
- 0 or -0 = false
- "" or '' = false
- null = false
- undefined = false
- NaN = false

You can also write conditional statements as switch statements, where the else if conditions are treated as cases in a switch operation. *Remember* to add break statements at the end of every case so that your code will stop executing once the condition is proven true.

You may also write else/if conditional statements as *ternary operators*. Question marks check truthiness, and blocks of code to be executed are separated by colons.

### Functions
A function is a block of code designed to perform a particular task. Naming functions follows the same rules as naming variables, and may include parameter names separated by commas. Functions often compute a return value, using a return statement.
- Functions help you to be able to reuse code
- If you do not use parentheses with you function instance, a return of the function definition will appear
- Functions can appear as variable values
- Functions can be called upon an event, with it is invoked from JavaScript code or self invoked.

### Events
JavaScript can be made to react to HTML events. HTML allows for event handlers with JavaScript.
- Since JavaScript is usually several lines long, event attributes commonly call functions
- [DOM HTML Events](https://developer.mozilla.org/en-US/docs/Web/Events)

Event handlers can be used to handle and verify user input, user actions and browser actions
- Things that should be done every time a page loads
- Things that should be done when the page is closed
- Action that should be performed when a user clicks a button
- Content that should be verified when a user inputs data
- More...

### Comments
Comments allow you to both negate any number of lines of code, and thoroughly describe your code.

### Other Notes
- **String Interpolation** is the insertion of variable content into a string *example 'I own a pet ' + myPet + '.'*. You can also use backticks to insert variables directly into strings *example `I own a pet ${myPet}.`*
- **Control Flow** or true/false statements determine a path for your program to take if a set of conditions are met or not. Even non-boolean data types can be rendered as true or false.
