Name the three ways to declare a variable?
1)The three ways you can declare a variable is var, let and const. Variable is the old way in really shouldn't be used anymore. Const is used to declare a variable that is constant which means it wont change.

Which of the three variable declarations should you avoid and why?
1) It's best to avoid var as the new let declaraction fuctions more efficent.


What rules should you follow when naming variables?
1) Declaring the same variable twice. It should only be declared once.
2) The name should containg only letters, digits or the symbols $ and _. The first character can't be a digit.
3)Do not use reserved words to declare.

What should you look out for when using the + operator with numbers and strings?
1) The plus operator will not convert strings into numbers. So for example 1 + "1" =11. In other words it does string concatenation. For example "string"+"string"=stringstring

How does the % operator work?
The % is a modelo opretor which gets the remainder of two values. For example 5%3=2 as the sum is 3 with a remainder of 2

Explain the difference between == and ===.
1) == tests whether the values are the same but not if the values databases are the same.
2) === tests if the left and right values are identical to on another aka strict equality.

When would you receive a NaN result?
You would receive a NaN when the number is not a legal number. For example 100/ "Dog" = NaN

How do you increment and decrement a number?
++num
--num

Explain the difference between prefixing and post-fixing increment/decrement operators.

1)Prefxing increment/decrement operators increments/decrements the value of the operator and returns the new value. For example 
let counter =1;
let a = ++counter;
alert(a) //2


2)Postfixing increment/decrement operators increments/decrements the value of the operator and returns the old value. 
let counter =1;
let a = counter++;
alert(a) //1

What is operator precedence and how is it handled in JS?
Operator precedence is similar to PEMDAS in math in which the expressions you use in your variable will be done according to how high the precedence is. 
How do you access developer tools and the console?
fn + f12>console

How do you log information to the console?
console.log

What does unary plus operator do to string 
representations of integers? It will convert the string into a number. 
