1. Declaring Variables
1.1. Use 'let' for variables that can change  
let variableName = initialValue;  

// Examples:  
let age = 25;  
let username = "Alice";  
let isActive = true;  

1.2. Use 'const' for variables that cannot change  
const constantName = value;  

// Examples:  
const PI = 3.14;  
const APP_NAME = "MyApp"; 

2. Writing conditions
2.1.Basic 'if-else' statement  
if (condition) {  
 Code to run if condition is true  
} else {  
 Code to run if condition is false  
}  

// Example:  
if (age >= 18) {  
  console.log("Access granted.");  
} else {  
  console.log("Access denied.");  
}  

// Multiple conditions with 'else if'  
if (score > 90) {  
  console.log("A");  
} else if (score > 80) {  
  console.log("B");  
} else {  
  console.log("C");  
}  
