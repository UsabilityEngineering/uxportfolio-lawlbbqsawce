<span align="center">
  <h1>Not So Regular Expressions</h1>
  <h2>Better than finding it yourself?</h2>
  <h3>by Kira Casto</h3>
  <h4>Apr 12, 2020</h4>
</span>
<br>
<p>Regular Expressions, or RegEx, is a concept that is sometimes criticized for its cryptic nature and reliance on a library of knowledge.
Is there truth to the daunting <strong>memorability</strong> of these expressions? Before answering this question, some background 
information is needed. RegEx are essentially just a method of looking for a pattern in a file. They allow for simple
or complex patterns, and can match things like digits or the possibility of dashes instead of spaces. This is done using a set of
syntax to construct a pattern to match to. Things like '[0-9]' would match all digits between 0 and 9, but one at a time. This means
that '01' would match '0' and '1' rather than '01'. Some symbols allow for flexibility in the number of matches. For example, adding
an asterisk after a pattern indicates to match the pattern as many times as possible. If there are no matches, zero is the maximum 
possible matches.</p>
<p>Now, that is a lot to take in. The individual parts of that information, however, are much smaller in comparison. As a whole, this
gives RegEx low <strong>learnability</strong>. If approached differently, however, RegEx can make progress in this category. The smaller
underlying concepts that make up RegEx have high <strong>learnability</strong> due to their small size and <strong>efficient</strong> syntax.
It is the concise nature of RegEx syntax, or the "alphabet" for RegEx, that can improve <strong>learnability</strong> in situations where the
same pattern covers multiple desired patterns. 
When trying to match one or more numbers that only has a dash with two or more numbers, those
words can even be matched to syntax definitions. One or more is '+' and numbers are '\d', so one or more numbers is \d+. Then there will only be
a dash when there are numbers to follow it. This means we can simply choose whichever works per case by adding an or condition. In RegEx, "or" is
a pipe character, or |. Thus our statement, "Digit, dash, digit(s) or one digit?" becomes (\d-\d+|\d)
This quality makes RegEx both great and awful at <strong>error tolerance</strong>, since it can
match the correct pattern even with improper syntax. However, this is not so helpful when it is not in fact the correct pattern and there will
not be any indications in most cases as to why this is. 

Ultimately, RegEx does tend to lack overall <strong>learnability</strong> for the layman. While the individual concepts that make up RegEx are
the opposite, the potential effort required to <strong>effectively</strong> match patterns will rely on the </strong>efficiency</strong> of the user's patterns.
For those to whom <strong>memorability</strong> comes naturally, RegEx could be the toolbelt they didn't know they were missing. For everyone else,
it may just be the toolbelt they didn't know they'd never use.</p>

[Return](../../../)
