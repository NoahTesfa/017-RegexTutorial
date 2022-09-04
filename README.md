# Regex Tutorial

This tutorial will go over the Regex expression used to validate an e-mail with the string 

## Summary

The e-mail regex is used among developers to confirm that e-mail addresses abide to the right syntax and assist in gaining better data. Elements needed for a valid email address are (user)@(domain).(extension)

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
The symbols $ and ^ are used to signify the pattern to view for everything inside the expression.

### Quantifiers
The e-mail regex uses the + quantifier in the User and Domain ruleset, quantifiers are used to control how many occurances of a characters are needed to make a match. The + quantifier idicates that at least one character needs to be in each string.

### Grouping Constructs
You can group up more than one character into a single unit by using parantheses around the expression.

### Bracket Expressions
Bracket expressions are used to match a specific set of solo characters, inside the brackets are range expressions.

### Character Classes
Character classes are short sequences of characters used to match a bigger set of characters, in the e-mail regex a character class example is [a-z,0-9].

### The OR Operator
The e-mail regex has no OR Operators.

### Flags
The e-mail regex has no Flags


## Author

Noah Tesfa | https://github.com/NoahTesfa