In Python there are several operators which perform basic arithmetic operations on numeric data that can be incorporated into expressions. When doing so, the operator sits between the values to be operated on (the operands).

# Addition

The addition operator `+` adds two numbers together. For example:

```py-cell
print(3 + 5) # Two integers produces an integer
print(2.5 + 4.5) # Two floats produces a float
print(-3 + 2.5) # An integer and a float produces a float
print(0.1 + 0.2) # Floating-pont error can occur with floats
```

# Subtraction

The subtraction operator `-` subtracts one number from another. For example:

```py-cell
print(10 - 4) # Two integers produces an integer
print(5.5 - 2.0) # Two floats produces a float
print(-3 - 7.5) # An integer and a float produces a float
print(0.3 - 0.1) # Floating-pont error can occur with floats
```

# Multiplication

The multiplication operator `*` multiplies two numbers together. For example:

```py-cell
print(4 * 6) # Two integers produces an integer
print(2.5 * 4.0) # Two floats produces a float
print(-3 * 2.5) # An integer and a float produces a float
print(0.1 * 0.2) # Floating-pont error can occur with floats
```

# Division

The division operator `/` divides one number by another. It performs floating-point division and so will always produce a float, even when both operands are integers and the result would be expressible as an integer. For example:

```py-cell
print(10 / 2) # Two integers produces a float
print(7.5 / 2) # Two floats produces a float
print(-9 / 2.5) # An integer and a float produces a float
print(8 / 3) # Floating-pont error can occur with floats
```

# Floor Division

The floor division operator `//` divides one number by another and rounds the result down to the nearest whole number, and expresses this number as a float For example:

```py-cell
print(10 // 3) # Round down
print(6 // 2) # Exact division
print(-7 // 3) # Rounds negative results down to the more negative whole number
# If either or both of the values used are floats, a float will be returned
print(7.0 // 3) 
print(7 // 2.5)
print(7.5 // 2.5)
```

# Modulo

The modulo operator `%` divides one number by another and returns the remainder. For example:

```py-cell
print(10 % 3) # Two integers produce an integer
print(7.5 % 2.5) # Two floats produce a float
print(9 % 3.5) # An integer and a float produces a float
```

When negative numbers are involved, the result of the modulo operation takes the sign of the divisor (the second operand). For example:

```py-cell
print(-10 % 3) # Result is positive (3 * -4 + 2 = -10)
print(10 % -3) # Result is negative (-3 * -4 + -2 = 10)
print(-10 % -3) # Result is negative (-3 * 4 + -2 = -10)
```

# Exponentiation

The exponentiation operator `**` raises one number to the power of another. For example:

```py-cell
print(2 ** 3) # Two positive integers produces an integer
print(4.0 ** 0.5) # Two floats produces a float
print(3 ** 2.0) # An integer and a float produces a float
print(9 ** -2) # Negative exponent produces a float, even if both operands are integers
```

Some novice Python users mistakenly use the caret symbol `^` for exponentiation as this is use for exponentiation in some other contexts, but in Python this is a completely different operator. It is the bitwise XOR operator (don't worry about what this does for now) and is not used for arithmetic.
