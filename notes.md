



An operand – is what operators are applied to. For instance, in the multiplication of 5 * 2 there are two operands: the left operand is 5 and the right operand is 2. Sometimes, people call these “arguments” instead of “operands”.

An operator is unary if it has a single operand. For example, the unary negation - reverses the sign of a number:

There are 8 basic data types in JavaScript.

number for numbers of any kind: integer or floating-point, integers are limited by ±(253-1).
bigint is for integer numbers of arbitrary length.
string for strings. A string may have zero or more characters, there’s no separate single-character type.
boolean for true/false.
null for unknown values – a standalone type that has a single value null.
undefined for unassigned values – a standalone type that has a single value undefined.
object for more complex data structures.
symbol for unique identifiers.
The typeof operator allows us to see which type is stored in a variable.

Usually used as typeof x, but typeof(x) is also possible.
Returns a string with the name of the type, like "string".
For null returns "object" – this is an error in the language, it’s not actually an object.