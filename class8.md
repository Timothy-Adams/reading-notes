**Assignment operators**

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal `(=)`, which assigns the value of its right operand to its left operand. That is, `x = f()` is an assignment expression that assigns the value of `f()` to `x`.

There are also compound assignment operators that are shorthand for the operations listed in the following table:

**Name**	                       ** Shorthand operator**              **Meaning**
Assignment	                              `x = f()`	                     `x = f()`
Addition assignment	                      `x += f()`	                 `x = x + f()`
Subtraction assignment	                  `x -= f()`	                 `x = x - f()`
Multiplication assignment	              `x *= f()`	                 `x = x * f()`
Division assignment	                      `x /= f()`	                 `x = x / f()`
Remainder assignment	                  `x %= f()`	                 `x = x % f()`
Exponentiation assignment	              `x **= f()`	                 `x = x ** f()`
Left shift assignment	                  `x <<= f()`	                 `x = x << f()`
Right shift assignment	                  `x >>= f()`	                 `x = x >> f()`
Unsigned right shift assignment	          `x >>>= f()`	                 `x = x >>> f()`
Bitwise AND assignment	                  `x &= f()`	                 `x = x & f()`
Bitwise XOR assignment	                  `x ^= f()`	                 `x = x ^ f()`
Bitwise OR assignment	                  `x |= f()`	                 `x = x | f()`
Logical AND assignment	                  `x &&= f()`	                 `x && (x = f())`
Logical OR assignment	                  `x ||= f()`	                 `x || (x = f())`
Logical nullish assignment	              `x ??= f()`	                ` x ?? (x = f())`




**Comparison operators**

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the `===` and `!==` operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

`const var1 = 3;
const var2 = 4;`


**Comparison operators**
Operator	                        Description	                              Examples returning true
`Equal (==)`	               Returns `true` if the operands are equal.	      `3 == var1`
                                                                                 `"3" == var1`
                                                                                  `3 == '3'`

`Not equal (!=)`	           Returns `true` if the operands are not equal.	  `var1 != 4`
                                                                                  `var2 != "3"`

`Strict equal (===)`   Returns `true` if the operands are equal and of the same type.  `3 === var1`

`Strict not equal (!==)`	Returns `true` if the operands are of the same type but not equal, or are of different type.	                                                           `var1 !== "3"`
                                                                                  `3 !== '3'`

`Greater than (>)`	Returns `true` if the left operand is greater than the right operand.`var2 > var1`
                                                                                        `"12" > 2`

`Greater than or equal (>=)`	Returns `true` if the left operand is greater than or equal to the right operand.	                                                                `var2 >= var1`
                                                                                 `var1 >= 3`

`Less than (<)`	Returns `true` if the left operand is less than the right operand.	`var1 < var2`
                                                                                    `"2" < 12`

`Less than or equal (<=)``	Returns `true` if the left operand is less than or equal to the right operand.	                                                                         `var1 <= var2`
                                                                                   `var2 <= 5`



                                                                                   
