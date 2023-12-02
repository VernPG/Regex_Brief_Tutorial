# Computer Science for JavaScript: Regex Tutorial

Welcome to my Regex tutorial. The task was to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes and Flags](#character-classes)
- [The OR Operator](#the-or-operator)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors include symbols such as ^ and $.


### Quantifiers

A quantifier tells how many times a user wants to match a previous token. A quantifier can be a + added in to show how many times a word character can be matched, but it has to be a word character and not a space. 
![preview image](./Develop/images/Screenshot%202023-12-02%20at%201.44.30 PM.png)

### Grouping Constructs

A grouping construct describes the sub-expressions of a regular expression and captures the substrings of an input string. Examples are putting an expression in parentheses (expr). What is in the parentheses will be discovered.This is very helpful in running validators for an email to ensure the email returns as true based on the parameters set. The example is the 3 noted in {3} only matches the .com and not the .education. One would need to increase the number to match the expression for emails greater than the three used in .com. 
![preview image](./Develop/images/Screenshot%202023-12-02%20at%202.02.36 PM.png)

### Bracket Expressions

A bracket expression is a matching list of expressions or a non-matching list of expressions. An example would be using the hex value with the one match shown in the square brackets.
![preview image](./Develop/images/Screenshot%202023-12-02%20at%201.35.26 PM.png)

### Character Classes and Flags

A character class defines a det of characters so they will match an input string. Example below shows the matches used with a global flag along with a lazy match.With the global flag turned on, it will recognize all the matches associated with the expression. Please note the /g to indicate the global flag turned on. 
![preview image](./Develop/images/Screenshot%202023-12-02%20at%201.36.42 PM.png)
![preview image](./Develop/images/Screenshot%202023-12-02%20at%201.37.16 PM.png)


### The OR Operator

A bracket expression is a matching list of expressions or a non-matching list of expressions and does not require the string to match all of the requirements. The OR operator always finds a zero length match. 
![preview image](./Develop/images/Screenshot%202023-12-02%20at%201.41.13 PM.png)

### Character Escapes

Using the backslash \ before the quantifier tells regex to look for what is entered following the \. This is seen in the example of creating a regex to validate an email. However, any special character added inside a bracket expression will lose any significance including the backslash \.
![preview image](./Develop/images/Screenshot%202023-12-02%20at%201.44.30 PM.png)

## Author

My name is Veronica Perez, and I am a UoM Full stack Bootcamp student who is currently becoming familiar with Regex only using it so far to create validation for email and password functions. I used https://regex101.com/ to run the examples. 


[My Repos can be found HERE](https://github.com/VernPG)