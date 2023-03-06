# REGEX: a brief explanation

This is a quick overview of regex and its uses.

## Summary

Regex is shorten from regular expression. It is a seqquice of characters that define a search pattern. These paterns are usualy used to find paterns in strings. 

Example: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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


In regex, anchors are used to signify the start and end of tests. These anchors are ^ and $. ^ is used to start the process while $ is used to finish it. 

If you look at the example above you can see how they are in their corisponding places.


### Quantifiers


In regex, quantifiries are used to set the limits of the string that your regex matches. Maximum and minimum numbers are some of the more frequintly used quantifires. 

Here are some that you will often see:
"+" matches 1 or more of the tokens that fallow
"*" matches 0 or more of the tokens that fallow
"?" matches 0 or 1 of the tokens that fallow

If you look at the example above you can see where "+" is in it and how a ")" directly proceedes both of them.


### Grouping Constructs


In regex, grouping constructs are used capture substrings of the subexpression that they have just deliniated through in an input string of a regular expression. 


### Bracket Expressions


In regex, a bracket expression is an expression that is closed inside a set of square brackets []. They only match a single character or collting element. 

If you look at the example above you will see there are several times the[]'s are used. 


### Character Classes


In regex, a character class is a spacific set of characters the are enclosed inside of square brackets. These are used to specify and match a character from a sertin string. 


### The OR Operator


In regex, a OR operator is ver siilar to a boolean. It can be used in a single grour or the whole expression. The simble used is "|". 


## Author

I am Alex Norrell. I am currently enrolled in a fullstack coding bootcamp through Georgia tech. I play music, I play games, and I play on computers. I just like to play around. 

https://github.com/alexnorrell