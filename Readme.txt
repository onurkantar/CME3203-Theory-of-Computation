HOMEWORK: Regular Expression to NFA

- In this assignment, you are supposed to write a JavaScript program, which converts a given regular
expression to NFA. The program takes two inputs from the user; a regular expression and a string to
test. It returns True if the NFA accepts the given string, otherwise returns False.
- For example
TestNFA (“(a+b)*ca*”, “aaabc”)
> True
TestNFA (“(a+b)*ca*”, “acabb”)
>False
TestNFA (“ba*+c*(ab*a)”, “cccaa”)
> True
TestNFA (“ba*+c*(ab*a)”, “bba”)
>False

- You may assume that:
- The regular expression only contains star, union and concatenation operators.
- The regular expression is syntactically correct. So you don’t need to check syntax errors.
- The regular expression contains only one-level parentheses. No nested parentheses exist.
- It should be a team work. The teams should have 2 or 3 members. No more or less members are
allowed. The uploaded file name must contain your team members’ student numbers.
- Add comment lines into your code to explain your solution.
Due date: 09/11/2018


##################
This assignment is not working well because of "Dynamic Epsilons Function" which finds the next states that machine can go
with an input then an epsilon or with just an epsilon if it is on the initial state.If you do not understand the code feel free
to mail me.
