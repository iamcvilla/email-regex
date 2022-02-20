# Matching an Email Regex

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

## Summary

The following regular expression can be broken up in three sections. The first sections is focused on the "username" of the email. The second sections is the @ symbol. Lastly, the third section is the domain.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Capturing Group](#capturing-group)
- [Bracket Expressions](#bracket-expressions)

### Anchors

Anchors have special meaning in regular expressions. They do not match any character. Instead, they match a position before or after characters. The ^ anchor matches the beginning of the text. The $ anchor matches the end of the text.

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

### Character Classes

With a “character class”, also called “character set”, you can tell the regex engine to match only one out of several characters. Simply place the characters you want to match between square brackets.

### Capturing Group

Parentheses group the regex between them. They capture the text matched by the regex inside them into a numbered group that can be reused with a numbered backreference. They allow you to apply regex operators to the entire grouped regex.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
