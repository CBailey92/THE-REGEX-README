# THE-REGEX-README
THE REGEX README 
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
/ to denote the boundaries of the regular expression.
^ represents the start of the current line in muliti-line mode, otherwise the start of the string.
() Create Numbered Capturing Groups.
: Colon has no special meaning in Regular Expressions, it just matches a literal colon.
\ Backward slash is the escaping character.
/ Forward slash charater is used to denote the boundaries of the regular expression.
? matches exactly one character.
\/ Consider the slash as a string.
[] match something that you are not familiar about a string you're looking for.
- indicates a range that would match any number from 0 to 9.
+ match the preceding character one or more times.
\d matches any single digit.
. represents the wildcard character.
{} Used to match exactly n instances of the proceeding charater or pattern.
* the preceding character can be found 0 or more times.
$ It matches the end of a line.
It is a URL that has https followed by colon. 
The next character matches a single digit of letters between a and z. 
The next character is a period is followed by a minus sign.
The next character is followed by a letter, period or  minus sign.
The next character is plus sign preceding is one time or several times.
The next character is slash and dot means there is a period.
The next character is a to z is followed by a period.
The next character is followed by the previous line between 2 and 6 times.
The next character is forward slash, w or 0.9.
The previous character can be found 0 or more times.
The last character is / .
