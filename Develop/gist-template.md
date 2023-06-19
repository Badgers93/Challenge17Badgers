# Matching an Email Regex Tutorial

This tutorial will briefly show how regex is used to match emails with the expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. This is useful when making sure emails have been submitting with valid characters.

## Summary

A regex is a super powerful when searching for or manipulating text strings, especially text files. Regex is supported in all scripting languages as well as most general purpose programming languages. A code snippet of the regex is:
``` /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ ```
The following tutorial will explain the concepts of a regex with regard to matching an email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping](#grouping)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

Anchors indicate the beginning and ending of a string. (^) is used to indicate the beginning of a string, and ($) is used to indicate the ending.

### Quantifiers

The email matching regex uses the (+) operator to connect the username with the email provider. The regex also uses the quantifier ({2,6}) to indicate a match in the range of 2 to 6, which matches the characters a to z.

### Character Classes

One character class used in the email matching regex is the \d class, which matches a single character that is a digit.

### Grouping

The email matching regex uses grouping by placing parathenses around the username value, the email provider value, and the .com/.org/.etc value. This groups them together.

### Greedy and Lazy Match

The email matching regex uses the greedy match. A question mark after the quantifier used (+) would turn this into a lazy match. This is a greedy match because it expands the match as far as it can and gives back only if it must to satisfy the rest of the regex.

## Author

Badgers93 is a Cognitive Science student currently completing the full stack flex web bootcamp. https://github.com/Badgers93
