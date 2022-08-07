# Regex Tutorial Assignment, Email Address Example

In learning about regular expressions and the functional use of them, below is the breakdown understanding of an example regex. Regular expressions are useful for validation for improved overall UI. Some examples of regex uses include: email address, password, phone number, username, url, etc.

## Summary

The regular expression I have chosen to use will be for email address validation for my future web developments to ensure that when a potential client or employer goes to my portfolio webpage, they can submit a comment/request with a return email address for corespondence.

Email Address Regex: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Besides just validation, regex can be useful when users perform the Find commands on user interfaces. 

Below will breakdown the components of my chosen regex.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors

- ^ will match a string that starts with anything following this symbol
- $ will match a string that ends with anything preceding this symbol

### Quantifiers

- {2,6} will match any of the preceding characters inside of the regular brackets 2 up to 6 characters 

### OR Operator

- [] will match any characters within these brackets

### Character Classes

- \d will match any digit
- \. will match any character

### Grouping and Capturing

- () creates a capture group of tokens within the parentheses

### Bracket Expressions

- [a-z0-9_\.-] any letter lowercase a-z, any number 0-9, includes _ and - as well as any character
- [\da-z\.-] any digit, any letter lowercase a-z, any character, including -
- [a-z\.] any letter lowercase a-z, any character

## Author

My name is Ellie Sargent. I am currently enrolled in the Vanderbilt University Coding Bootcamp and eagerly look forward to becoming a full stack developer! My GitHub link is: https://github.com/ecsarg
