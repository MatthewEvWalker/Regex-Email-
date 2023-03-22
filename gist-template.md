# Email Regex 

Introductory paragraph (replace this with your text)

Regular expressions can be used to find certain character patterns inside a string. Within a string, you can also find and replace a single or sequence of characters. They are also commonly used for input validation. For legitimate e-mail addresses, this regex matches character information.

# Summary

The regex code that is used for emails is the following:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

# Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Author](#author)

# Regex Components:

## Anchors
The anchors used to contain this regular expression are: ^ to start, and $ to finish.


## Quantifiers
In this example, we used + to communicate there is another sequence to be matched as a quantifier. We also used {2,6} as another quantifer in order to specify the input as a minimum of 2 to a maximum of 6 characters.


## Grouping Constructs
There are three groups being captured in this example. Group #1 is the username of the e-mail account [a-z0-9_\.-]. The second group captures the domain name or e-mail service being used [\da-z\.-]. Finally, the third group captures the domain extension (i.e .com or .net) [a-z\.]{2,6}


## Bracket Expressions
As seen in the Grouping Constructs, there are also 3 bracket expressions. The information in the bracket expressions is opened and closed between brackets like this []. 

Bracket Expression #1: [a-z0-9_\.-] - This Regex allows case sensitive characters from a-z, numbers from 0-9 an underscore, periods and hyphens.

Bracket Expression #2: [\da-z\.-] - This Regex allows all digits, case sensitive characters from a-z, periods and hyphens

Bracket Expression #3: [a-z\.] - This Regex also allows all case sensitive characters from a-z and periods.



## Character Classes
In this regular expression, the charactor class /d is used which in Javasctipt classifies the use of any digit from 0 to 9.


# Author

My name is Matthew Walker and I hope you enjoyed this brief introduction to regular expressions.

Here is my link to [GitHub]( https://github.com/MatthewEvWalker?tab=repositories ) and [LinkedIn]( https://www.linkedin.com/in/matthew-walker-918422267/ )