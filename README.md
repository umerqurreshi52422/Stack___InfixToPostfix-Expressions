Infix to Postfix Converter using Stack

This program converts an Infix expression to a Postfix expression using the Stack data structure.
How it works

The program takes an Infix expression as input and converts it to a Postfix expression using the following algorithm:

    Start scanning the expression from left to right.
    If the scanned character is an operand (variable or number), output it.
    If the scanned character is an operator, check its precedence.
    If the precedence of the scanned operator is greater than the precedence of the operator in the stack, push it onto the stack.
    If the precedence of the scanned operator is less than or equal to the precedence of the operator in the stack, pop the stack and output the operator until the stack is empty or an operator with lower precedence is encountered.
    Repeat steps 2-5 until the expression is scanned completely.
    If any operator remains in the stack, pop it and output it.

Features

    User-friendly interface
    Can handle single-letter variables and single-digit numbers
    Supports the following operators: +, -, *, /, and parentheses ()

Requirements

    C++ compiler

How to use

    Compile the program using a C++ compiler.
    Run the program.
    Choose option 1 to enter the Infix expression.
    Choose option 2 to convert the Infix expression to a Postfix expression.
    Choose option 0 to exit the program.



