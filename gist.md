# Title Matching a Hex Value

Regex expressions are regular expressions that use special characters which define or verify patterns in code and are usually used for validating that information matches the stored data inside of our databases.

## Summary

Matching a Hex Value:

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

This is a search pattern meant for matching hex values

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)

## Regex Components

### Anchors

/ Opening ^ anchors the regex pattern Denoting the start of a line. The $ denotes the end of the code.

### Quantifiers

The quantifiers in this expression are ? which means 0 or 1.

### Grouping Constructs

[ The Array Brackets indicate our grouping constructs. In this case all of the grouping tells us which characters are valid for te expression In this case we see for both statements it calls[a-f0-9] which means each space in the code may include either a letter a, b,c,d,e,f or a numerical digit 0,1,2,3,4,5,6,7,8,9]

### Bracket Expressions

{The curly braces call our quantities or how many characters we are looking to match. In this case we see both {6}&{3} so we know a hexcode can be either 6 or 3 characters long}

### Character Classes

There are no Character classes defined in this expression.

### The OR Operator

| the vertical absolute Value symbol is our or operator it symbolizes or in javascript (for loops) as well as regex language. For example this " red | blue " means red or blue.|

## Author

Melissa Lycan
http://www.github.com/MelissaLycan
