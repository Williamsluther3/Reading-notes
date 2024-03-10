# Expression & Loop Summary

 ## Expression  
 
 *Expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) : x = 7 uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.
Expression also evaluate: 3 + 4 uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

## Loops  

*Loops* offer a quick and easy way to do something repeatedly. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!) The two most common loops are a *For Statements and a While Statements.

## For Statements  

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop. 
A for statement looks as follows:

for (initialization; condition; afterthought)
statement

## While Statement  

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)

  statement

### A while loop is a loop that is going to run while a specified condition evaluates to true. If condition is true, the statement executes again. At the end of every execution, the condition is checked. When the condition is false, execution stops, and control passes to the statement following do...while.
