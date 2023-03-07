# Javascript Simplified

## Tools Needed
- Browser
  - Chrome, Firefox, Opera, Safari
- Javascript Runtime Environment
  - Node.js
-  IDE
   -  VSCode
   -  Live Server extension
   -  Intellisense to quickly identify issues in code
   -  Prettier
      -  set to format on save

##  Adding Javascript file to HTML
- `<script src="script.js"></script>`

## Variables
- It's like a box. You can name this box and pass it around.
- Can be defined using let and const
  - `let x = 0;`
  - `const y = 0;`

## Types in Javascript 
- `typeof x`
  - Display the type of the variable
- **Types**
  - **Number**
    - integers, floats
    - In the float arithmetics there is a chance of values not rounded as expected. Make sure to ceil, floor or round the values for managing expectations in output
  - **String**
    - string can be wrapped around single or double quotes
  - **Boolean Value**
    - truth or false is returned
- **Garbage Collection**
  - Delete the variables from the memory to keep the resource consumption at optimum levels
- **Comments**
  - Self explnatory text to improve code readability
  

## Functions
- Reusable logical statements
- Returns value if needed 
- Functions can ebe passed as function arguments
  - Callbacks work on this principle
  - Common pitfall : avoidance : Use function names without the parantheses
- 