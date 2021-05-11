# Regex Tutorial
Introductory paragraph (replace this with your text)

## Summary

/[\w._%+-]+@[\w.-]+\.[a-zA-z]{2,4}/
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

/[\w._%+-]+@[\w.-]+\.[a-zA-z]{2,4}/
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors

Anchors are characters in a regular expression that begins and the end with the same character.  

Here are some Anchors examples below:

* `^` - start of string, or a start of a multi line pattern
* `$` - end of string or a multi line pattern. 


### Quantifiers

Qunatifiers are characters within the regular expression that specify how many characters, characters classes, or groups must be inputted to match.

Examples of Quanitifers

* `*` - matches a string that is zero or more
* `+` - matches a string that is one or more
* `?` - matches a string that either is zero or one
* `{}` -  matches a string that has exactly the number in the curly brackets unless specified with a comma. 


### OR Operator

OR Operators (logical disjuction) for a set of characters is true  and if one or more operands is true. Typically used with Boolean values. 

### Character Classes

Character Classes (Character Set) tells the regex engine to match only one out of serveral specific characters, such as digits, words, or white space

Examples of Character Classes:

* `\d` - matches a character that is a digit
* `\w` - matches a word character
* `\s` - matches a white space character 
* `\S` - matches a not white space character.
* `.` - matches any character



### Flags

Flags are optional parameters that we can add to a plain expression to make it search in a different way. Each flag is written in different characters which mean different words and explainations as seen below.

* `g` - Global which restarts any searches
* `m` - Multi-line, when enabled the Anchors (^ $) will match the start/end of a line.
* `i` - Insensitive, changes everything to case-insenstive

### Grouping and Capturing
Grouping coallates a string so it matches an entire complete block

Examples of Grouping:
* `()` - parentheses makes a capture group
* `(?:)` - using `?:` ends the capturing group
* `(?<>)` - using `?<>` adds a name to the group

### Bracket Expressions

Bracket Expressions are letters enclosed by a bracket `[]` matching any character between the brackets. 

### Greedy and Lazy Match

Greedy and/or Lazy Matching are quantaties that expand through searches and everything. 


### Boundaries

* `\b` - Something that is bound by a word at the start or end of a string
* `\B` - The opposite of the bound word above.
* `*` - Will match any word that is there


### Back-references


### Look-ahead and Look-behind

## Author

Johnny Wu

[GitHub Profile](https://github.com/WuJoh)
