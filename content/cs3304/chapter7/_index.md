---
# Title, summary, and page position.
linktitle: Chapter 7
summary: Learn how to use Academic's docs layout for publishing online courses, software documentation, and tutorials.
weight: 1
icon: book-reader
icon_pack: fas

# Page metadata.
title: Chapter 7
date: "2018-09-09T00:00:00Z"
type: book  # Do not modify.
---


=========
- Expressions are fundamental
- Understanding syntax is very important
- Must understand the meaning, semantics, of the statements

Arithmetic Expressions
======================
- Math in computer languages have developed from how we do math
- Kept the typical order of operations
- Unary, single operator and operand
- Binary, single operator and 2 operands
- Infix, operator between operands
- Prefix, operator before operand
- Use parentheses

Precedence/Associativity
========================
- Which operation will occur before the other
- `a + b *`
- Generally we will follow the typical math order
- Parentheses are always a way to enforce the order you want
- Generally we associate left to right when operators have same level of
precedence

Side Effects
============
- A side effect is when a function changes a parameter or a global variable.
- This matters when you are using a parameter in an expression where the 
parameter is also being combined with the function return:

	a + fun(a)

- Some languages, e.g. functional languages, don't typically allow for side
effects.

Type Conversions
================
- Narrowing
	- Going from a larger memory type to a smaller
	- Generally bad unless you know the data won't overflow
	- e.g. Double to float
- Widening
	- Going from a smaller memory type to a larger
	- Generally not a problem
	- e.g. Float to double
- Mixed expression will typically invoke implicit type coercion

Boolean Expressions
===================
- Symbols or words
- Short circuit evaluation
	- Only evaluate as much as needed to determine truth of statement
	- A && B || C
	- if ( x != 0 && y / x < 10 )

Assignment Statements
=====================
- Central concept of imperative languages
- Compound statement
	- a += b;
	- x = ++ count;
		- count = count + 1;
		- x = count;

Functional Languages
====================
- Once a variable is bound it can't be changed.
- Functions operate like mathematical functions
	- Operate on inputs and provide outputs
	- No side effects

Summary
=======
- Expressions and assignments are stems
- Came from imperative languages
- Evolved over time

