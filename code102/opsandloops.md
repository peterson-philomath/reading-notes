# Operators and Loops

## Reading Notes

1. **What is an expression in JavaScript?**
   - Expression: A valid unit of code that resolves to a value
   - Two Types:
      - Side effects (such as assigning values)
      - Evaluate
2. **Why would we use a loop in our code?**
   - It allows for a task to be done repeatedly.
   - Types of loops
     - For
     - while
3. **When does a for loop stop executing?**
   - Goes until a specified condition evaluates to false.
   -for (initialization; condition; afterthought){
   statement}
4. **How many times will a while loop execute?**
   - executes as long as a specified condition evaluates as true.
   - while (condition){
   statement}

## Lecture Notes

let x=5;  
let y='5';

console.log(x==y); //true  
console.log(x===y); //false

Logical AND --> &&  
console.log((x<10) && (y<10));  
T    &&    T --> Response is true

console.log((x<10) && (y>10));  
       T    &&    F --> Response is false

Logical OR --> ||  
console.log((x<10) || (y>10));  
T    or    F --> Response is true

//  Logical NOT --> !
// console.log(!true); --> Returns false
// console.log(!false); --> returns true

## Resources

- [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
