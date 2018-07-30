# Regular-Expressions
A list of useful regex for editing data.

### Put all rows in quotes
^(.+)$  
"$1"  
### Change end of line for coma
\n  
,  

### This.something.click
this.something.click === \bthis.\b[a-zA-Z]+.click
