# Regex-Tutorial-Email-Match

A Stater example to explain Regex

## Summary

This tutorial will explain to the reader how to match emails using the regex expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. 
For example this can be used when a user is logging into their account. The expression can be used to check if the user given email matches one in the database.

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

### Anchors

That anchors that are being used in the Regex expression are `^` which is used to indicate the start of a string, and `$` to indicate the end of the string.

### Quantifiers

The first quantifier in this regex is the `+` operator. What this does it match the preceding items 1 or more times. So in the case `^([a-z0-9_\.-]+)@` the `+` will match the information before the @ sign of the email given.

The second quantifier is `{2,6}`, which will allow a match range of 2-6 characters.

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

Created by Matthew Bull

https://github.com/Matt-Bull1/