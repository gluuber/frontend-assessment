Introduction
---
Thanks for considering me for the role and allowing me to take this frontend technical assessment.

Exercise 1
---
exercise1-desktop_mobile.html is styled to suit both desktop and mobile user agents.

Exercise 2
---
exercise2-tabs_accordion.html will load either Tabs or Accordion views depending on user agent.

###### Bonus points
* Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`.

Javascript bafoonery...

'b' + 'a' -> ba

++ 'a' -> NaN - 'Not a Number' is the result of attempting a unary operation on a string, (SyntaxError: invalid increment/decrement operand)

+ 'a' -> 'a'

Put the result to together to spell 'baNaNa' then convert it to lower case with toLowerCase().
