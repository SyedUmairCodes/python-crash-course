# Whitespaces in Strings

Whitespace in programming means inserting spaces between characters or the end-of-line characters and even newlines are considered as whitespace. In python, whitespaces allow you to format your output to be more readable.

- Adding a `\t` before a string will insert a tab that's about four to five spaces before the string is printed on the console.
- Adding a `\n` will start each separate character in a newline.
- 

> You can also combine newlines and tabs to better format your output.

## Removing Whitespace

Whitespace is great for formatting the output of your programs to make them more easier for the user to understand but adding unnecessary whitespace in your code can lead to bugs and errors.

Stripping away whitespace from user input is also a common thing that most programs do since a space is a separate character, if a user enters their password and mistypes an extra space or tab then the password would be incorrect.

The `strip()` method in Python removes anykind of whitespace in a string and the `rstrip()` and `lstrip()` methods remove whitespaces from the right and left side of the string respectively.

## Removing Prefix and suffixes

A lot of times you could be working on a program where the user has to input a value that has a prefix or suffix. A URL for example has the `http://` as a prefix and the domain like `.com or .org` as a suffix.

These values can be removed by using the `removeprefix()` and `removesuffix()` methods respectively.
