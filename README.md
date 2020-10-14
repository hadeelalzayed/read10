# read10
if you understand execution  contexts and stacks you are more likely to find the error in you codeDebugging is the process of finding errors ,it involves a process of deduction the console helps narrow down the area in which the errors is located so you can try to find the exact errorJavaScript has 7 different types  of errors each creates its own error objects which can tell the line number and gives a description of erroryou can handle the errors by using the (try, catch, finally) statements To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run
ERROR OBJECTS
 (Links to an external site.)Syntax Error
(SYNTAX IS NOT CORRECT)

MISMATCHING OR UNCLOSED QUOTES
MISSING CLOSING BRACKET
MISSING COMMA IN ARRAY
MALFORMED PROPERTY NAME
 (Links to an external site.)Reference Error
(VARIABLE DOES NOT EXIST)

VARIABLE IS UNDECLARED
NAMED FUNCTION IS UNDEFINED
 (Links to an external site.)Eval Error
(INCORRECT USE OF eval() FUNCTION )

 (Links to an external site.)URI Error
(INCORRECT USE OF URI FUNCTIONS)

 (Links to an external site.)Type Error
(VALUE IS UNEXPECTED DATA TYPE)

 (Links to an external site.)RangeError
(NUMBER OUTSIDE OF RANGE)

 (Links to an external site.)Error
(GENERIC ERROR OBJECT)

 (Links to an external site.)NaN
(NOT AN ERROR)

 (Links to an external site.)HOW TO DEAL WITH ERRORS
1: DEBUG THE SCRIPT TO FIX ERRORS 2: **HANDLE ERRORS GRACEFULLY **

 (Links to an external site.)HANDLING EXCEPTIONS
Using try, catch, and finally.

try {

catch (exception) {

finally {

}
