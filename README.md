Osu-Regex-2022
# A into to Regex !


## Summary

Below will walk you through some of the core components of regex  such as Anchors, Quantifiers, Grouping Constructs, Bracket Expressions, Character Classes, OR Operators, Flags, and Character Escapes.

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
Regular expressions can be found in many different programming languages, but how they are used and implemented can very. Occasionally some characters may be used in different ways in different situations.
Sometimes a character has a relatively universal use. Below are some common regex components.
-Anchors
-Character sets
-Modifiers
### Anchors
In regular expressions, we can use anchors to check if the matching symbol is a starting symbol or ending symbol of an input string. Anchors have two types: 
The first type is the caret ^ this checks to see if the matching character is the first character of the input.
 the second type is the dollar sign $ which will check if a matching character is the last character of an input string.
### Quantifiers

### Grouping Constructs
Grouping constructs are used to describe the  subexpressions of a regular expression, and is also able to capture substrings of an input string.
 You can use grouping constructs to do the following:
-Match- is used for a sub-expression that is repeated in a input string.
-Apply- is used when a sub-expression  has multiple regular expression language elements.
-Include- is used when a sub-expression in a string is returned by the Regex.

### Bracket Expressions
A bracket expression can be either a matching list expression or a non-matching list expression.
and is used when a list consists of one or more expressions:character classes, ordinary characters, collating symbols, equivalence classes, collating elements, or range expressions.
### Character Classes
 character classes are In the realm of regular expressions, a character class is a set of characters enclosed within square brackets,
 and specifies the characters that will match with the single character in an input string.
### The OR Operator
When we try to build a logical “or” operation using regular expressions, we have a few approaches that we can use. the grouping and alternation provided by the regex are very good at what they do ,
 but when those provided are not able to be used , we are able to perform a second match using a separate regular expression using the "OR" expression.
### Flags
Flags also known as  modifiers this is because Flags are used to modify the output of regular expressions.
  Flags can be used in any order or combination, and are built into the Regex system.
-i	Case insensitive: Match will be case-insensitive.
-g	Global Search: Match all instances, not just the first.
-m	Multiline: Anchor meta characters work on each line.
### Character Escapes
A part of regex is Character Escaping some of these escapes can be expressed by -backslash's \ they are used in regular expressions to escape the next character.
 This allows us to included characters such as { } [ ] / \ + * . $ ^ | ? as matching characters.
 in order To use one of the special characters as a matching character, prepend it with \.
## Author

Ian shaw - https://github.com/irshaw