# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

I will be describing a regular expression that matches URLs. The regex has four parts. First, it checks for "http://" or "https://". Then, it matches the domain name. Third, it matches the top-level domain. And fourth, it matches the rest of the URL after the domain.

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

The regex starts and ends with ^ and $, respectively. These are called anchors and they define the start and end of the input string. They ensure that the string being validated conforms to the given pattern, which in this case is a URL.

### Quantifiers

The regular expression includes several quantifiers that specify how many times the preceding character or group should be matched. The first quantifier is '?', which means that the preceding 's' in 'https' is optional. The next quantifier is '\*', which matches zero or more occurrences of the preceding character or group. This is used for the path of the URL.

### Grouping Constructs

The regular expression has two groups, denoted by () brackets. The first group (https?:\/\/)? matches the optional "http://" or "https://" at the beginning of the URL. The second group ([\da-z\.-]+) matches the domain name.

### Bracket Expressions

Bracket expressions are used to match a character from a set of characters. In this regular expression, we have two bracket expressions: [\da-z\.-] and [a-z\.]. The first bracket expression matches any digit, lowercase letter, period, or hyphen. The second bracket expression matches any lowercase letter or period.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

Andy Barringer

- I'm a student full-stack developer
- GitHub: https://github.com/wabarringer
