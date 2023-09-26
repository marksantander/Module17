# Email Checker

Email Checker was created and maintained by Aman Nurani. It provides a powerful email validating system for both development and production for Laravel. It uses fsockopen(), cURL and many more to validate email address exists or not in real world.

## Summary

This tutorial will explain how to use regex to validate email addresses.

^[a-zA-Z0-9.!#$%&'*+-/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$

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
To get the latest version, simply require the project using Composer:
^$ composer require aman00323/emailchecker
Once installed, You need to include Aman\EmailVerifier\EmailChecker to access methods for email verify.

### Anchors

Anchors match the beginning of the string, or the beginning or end of a word.  he following anchors are used in the email address regex pattern:

- ^: Matches the beginning of the string.
- <span class="math-inline">\: Matches the end of the string. ### **Character Classes** Character classes are special characters that match a set of      characters. The following character classes are used in the email address regex pattern: * `[a-zA-Z0-9.!#%&'*+-/=?^_{|}~-]+: Matches any alphanumeric character, period, exclamation point, hash symbol, dollar sign, percent sign, ampersand, apostrophe, asterisk, plus sign, hyphen, slash, question mark, equal sign, caret symbol, underscore, backtick, curly brace, pipe symbol, tilde, or hyphen.
- [a-zA-Z0-9-]+: Matches any alphanumeric character or hyphen.

### Quantifiers

Quantifiers are characters that specify how many times a character or character class must match. The following quantifiers are used in the email address regex pattern:

+: Matches one or more occurrences of the preceding character or character class.
*: Matches zero or more occurrences of the preceding character or character class.

### OR Operator

### Character Classes

^app(EmailChecker::class)->checkDisposableEmail('something@example.com','boolean'));
^app(EmailChecker::class)->setFromEmail('something@example.com','boolean'));
^EMAIL_CHECKER_SET_FROM='something@example.com'

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Email Checker was created and maintained by Aman Nurani. It provides a powerful email validating system for both development and production for Laravel. It uses fsockopen(), cURL and many more to validate email address exists or not in real world.

https://github.com/aman00323/email-checker

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
