# 1. Ellen Ullman, Close to the machine: Technophilia and its Discontents

“We think we are creating the system for our own purposes. We believe we are making it in our own image... But the computer is not really like us. It is a projection of a very slim part of ourselves: that portion devoted to logic, order, rule, and clarity.”

---

# 2. Ursula K. Le Guin, The Left Hand of Darkness.

When action grows unprofitable, gather information; when infor- mation grows unprofitable, sleep.

# 3. Master Yuan-Ma, The Book of Programming

“Below the surface of the machine, the program moves. Without effort, it expands and contracts. In great harmony, electrons scatter and regroup. The forms on the monitor are but ripples on the water. The essence stays invisibly below.”

---

# Chapter 1 : Values, Types and Operators

# values

A typical computer has more than 30 billion bits in its volatile data storage (working mem). Non volatile memory (the hard disk for example) tends to have a magnituted more.

To be able to work with such large quantities of bits without getting lost, we must separate them into chunks that represent peices of information. In a js env those chunks are called values. Though all values are made of bits, they play different roles.

Every value has a type that determines its role.

Some values are numbers, some are pieces of text, some are functions and so on.

To create a value, you must merely invoke its name. This is convenient. You dont have to gather all the building material for your values of pay for them.

You just call for one, and whoosh, you have it. They are not really created from thin air. Every value has to be stored somewhere and if you need to use humongous amount of that you are likely to run out of memory.

# Atomic elements of javascript program

# Numbers

These are numeric values. Javascript uses 64 bit number of bits to store a single value.
