# Go Regex Go
Regular expressions (i.e. Regex) aid search patterns via special characters. They can  be used to find and replace a character as well as validate items such as an email.

## Summary
The regular expression I will be explaining is: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

### Anchors
/`^`([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})`$`/
The `^` anchor represents the beginning of the string, with the following character (in this case `(`) being the start of the string. The `$` anchor signifies the end of the string.

### Quantifiers
/^([a-z0-9_\.-]`+`)@([\da-z\.-]`+`)\.([a-z\.]`{2,6}`)$/
Quantifiers set the string limits that your regex will match. Essentially, they determine the minimum and maximum amount of characters your regex will look for. They are greedy, which means they will match as many patterns as possible.
`+` - matches the pattern one or more times
`{2,6}` - will match a minimum of 2 to a maximum of 6 times

### OR Operator
`|`
There is no OR operator in this regex. 

### Character Classes
/^([a-z0-9_\`.`-]+)@([`\d`a-z\`.`-]+)\`.`([a-z\`.`]{2,6})$/

Character
`.` - Will match any character except \n (new line)
`\d` — Matches any numeral digit. This class is equivalent to the bracket expression 0-9.

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author


# See My Work:
https://github.com/AngerOverApathy
