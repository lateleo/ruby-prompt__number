---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Floats (numbers that include a decimal point) and intigers (numbers that do not). Additionally, numbers can be expressed in string form if necessary.

# What are some common operations and comparisons you would perform on numbers?

Basic arithmetic operations (addition, subtraction, multiplication, division), greater/less than, and conversion between intiger, float and string forms.

# What is the difference between the `+` operation on a number versus on a String?

When used on a pair of numbers, it executes the addition operation, and when used on a pair of strings, it appends them together in the order given. So, 1 + 2 will return 3, but '1' + '2' will return '12'.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

In string form, no, it won't work (at least, not the way you want it to). If you append `.to_i` to the end of the string to get `"20".to_i`, however, that converts the string into a number (in intiger form), which allows you to execute mathematical operations on it.

# What is the purpose of the `times` operation? Is that the same as `*`?

The purpose of the `times` operation is to do run a sequence of code a number of times equal to the intiger on which the operation is being executed. By contrast, `*` is the multiplication operation, so it's purpose is very different (Although, there are instances where either can be used to produce the same effect, such as when you want a string repeated).
