Email Regex
A regex or regular expression is a formula that defines a search pattern using meta characters. The search parameters are vague to encompass the essence of what you are searching for. For example, the email regex will not return a specific email address, but any email address that can be found. 

Summary
The regex that we will be going over is:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

This expression is used to match an email address (any email addres on the document). This regex uses most of the regex components.

Table of Contents
Anchors
Quantifiers
OR Operator
Character Classes
Flags
Grouping and Capturing
Bracket Expressions
Greedy and Lazy Match
Regex Components
Anchors
^([a-z0-9_\.-]+) In this example the anchor is ^. It is searching for a string that starts with any number or letter. Denotes, the beginign of a string.

{2,6})$/ In this example the anchor is $ which is looking for ends with

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

taken all together, we are looking for an exact match that starts with any number or letter and ends with a domain name.

Quantifiers
([a-z0-9_\.-]+)

In this example the quantifer is '+'. We are searching for one or more letters a-z and one or more numbers 1-9.

OR Operator
[a-z0-9_\.-]

In this instance, the or opertor is []. So this example is searching for a letter a-z or number 0-9.

Character Classes
([\da-z\.-]+)

The character class in this instance is \d

This mataches a single character that is a number

Flags
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ In this example, the flag is the foward slash (/ /). This sets the boundery for this specific flag. It is like punctuation. We know that this is one complete regex from / to /

Grouping and Capturing
[a-z0-9_.-]+)

In this example, the grouping operator is () So, we are looking for a group of letters and number a-z and 0-9 in any combination.

Bracket Expressions
[a-z0-9_\.-] This code is used to find any letter (a-z) and number combination (0-9).

Greedy and Lazy Match
The operators * {} +

Author
My name is Camilo Restrepo and i am a beginner software developer studying coding at the University of Miami.