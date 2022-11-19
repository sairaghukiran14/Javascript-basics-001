# Javascript-basics-001
/*
Javacript Basics Handson 001
--------------------------------------------------------------------------------------------------------------------------
Variables in Javascript
*/
const r = 0;//End of a Statement should be ended with ; (Semicolon)
// const defines a Constant reference to the value,cannot be assigned a value to the const variable
 
r = 1;
// Forcing the variable to be assigned a new value throws a Uncaught TypeError
//const variable cannot be initialized later

let l = 999;
l = 9999;
//We can reassign a value to the let variable in Javascript

let a;
a = 888;
//Let values can be Iniliazed later
// we cannot redeclare the let variable more then one time
let b = 1;
let b = 19;
/*
Javasript has 2 main Types:
1.Primitive Types
                -Numbers
                -Strings
                -Booleans
                -Symbols
                -null
                -undefined
2.Object Types
                -Any value that is not primitive is OBJECT
                -Objects have properties and methods that can act as properties
------------------------------------------------------------------------------------------------------------------------------
Expressions in Javascript:
-Expressions is a single unit in JS that Javascript Engine can evalute and return a value.
Primary Expressions:
                */
                2
                0.02
                ;
                true
                false
                this // the Current scope
                undefined
                i // variable
/*
Arithmatic Expressions:                                                                             */
                        1 / 2
                        i++
                        i-=2// i = i-2;
                        i * 2
// .  String Expressions :

                'A' + 'String' // where + concatinates the string i.e the result is " AString " .
//    Logical Expressions :
                a && b
                a || b
                !a
/*
--------------------------------------------------------------------------------------------------------------------------------
Operators in Javascript:
1.Arithmetic Operators
    + (Addition Operator)
    - (Subtraction Operator)
    / (Division Operator)
    % (Remainder Operator)
    * (Multiplication Operator)
    **(Exponentiation Operator)
*/

let a1 , a2 , a3;
a1 = 2;
a2 = 3
a3 = a1 + a2; // 2 + 3 = 5
a3 = a2 - a1; // 3 - 2 = 1
a3 = a2 / a1; // 3 / 2 = 1.5
a3 = a2 % a1; // 3 % 2 = 1
a3 = a2 * a1; // 3 * 2 = 6
a3 = a2 ** a1; // 3 ** 2 = 9

//Precedence Rules in Javascript

let a4 = 1 * 2 + ((5 / 2) % 2); // result is 2.5
// * / % these have same importance
// + - these have next best importance
// = assignment have the last importance
//operations on the same level are executes in the order they found form left to right( * / %)

/*
2.Comparision Operators
these comparision operators are always boolesn either 'true' or 'false'
----DisEquality Comparision Operators:
        -  < means "less than"
        -  <= means "less than or equal to"
        -  > means "greater than"
        -  >= means "greater than or equal to"
*/
let a5 = 1;
a5 >=1 /* true
---Equality Comparision Operators:
        -  === means checks for equality
        -  !== means checks for Inequality
*/
