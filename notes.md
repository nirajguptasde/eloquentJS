# Elquent JS : Modern Introduction to Programming

## Intro

Computers are as common as screwdrivers these days but they are far more complex then them. Making them do exactly what you want is not very easy.

If the task you have at hand is a simple one you can find an application and get started. But if your task is unique and open-ended its a completely different story.

This is where programming comes in.

Most programming is done with a programming language. A programming language is artificaly constructed langauge used to instruct computers. It is interseting that the best way to communicate with computers borrows so heavily from the way we communicate with each other.

Like human langauges, computer langs allow words and phrases to combined in new ways, making it possible to express ever new concepts.

# On Programming

Programming is hard. The fundamental rules are simple and clear. But the programs built on top of these rules tend to become complex enough to introduce their own rules and complexity.

A program is many things. It's a piece of text typed by a programmer it is the directing force that makes the computer do what it does. It is the data in computer's memory. Yet it controls the actions peformed in same memory.

Keeping programs under control is the main problem of proramming. The art of programming is the skill of controlling complexity. The great program is subdued - made simple in its complexity.

A sense of what good program looks like is developed in practice, not learned from the list of rules.

# Why care about programming langaugae?

Same program can be expressed in both long and short, undreadable ways. The first version of the program is extremely obscure.

# Code and what to do with it?

code is the text that makes up programs.

Operators that use two values are called binary operators and the ones that use one value are called unary operators.

There is only one value in javascript that is not equal to itself.

That is NaN.

NaN is supposed to denote the result of a nonsensical compution, and as such, it isnt equal to the result of any other nonsensical computation.

# Logical Operators

There are some operations that can be applied to Boolean values themselves. Javascript supports 3 logical operators. and, or and not. These can be used to reason about booleans.

The && operator represents logical and. It is a binary operator and its result is only true if both the vlaues given to it are true.

# And

true && true // true
true && false // false
false && true // false
false && false // false

# Or

the || operator denotes logical or. It produces true if either of the values given to it are true.

true || false // true
false || false // false

# Not

Not is written as exclamination mark (!).

Its a unary operator that flips the value give to it. !true prodcues false. !false gives true.

# Ternary logical operator

true ? 1 : 2 // 1
false ? 1 : 2 // 2

This one is called conditional operator. The value on the left of the question mark "picks" out which

# Empty values

There are two special values, written null and undefined. That are used to denote absense of a meaningful value. They are themselves values but carry no information.

# Automatic Type conversion

Js goes out of its ways to accept almost any program you give at it. even progarms that do odd things.

When an operator is applied to wrong type of value, javascript will quietly convert hat value to the type that it needs

This is called type coercion.

# Chapter 2: Program Structure

## Expressions and Statements

A fragment of code that produces values is called an expression. Every value that is written literally i.e 22 or "dunder" is an expression.

An expression between () is also an expression. as is a binary operator or the unary and ternary operator.

This shows part of the beauty of a language based interface. Expressions can contain other expressions in a way similar to how subsentences in human langauges are nested. Subsentece can contain its own subsentence and so on. This allows us to build expressions that describe complex computations.

If an expression corresponds to a sentence fragment, a javascript statement corresponds to a full sentance.

The simples ones are those with the semicolon at the end.

1;
false;

It is a useless program, though. An expression can be content to just produce a value.

A statement stands on its own. so it amounts to something only if it affects the world.
