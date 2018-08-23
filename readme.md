# Javascript Notes

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

### Variables
Variables store information and are declared by starting your statement with 'var', 'const', or 'let', followed by a space and the name of the variable.
- **var** is a general variable declaration
- **const** declares a constant variable who's value cannot change
- **let** much like 'var', these variables can be reassigned if necessary

### Values
Javascript defines two types of values. Fixed values are called "literals", while variable values are called "variables". Numbers and static strings are literal values while variables can be changing values of stored data.

### Properties
Each piece of data has additional information attached to it, known as properties. Append the data with a period, followed by the property.
- [Javascript properties index](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Properties_Index#A)

### Methods
Each piece of data has the ability to calculate new information and output that information, using methods. Append the data with a period, the name of the method and opening and closing parentheses.
- [Javascript methods index](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Methods_Index)

### Global Objects
Global objects, or libraries are methods that are called without an instance. Objects are called by first declaring the library name, followed by a period, followed by the name of the method and then an opening and closing parentheses.
- [Javascript global objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)

### Comments
Comments allow you to both negate any number of lines of code, and thoroughly describe your code.

### Other Notes
- **String Interpolation** is the insertion of variable content into a string *example 'I own a pet ' + myPet + '.'*. You can also use backticks to insert variables directly into strings *example `I own a pet ${myPet}.`*
