# Python-Basic-Fundamental-part-2

### FOR
For loops are used for sequential traversal. For example: traversing a list or string or array etc. In Python, there is no C style for loop, i.e., for (i=0; i<n; i++). There is “for in” loop which is similar to for each loop in other languages.

### WHILE
In python, while loop is used to execute a block of statements repeatedly until a given condition is satisfied. And when the condition becomes false, the line immediately after the loop in the program is executed. All the statements indented by the same number of character spaces after a programming construct are considered to be part of a single block of code. Python uses indentation as its method of grouping statements.

### Nested Loop
Python programming language allows to use one loop inside another loop. Following section shows few examples to illustrate the concept.

### Loop Control Statements
Loop control statements change execution from its normal sequence. When execution leaves a scope, all automatic objects that were created in that scope are destroyed. Python supports the following control statements.

## Break
Break brings control out of loop

## Continue
Continue returns the control to the beginning of the loop

### ELSE For Loop
## ELSE After FOR
In Python, the else function is also known after for. The function is prioritized on the loop search - to provide program exits when search is not found. For loops also have an else clause which most of us are unfamiliar with. The else clause executes after the loop completes normally. This means that the loop did not encounter a break statement. The common construct is to run a loop and search for an item. If the item is found, we break out of the loop using the break statement. There are two scenarios in which the loop may end. The first one is when the item is found and break is encountered. The second scenario is that the loop ends without encountering a break statement.

## ELSE After WHILE
In the while statement, the else statement block will always be executed when the condition in while becomes false. With the else statement we can run a block of code once when the condition no longer is true.

### PASS
Pass function is used to skip an iteration of the loop because in loop empty code is not allowed. So when there is pass statement, there will be nothing happens, but it will skip the error while there is empty code

### LIST COMPREHENSION
Making list from inline loop and if

### ERROR & EXCEPTION HANDLING
Two types of errors based on their occurrence:
## Syntax errors
Syntax error occurs when python can't understand what you're commanding
Some most common causes of syntax errors:
- Misspelled reserved keywords
+ Missing required spaces
- Missing quotes
- Misuse of block statements (if-else, loops)
- Missing assignment operator (=)
- Invalid variables declaration
- Invalid function calling or defining

## Exceptions
Exception are also called Runtime errors
+ Even if we have written a statement or expression from python correctly, there is a possibility that an error will occur when the command is executed
- Errors that occur while the process is in progress are called exceptions and can be fatal if not handled
- Most exceptions in python are not handled by the application, so the application crashes and then an error message appears

### FUNCTION
In mathematics, a function is a process that relates an input and an output. In Python, apart from these relational functions, functions are also a way to organize code - with the ultimate goal of code reusability. Instead functions have only one specific use but can be reused. Python's common functions are provided, but we can always define our own function.
