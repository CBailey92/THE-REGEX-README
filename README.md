# THE-REGEX-README
THE REGEX README 
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
/ To denote the boundaries of the regular expression.
^ Represents the start of the current line in multi-line mode, otherwise the start of the string.
() Create Numbered Capturing Groups.
: Colon has no special meaning in Regular Expressions, it just matches a literal colon.
\ Backward slash is the escaping character.
/ Forward slash character is used to denote the boundaries of the regular expression.
? Matches exactly one character.
\/ Consider the slash as a string.
[] Match something that you are not familiar about a string you're looking for.
- Indicates a range that would match any number from 0 to 9.
+ Match the preceding character one or more times.
\d Matches any single digit.
. Represents the wildcard character.
{} Used to match exactly n instances of the proceeding character or pattern.
* The preceding character can be found 0 or more times.
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
